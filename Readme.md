# Docker Commands
### 1. docker –version

This command is used to get the currently installed version of docker

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/1.png?raw=true)

<br />

### 2. docker pull

Usage: docker pull <image name>

This command is used to pull images from the docker repository(hub.docker.com)

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/2.png?raw=true)

<br />

### 3. docker run

Usage: docker run -it -d <image name>

This command is used to create a container from an image

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/3.png?raw=true)

<br />

### 4. docker ps

This command is used to list the running containers

Course Curriculum
Docker Certification Training Course

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/4.png?raw=true)

<br />

### 5. docker ps -a

This command is used to show all the running and exited containers

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/5.png?raw=true)

<br />

### 6. docker exec

Usage: docker exec -it <container id> bash

This command is used to access the running container

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/6.png?raw=true)

<br />

### 7. docker stop

Usage: docker stop <container id>

This command stops a running container

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/7.png?raw=true)

<br />

### 8. docker kill

Usage: docker kill <container id>

This command kills the container by stopping its execution immediately. The difference between ‘docker kill’ and ‘docker stop’ is that ‘docker stop’ gives the container time to shutdown gracefully, in situations when it is taking too much time for getting the container to stop, one can opt to kill it

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/8.png?raw=true)

<br />

### 9. docker commit

Usage: docker commit <conatainer id> <username/imagename>

This command creates a new image of an edited container on the local system

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/9.png?raw=true)

<br />

### 10. docker login

DevOps Training
This command is used to login to the docker hub repository

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/10.png?raw=true)

<br />

### 11. docker push

Usage: docker push <username/image name>
This command is used to push an image to the docker hub repository

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/11.png?raw=true)

<br />

### 12. docker images

This command lists all the locally stored docker images

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/12.png?raw=true)

<br />

### 13. docker rm

Usage: docker rm <container id>

This command is used to delete a stopped container

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/13.png?raw=true)

<br />

### 14. docker rmi

Usage: docker rmi <image-id>

This command is used to delete an image from local storage

![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/14.png?raw=true)

<br />

### 15. docker build

Usage: docker build <path to docker file>

This command is used to build an image from a specified docker file


![docker command](https://github.com/royparsaoran17/docker-command/blob/main/images/15.png?raw=true)