Video link : ` https://www.youtube.com/watch?v=OhnTMWmfTBE&list=PL0tP8lerTbX1m-Z1Dj7M-k-PuKDNJkRul&index=6 `

# Docker

`what is a Docker ?` - `Docker is not the only way to create a Container but it's the most popular one`
- Docker is a containerization platform for developing, packaging, shiping and running application 
- we can say that docker provides us a platform to perfrom SDLC operation on our project.
- i.e. Development, testing, deploying etc.
- Docker let us the ability to run an application in an isolated enviroment known as a container.
- It makes deployment and development efficient.

`What is a Container ?`
- It's a way to package an application with all the necessary dependencies and configurations.
- It can be easily shared.
- This makes development and deployment efficient.

# Architecture
![Docker Architecture](misc/Architecture.png)
- Here C1, C2, C3 are container 1, 2, 3 respectively.
- These containers are issolated from each other. 

# Difference between Docker and VM's (Virtual Machine's)
![Difference Between Docker and Virtual Machine's](misc/Diff_Docker_VM.png)


## Main components of Docker
- Docker File -> `Simple text file to write all the configurations/ instructions to build the image and use to build the docker image with the help of docker Engine`
- Docker Image -> `Single file with all the dependencies and libraries to run the project/ program`
- Docker Container -> `Process/ Instance with all necessary dependencies and libraries`
- Docker Registry -> `It's a central repo for storing and distributing Docker Images.`

![Chart](misc/Docker_file-Image.png)