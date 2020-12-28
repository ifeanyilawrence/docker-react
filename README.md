# Docker-React

docker-react is a test project showing how to containerise a React app using docker.

## Features
* Docker, docker-compose
* Travis-ci CI/CD configuration
* Deployment with AWS Elastic Beanstalk

## Usage

* In dev environment
```bash
docker-compose -f docker-compose-dev.yml up --build
```

## Description
* It contains a bootstraped React app using create-react-app
* No special React component, just the default components provided by the create-react-app
* It contains a Dockerfile, Dockerfile.dev, docker-compose-dev.yml & docker-compose.yml for running the container in dev & prod environment
* The repo includes a travis-ci yml configuration file to show how to configure travis yml file.
* The parameters should be changed accordingly for the elasticbeanstalk config.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
