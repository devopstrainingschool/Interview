# Docker Questions
## 1- What is a virtualization?
### Virtualization is the process of running a virtual instance of a
### computer system in a layer abstracted from the actual hardware
## 2- What is a hypervisor?
### A hypervisor, also known as a virtual machine monitor or VMM, is software that creates and runs virtual machines (VMs).
## 3- What are the type of hypervisors?
### A type 1 hypervisor acts like a lightweight operating system and runs directly on the host’s hardware, 
### A type 2 hypervisor runs as a software layer on an operating system, like other computer programs
## 4- What is a container?
### It is a layers of images having Linux base Image.
## 5- What is the command to list docker running containers?
### docker ps
## 6- What is the command to list all docker containers?
### docker ps -a
## 7- What is the command to stop a container?
### docker stop container_name(or ID)
## 8- What command to use if you want to remove a container?
### docker rm container_name
## 9- How to see docker version?
### docker version
## 10- what command to see all docker images locally?
### docker images
## 11- Let say we want to run a docker image yannickeboo/webapp:v1 on port 8080, what is the command?
### docker run -itd -p 8080:8080 yannickeboo/webapp:v1
## 12- what is the command to see inside a conatiner with more details?
### docker inspect container_name
## 13- How to see the logs inside a running container?
### docker logs container_name(or ID)
## 14- What is a command to pull an image locally?
## 15- What is the command to run a command inside a conatiner?
### docker exec container_ID command_to_execute
### for example, docker exec 386hdj pwd
## 16- what is the command to build a docker image?
# 17- What is the command to push docker image to remote artifactory?
