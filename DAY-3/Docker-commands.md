**DOCKER COMMANDS**
1. docker version
We usually start by finding the installed version of docker that we are working on.

2. docker search mysql
The “docker search” command searches for specific images through the Docker hub. This command returns the specific information, including image name, description, automated, official stars, etc.

3. docker pull
As the name suggests, this command pulls a specific image from the Docker Hub. All you have to do is use the command ‘docker pull’ along with the name of the image.

4. docker run 
This command is used to create a container from an image

5. Docker ps
This command is used to list all the running containers in the background.

6. Docker stop 
The ‘docker stop’ command stops a container using the container name or its id.

8. Docker kill
This command is used to stop the container immediately by killing its execution. While the ‘docker stop’ command helps shut down the container in its own time, the ‘docker kill’ command stops it at once.

9. docker exec 
This command is used to access the container that is running.

10. docker login
This command helps you to log into your docker hub. As you try to log in, you will be asked to give your docker hub credentials. 

11. Docker commit 
This command is used to create or save an image of the edited container on the local system. 

12. docker push 
This command helps push or upload a docker image on the repository or the docker hub

13. docker network 
The ‘docker network’ command is used to know the details of the list of networks in the cluster.

14. docker rmi 
This command is used to free up some disk space. The image id is used to remove the image while using this command.

15. docker ps -a
This command is used to know the details of all the running, stopped, or exited containers.

16. docker copy
This command copies a file from docker to the local system.

18. docker logs   
This command is used to check the logs of all the docker containers with the corresponding contained id mentioned in the command.

19. docker volume 
This command creates a volume so that the docker container can use it to store data.

19. docker logout 
This command will log you out of the docker hub.
