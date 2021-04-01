# Introduction 
A simple flask application that prints "Hello World" in a website. The main objective of this project was to introduce myself to docker.  

# Getting Started
1.) Navigate to project directory
From the command window, cd into your desired project location.

For example:
cd user/documents

2.) Build docker image
$ docker build -t simple-flask-app:latest .
Run the Docker container using the command shown below.

3.) View docker images
$ docker images

4.) Run docker image
$ docker run -d 5000:5000 simple-flask-app 

5.) Stop the docker container
$ docker ps -a #lists call containers running
$ docker rm -f "container string from above"



