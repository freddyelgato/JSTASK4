# JSTASK4 - "Hello World" Application in JavaScript

This project is a simple "Hello World" web application created in JavaScript and deployed in a Docker container. You can run it locally and access it in your browser.

## Requirements
- **Docker**: [Install Docker](https://www.docker.com/get-started) if you don’t have it yet.

## Installation Instructions

1. **Clone this repository**:
   ```bash
   git clone https://github.com/freddyelgato/jstask4.git

2. **Run the application in Docker**:
   ```bash
   docker run -d -p 5173:5173 --name jstask4 2424833f/jstask4
 - **d**: Runs the container in detached mode.
 - **p8080**: Maps container port 5173 to your machine's port 5173.

3. **Access the application in your browser to see the "Hello World" message**:
   ```bash
   http://localhost:5173
   
## Useful Commands
- View containers: `docker ps`.
- Stop the container: `docker stop JSTASK4`.
- Remove the container: `docker rm JSTASK4`.

## Enlaces
- Docker Hub Image: [docker ps](https://hub.docker.com/r/2424833f/jstask4).

