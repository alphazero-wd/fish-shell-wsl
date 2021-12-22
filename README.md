### WSL
- Install Ubuntu in Microsoft Store

- Run Ubuntu and run the command to upgrade the repository:<br />
`sudo apt update`

### Fish Shell on WSL

- Install Fish<br />
`sudo apt install fish`

- Run Fish Shell<br />
`fish`

- Install curl<br />
`sudo apt install curl`

- Install powerline fonts<br />
`sudo apt install fonts-powerline`

- Install Oh My Fish<br />
`curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install | fish`

- Set fish as a default shell<br />
`chsh -s /usr/bin/fish`


### NodeJS<br />
- Install NVM</br>
`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`

- Install NVM to update NodeJS for Oh My Fish<br />
`omf install https://github.com/fabioantunes/fish-nvm`<br />
`omf install https://github.com/edc/bass`

- Install latest NodeJS version<br />
`nvm install 16.13.1`

- Switch Node versions:<br />
`nvm use 16.13.1`

### PostgreSQL<br />
- Install PostgreSQL on WSL:<br />
`sudo apt install postgresql postgresql-contrib`

- Confirm installation:<br />
`psql --version`

- Create a postgres user and set the password for the user postgres:<br />
`sudo passwd postgres`

- Start running the database:<br />
`sudo service postgresql start`

- Connect to the postgres service and open the psql shell: <br />
`sudo -u postgres psql`

- Change password in case authentication failed:<br />
`ALTER USER postgres WITH PASSWORD 'password';`

## Git

- Add a PPA (Personal Package Archive), maintained by the Git team for Ubuntu users<br/>
`sudo add-apt-repository ppa:git-core/ppa`

- Update git<br/>
`sudo apt install git`
