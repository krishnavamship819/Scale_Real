# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

## Docker build image

### `docker build -t krish-vamshi`

## Docker run container

### `docker run -it -p 3000:3000 krish-vamshi`

## Docker Volume run container

### `docker run -it -p 3000:3000 -v PWD:/usr/src/app -v /usr/src/app/node_modules -e CHOKIDAR_USEPOLLING=true kv-react-docker-starter`

## Docker compose build image

### `docker-compose build`

## Docker compose run container

### `docker-compose up`

## Docker compose run container in detached mode

### `docker-compose up -d`

## Docker compose check running container status

### `docker ps`

# TO Run The project

## First Build the docker Compose

### `docker-compose build`

## Run the Image

### `docker-compose up`

## Inorder see the logs

First get the running conyainer ID and use the follwing command

### `docker logs container_ID -f`

### You can access the React-app runing in container through

Open [http://localhost:8080](http://localhost:8080) to view it in your browser.
