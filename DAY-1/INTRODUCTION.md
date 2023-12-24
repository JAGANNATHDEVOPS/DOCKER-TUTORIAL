**DOCKER OVERVIEW**
Docker is an open source platform designed to build, distreibute & run application inside a container.

**WHAT IS DOCKER**
Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications. By taking advantage of Docker's methodologies for shipping, testing, and deploying code, you can significantly reduce the delay between writing code and running it in production.

**WHAT IS CONTAINER**
Containers are packages of software that contain all of the necessary elements to run in any environment. In this way, containers virtualize the operating system and run anywhere, from a private data center to the public cloud or even on a developer's personal laptop.

**VMs CONTAINERs**
_VMs_
1. More time to create
2. Dedicated OS
3. Specific bin & lib
4. Dedicated resources
5. Memory wastage
6. Low performance
7. Complex configuration
8. Heavy weight(GBs)
9. Memory can't share

_CONTAINERs_
1. Less time to create
2. Common O.S
3. Common bin / lib
4. Common resources
5. No memory wastage
6. High performance
7. Simple configuration
8. Light memories(mbs)
9. Can share memory

**Hardware compatibilty:**
In hyperviser solution a dedicated OS for each virtual machine makes it more expensive & slow to respond as compared to a Docker container application.
Any virtual machine created in a specific hypervisor platform can't run on other hypervisor platform.

**Process isolation & security**
In docker containers, each application or container is isolated from others, but they use the same root.
This provides the advantages of simplified management, although it also leads to a few disadvantages.
For instance, if the root is compromised, the host container could be at risk.

**Docker history**
Docker, launched in 2013.

**Support Platform**
1. Various linux distributions(Ubuntu, Fedora, RHEL, Centos, etc)
2. Also in windos
