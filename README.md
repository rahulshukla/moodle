# install moodle using docker compose

- Clone the git repository

- install docker-compose if not installed yet
```sh
sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

docker-compose --version
```
- Run the moodle and mongo db containers
```sh
cd moodle
sudo docker-compose up -d 
```
- check the browser 
http://devlms.simplilearn.com:8080  [ make sure your hosts file has has devlms.simplilearn.com entry ]
