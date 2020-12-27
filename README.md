# Docker-React

docker-react is a test project showing how to containerise a React app using docker.

## Features
* It contains a bootstraped React app using create-react-app
* No special React component, just the default components provided by the create-react-app
* It contains a Dockerfile, Dockerfile.dev for running the container in dev environment and a docker-compose.yml file

## Usage

* using docker
```bash
docker build .
docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/usr/app <image_id_from_prev_command>
```

* using docker-compose
```bash
docker-compose up --build
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
