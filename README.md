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

### docker cp 
'sample.txt' file copied from docker container to host
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/0209e54d-c5b2-45b8-b146-39ff69326edd)

### docker stats
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/3829e617-27cb-4e4a-8b5f-e40369f918da)

### docker top
The output of the command is saved in **output.txt**
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/4808efab-5dd8-4721-8ca3-e91c1e41ac3c)
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/9272b461-95ee-4a7f-8c3a-e4193b93ace6)

### docker start
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/ed83ade1-db60-4737-857d-ccd99d06f660)

### docker pause
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/b36ed8c0-6408-498f-be58-0a37224ed7cf)

### docker unpause
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/4c39459b-4976-4bfa-88b7-c7e8aae2cf72)

### docker rename
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/aab7c740-d4eb-4639-b1a1-6d827de680cf)

### docker attach and docker wait
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/f6f15143-46a6-4fa9-9bb7-1daa7f4ab334)

### docker update 
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/12074b1a-0714-45be-bcdb-6a78c1f68558)

## docker restart
![image](https://github.com/AdeelAhmedIqbal/DICE/assets/62285793/e814ecf1-2924-4504-91d0-42faaabbcf3f)








