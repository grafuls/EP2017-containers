# EP2017-containers
Dockerfiles for EP2017 "Dockerizing pytest" talk

## Requirements 
- docker-ce > 1.7

## Building images
```bash
cd jenkins_docker
docker build -t jenkins:ep2017 .
```
```bash
cd jenkins_slave
docker build -t java:ep2017 .
```
* Note: this container build requires the jenkins contanier to be running at the time of building

## Running the composer
```bash
docker-compose up
```

# You can then access your jenkins instance @localhost:8080
