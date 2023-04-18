# BUAN 5315 Docker Cheat Sheet

Docker is a popular open-source platform for developing, packaging, and deploying applications in a containerized environment. A container is a lightweight, standalone, executable package of software that includes everything needed to run an application, including the code, libraries, and system tools.

Docker Concepts:

•	Image: A read-only template that contains a set of instructions for creating a Docker container.

•	Container: An isolated and lightweight runtime environment created from an image that can run applications.

•	Dockerfile: A text file that contains instructions for building a Docker image.

•	Registry: A storage and distribution system for Docker images, which can be public (e.g. Docker Hub) or private.

•	Volume: A way to store data outside of a container, which can be shared between containers or with the host system.

•	Network: A way to connect containers together or to the host system, allowing them to communicate with each other.


Docker Commands:

	docker pull <image-name>: Pull an image from Docker Hub or a private registry.

	docker run <image-name>: Create a new container from an image and start it.

	docker ps: List running containers.

	docker stop <container-id>: Stop a running container.
  
	docker rm <container-id>: Remove a stopped container.

	docker images: List available images.

	docker rmi <image-id>: Remove an image.

	docker build <path-to-Dockerfile>: Build an image from a Dockerfile.

	docker push <image-name>: Push an image to Docker Hub or a private registry.

	docker exec -it <container-id> <command>: Run a command inside a running container.



