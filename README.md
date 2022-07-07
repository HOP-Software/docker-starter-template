# docker-starter-template for Hop Digital
Docker Compose workflow that sets up a LAMP network of containers for local WordPress development.

## Usage
To get started, make sure you have [Docker installed](https://docs.docker.com/docker-for-mac/install/) on your system, and then clone this repository.

Next, navigate in your terminal to the directory you cloned this, and spin up the containers for the web server by running `docker-compose up -d --build site`.

Remove container 
`docker-compose down`

Create container 
`docker-compose up -d`

### Database
Comment the line if you need create a new database 
./schema/:/docker-entrypoint-initdb.d 