## Student

Micaela Belen Mera Rodriguez

## Project Description

This project is a simple React application running inside a Docker container.

The application displays :

<h1>Coding 1</h1>

The application can be accessed at :

http://localhost:7775

## Requirements

Before running the project, make sure you have:

- Docker Desktop
- Node.js
- npm

## Run the Project

### 1. Build the Docker image

Open PowerShell in the project folder and run :

docker build -t coding-assignment11 .

### 2. Run the Docker container

Run : 

docker run -p 7775:3000 coding-assignment11

### 3. Open the application

Open your browser and go to :

http://localhost:7775

## Stop the Application

Press :

Ctrl + C

in PowerShell to stop the container.

## Docker

The React application runs on port 3000 inside the Docker container. 
Port 7775 on the computer is connected to port 3000 inside the container.
