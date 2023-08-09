# DICE DEVOPS Assignment 1
## Part 1
### Dockerfile Explanation
- I used the official **python:3.8** base image
- Set **/app** as my working directory-
- Expose port '8080' for external access
- Set command to run my sample Python program
### Python program explanation
prints *Hello World*
### Installation Guide

Build the docker image

![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/d4f1e01c-e866-406c-b836-08158299c70d)

Run the docker container

![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/6412eabd-a890-460b-bd66-ee8061b1988b)

## Part 2: Docker Containers with Commands 
### I AM USING NGINX IMAGE FOR THIS PART!!!
### docker ps
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/b6e22842-bab8-48cb-96a0-346d836d9d0c)

### docker logs
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/ed95c283-e857-4595-b419-02a88d266b22)

### docker inspect
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/9b3e8161-4211-4091-a2ff-b44041917527)

### docker exec
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/1745e19d-c634-4e3f-8bdc-f34120c09bcf)

### docker commit 
'custom-nginx' image created from original container
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/ff4f22a0-0758-491d-ba79-6646f672a00a)





