---
tags: docker
---

# Docker architecture

First, remember, that Docker is a client-server application, it consists of Docker client and Docker server (also known as the Docker daemon). 
The Docker client command line tool talks with the Docker server and asks it to do things. 
One of these things is Docker build: building a new Docker image. The Docker server can run on the same machine as the client or in a virtual machine, that also can be local, remote or in the cloud.