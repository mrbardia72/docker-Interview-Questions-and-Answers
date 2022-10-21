# Docker Commands Interview Questions and Answers

## What are some popular container orchestration systems?
   Some popular container orchestration systems are Kubernetes, Apache Mesos, and Docker Swarm.

## Which of the following commands creates a new container instance?
   docker run

## docker start
The docker start command is used to start one or more stopped containers.

## docker stop
The docker stop command is used to stop one or more running containers.

## docker build
The docker build command is used to build an image from a Dockerfile.

## docker run
The docker run command is used to run a container from an image.

## docker create
 The docker create command is used to create a new container from an image. This command will create a new container but will not start it. To start the container, you will need to use the docker start command.

## docker run
The docker run command is used to launch a new container from a given image. This command takes in a number of different parameters and options that can be used to customize the container that is created. For example, you can use the docker run command to specify the name of the new container, the port mapping for the container, the environment variables for the container, and so on.

## docker instantiate
The docker instantiate command creates a new container from a given image, but with a different set of environment variables than the original image. This can be useful for creating different versions of the same image with different settings.

## Which of the following commands would be most appropriate for creating a new container?
The most appropriate command for creating a new container would be “docker run.” This command will create a new container with the specified image and run it.

## docker launch
There are a few different ways to launch a Docker container. The most common way is to use the “docker run” command. This command will launch a new container with the specified image.

## docker ps
The “docker ps” command will list all of the running containers on your system.

## docker stop
The “docker stop” command will stop a running container.

## docker build
The docker build command is used to create a new Docker image from a given Dockerfile. This command will take in the path to the Dockerfile as its first argument, and then an optional tag name for the new image as its second argument. If no tag name is specified, then the new image will be given the “latest” tag by default.

## docker run
The docker run command is used to launch a new container from a given image. This command takes in a number of different parameters and options that can be used to customize the container that is created. For example, you can use the docker run command to specify the name of the new container, the port mapping for the container, the environment variables for the container, and so on.

## docker create
The docker create command is used to create a new container from an image. This command will create a new container but will not start it. To start the container, you will need to use the docker start command.

## Which of the following commands can be used to remove all unused images on your machine?
The docker system prune command can be used to remove all unused images on your machine.

## docker rmi -f $(docker images)
This command will remove all of the images stored on your local machine.

## docker rm -f $(docker ps -a -q)
Answer: This command will remove all of the containers stored on your local machine, regardless of whether or not they are running.

## docker rm -f $(docker images)
This command will remove all of the images that are currently stored in your Docker instance. This can be useful if you want to start from scratch or if you want to clear up some disk space.

## docker system prune -a
The docker system prune command will remove all unused data from your Docker system. This includes things like unused containers, images, volumes, and networks. The -a flag will also remove any data that is not associated with a running container, which can be useful for cleaning up after experiments or one-off tasks.

## docker cleanup -all
The docker cleanup command is used to remove all unused containers, images, and volumes from your system. This can be helpful if you are running low on disk space, or if you want to clean up your system to prepare for a new Docker installation.

## Which of the following commands attaches your terminal session to a running container?
docker attach

## docker attach [container-name]
The docker attach command will allow you to attach to a running container. This is useful if you want to check on the status of a running container or if you need to troubleshoot an issue.

## docker build [path-to-Dockerfile]
Answer: The docker build command is used to build a Docker image from a Dockerfile. This is the first step in creating a container.

## docker commit [container-name] [new-image-name]
Answer: The docker commit command will create a new image from a container. This is useful if you have made changes to a container and want to save those changes as a new image.

## docker cp [container-name]:[path-to-file] [destination-path]
Answer: The docker cp command will allow you to copy files from a container to your local machine. This is useful if you need to retrieve files from a container for troubleshooting or analysis.

## docker create [image-name]
Answer: The docker create command will create a new container from an image. This is the first step in running a container.

## docker diff [container-name]
Answer: The docker diff command will show you the differences between a container and its image. This is useful for troubleshooting or for understanding what changes have been made to a container.

## docker events
Answer: The docker events command will show you a stream of events from the Docker daemon. This is useful for monitoring the status of your Docker environment.

## docker exec -it [container-name] [command]
Answer: The docker exec command will allow you to run a command inside of a container. This is useful for troubleshooting or for running one-off commands inside of a container.

## docker export [container-name] > [filename.tar]
Answer: The docker export command will export a container as a tar file. This is useful for creating backups of containers or for moving containers to another Docker environment.

## docker history [image-name]
Answer: The docker history command will show you the history of an image. This is useful for understanding how an image was created or for troubleshooting issues with an image.

## docker images
Answer: The docker images command will show you a list of all images on your system. This is useful for managing your images and for understanding what images are available.

## docker import [filename.tar] [new-image-name]
Answer: The docker import command will import a tar file as a new image. This is useful for importing backups of containers or for moving containers to another Docker environment.

docker kill

## docker connect [container-name]
The docker connect command is used to connect a running container to a network. This is useful for when you want to connect a container to a specific network in order to access resources on that network.

## docker link [container-name]
The docker link command is used to connect a running container to another running container. This is useful for linking together different applications or services that need to communicate with each other. For example, if you have a web server container and a database container, you can link them together so that the web server can access the database.

## docker join [container-name]
The docker join command allows you to join an existing container to a new or existing network. This can be useful if you need to connect to a container that is running on a different host.

## Which of the following commands can be used to find out which network interfaces are being used by a container?
The `docker network inspect` command can be used to find out which network interfaces are being used by a container.

## docker inspect –networks [container-name]
This command will give you information about the network settings for a given container. This can be useful for troubleshooting networking issues, or for understanding how a container is configured.

## docker network create [network-name]
Answer: This command will create a new network with the given name. This can be useful for creating isolated networks for testing or development purposes.

## docker network rm [network-name]
Answer: This command will remove the given network. This can be useful for cleanup purposes, or for removing unused networks.

## docker inspect –network [container-name]
The docker inspect command is a powerful tool that can be used to retrieve detailed information on one or more containers. The –network option can be used to specifically retrieve information on the network settings for a given container. This can be useful for troubleshooting networking issues, or for simply understanding how a container is configured.