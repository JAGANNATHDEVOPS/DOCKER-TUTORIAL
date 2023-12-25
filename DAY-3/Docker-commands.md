**DOCKER COMMANDS**
1. docker version
We usually start by finding the installed version of docker that we are working on. Here is how to find it –
_
Client: Docker Engine - Community
 Version:           24.0.7
 API version:       1.43
 Go version:        go1.20.10
 Git commit:        afdd53b
 Built:             Thu Oct 26 09:07:41 2023
 OS/Arch:           linux/amd64
 Context:           default

Server: Docker Engine - Community
 Engine:
  Version:          24.0.7
  API version:      1.43 (minimum version 1.12)
  Go version:       go1.20.10
  Git commit:       311b9ff
  Built:            Thu Oct 26 09:07:41 2023
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.6.26
  GitCommit:        3dd1e886e55dd695541fdcd67420c2888645a495
 runc:
  Version:          1.1.10
  GitCommit:        v1.1.10-0-g18a0cb0
 docker-init:
  Version:          0.19.0
  GitCommit:        de40ad0_

  2. docker search mysql
The “docker search” command searches for specific images through the Docker hub. This command returns the specific information, including image name, description, automated, official stars, etc. Here is how to use it – 
_NAME                            DESCRIPTION                                     STARS     OFFICIAL   AUTOMATED
mysql                           MySQL is a widely used, open-source relation…   14731     [OK]
mariadb                         MariaDB Server is a high performing open sou…   5620      [OK]
percona                         Percona Server is a fork of the MySQL relati…   622       [OK]
phpmyadmin                      phpMyAdmin - A web interface for MySQL and M…   918       [OK]
bitnami/mysql                   Bitnami MySQL Docker Image                      105                  [OK]
bitnami/mysqld-exporter                                                         6
cimg/mysql                                                                      2
ubuntu/mysql                    MySQL open source fast, stable, multi-thread…   55
rapidfort/mysql                 RapidFort optimized, hardened image for MySQL   25
rapidfort/mysql8-ib             RapidFort optimized, hardened image for MySQ…   9
google/mysql                    MySQL server for Google Compute Engine          25                   [OK]
rapidfort/mysql-official        RapidFort optimized, hardened image for MySQ…   9
hashicorp/mysql-portworx-demo                                                   0
elestio/mysql                   Mysql, verified and packaged by Elestio         0
bitnamicharts/mysql                                                             0
newrelic/mysql-plugin           New Relic Plugin for monitoring MySQL databa…   1                    [OK]
databack/mysql-backup           Back up mysql databases to... anywhere!         105
linuxserver/mysql               A Mysql container, brought to you by LinuxSe…   41
mirantis/mysql                                                                  0
linuxserver/mysql-workbench                                                     54
vitess/mysqlctld                vitess/mysqlctld                                1                    [OK]
eclipse/mysql                   Mysql 5.7, curl, rsync                          1                    [OK]
drupalci/mysql-5.5              https://www.drupal.org/project/drupalci         3                    [OK]
drupalci/mysql-5.7              https://www.drupal.org/project/drupalci         0
datajoint/mysql                 MySQL image pre-configured to work smoothly …   2                    [OK]_

3. docker pull
As the name suggests, this command pulls a specific image from the Docker Hub. All you have to do is use the command ‘docker pull’ along with the name of the image.
4. Docker run 
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
