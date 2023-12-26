**Docker objects**

When you use Docker, you are creating and using images, containers, networks, volumes, plugins, and other objects. This section is a brief overview of some of those objects.

**Images**

An image is a read-only template with instructions for creating a Docker container. Often, an image is based on another image, with some additional customization. For example, you may build an image which is based on the ubuntu image, but installs the Apache web server and your application, as well as the configuration details needed to make your application run.

You might create your own images or you might only use those created by others and published in a registry. To build your own image, you create a Dockerfile with a simple syntax for defining the steps needed to create the image and run it. Each instruction in a Dockerfile creates a layer in the image. When you change the Dockerfile and rebuild the image, only those layers which have changed are rebuilt. This is part of what makes images so lightweight, small, and fast, when compared to other virtualization technologies.

**Containers**

A container is a runnable instance of an image. You can create, start, stop, move, or delete a container using the Docker API or CLI. You can connect a container to one or more networks, attach storage to it, or even create a new image based on its current state.

By default, a container is relatively well isolated from other containers and its host machine. You can control how isolated a container's network, storage, or other underlying subsystems are from other containers or from the host machine.

A container is defined by its image as well as any configuration options you provide to it when you create or start it. When a container is removed, any changes to its state that aren't stored in persistent storage disappear.

**Example docker run command**

The following command runs an ubuntu container, attaches interactively to your local command-line session, and runs /bin/bash.

 _docker run -i -t ubuntu /bin/bash_

1. When you run this command, the following happens (assuming you are using the default registry configuration):
2. If you don't have the ubuntu image locally, Docker pulls it from your configured registry, as though you had run docker pull ubuntu manually.
3. Docker creates a new container, as though you had run a docker container create command manually.
4. Docker allocates a read-write filesystem to the container, as its final layer. This allows a running container to create or modify files and directories in its local filesystem.
5. Docker creates a network interface to connect the container to the default network, since you didn't specify any networking options. This includes assigning an IP address to the container. By default, containers can connect to external networks using the host machine's network connection.
6. Docker starts the container and executes /bin/bash. Because the container is running interactively and attached to your terminal (due to the -i and -t flags), you can provide input using your keyboard while Docker logs the output to your terminal.
7. When you run exit to terminate the /bin/bash command, the container stops but isn't removed. You can start it again or remove it.

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

11. docker commit 

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
