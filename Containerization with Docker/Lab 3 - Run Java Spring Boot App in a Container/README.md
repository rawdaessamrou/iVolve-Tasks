# Lab 3: Run Java Spring Boot App in a Container

## Overview
This lab demonstrates how to containerize a Java Spring Boot application using Docker. It covers cloning the source code, writing a Dockerfile, building a Docker image, running a container, and verifying the application is accessible via a web browser.

## Dockerfile
The Dockerfile uses a Maven base image with Java 17, sets a working directory, copies the application source code into the container, builds the app using `mvn package`, and runs the generated JAR file. Port 8080 is exposed to allow external access.

## Tools Used
- **Docker** – Used to build the image and run the container.
- **Maven** – Used inside the container to build the Java application.
- **Java 17** – Runtime for the Spring Boot application.
- **Git** – Used to clone the source code from GitHub.

## Outcome
A Docker image named `app1` was built from the source code and a container named `container1` was launched from it. The Spring Boot application was accessible at `localhost:8080`, returning the expected response. The container was then stopped and removed.

### Commands History
![Commands History](Comands.png)

### Application Running
![Application Running](Application-Running.png)
