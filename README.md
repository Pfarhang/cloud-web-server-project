# Cloud Web Server Project

This project demonstrates how to deploy a web server in the cloud using Linux and Docker.

## Technologies
- Linux (Ubuntu)
- Docker
- Nginx
- Cloud Infrastructure

## Project Steps

1. Create a cloud server
2. Install Docker
3. Deploy a web server container
4. Access the server through a public IP

## Goal

The goal of this project is to demonstrate cloud infrastructure and container deployment skills.
## Run the Project

Build the Docker image:

docker build -t cloud-web-server .

Run the container:

docker run -p 80:80 cloud-web-server

Then open in your browser:

http://localhost
