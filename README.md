# Dockerizing a Simple Node.js Application

This project demonstrates how to containerize a simple Node.js web application using Docker.

## Technologies Used
- Node.js
- Express.js
- Docker

## Project Steps

1. Created a simple Node.js web application
2. Wrote a Dockerfile to containerize the application
3. Built a Docker image
4. Ran the container locally
5. Pushed the Docker image to Docker Hub

## Build Docker Image

docker build -t docker-node-app .

## Run Docker Container

docker run -p 3000:3000 docker-node-app

## Application Output

When the container runs successfully, visiting:

http://localhost:3000

will display:

Dockerized Node.js App Running 🚀

## Docker Hub Image

https://hub.docker.com/r/ashwinpoojary/docker-node-app
