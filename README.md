# Dockerized 3D Boxes Background

## Description
This project demonstrates containerization of a frontend application using Docker and Nginx.

## Build Docker Image
```bash
docker build -t 3d-box-app .

## Run Container
docker run -p 8082:80 3d-box-app

## Output
Application runs on:
http://localhost:8082

## docker ps
Used to verify container is running.

## Screenshots

### Docker Build
![Docker Build](build.png)

### Running Container
![Running Container](run.png)

### docker ps Output
![Docker PS](ps.png)

### Application Output
![Output](output.png)

## Conclusion
Docker container successfully built and deployed.
