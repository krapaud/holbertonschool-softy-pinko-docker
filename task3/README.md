# holbertonschool-softy-pinko-docker

## Project Overview
This project provides a Docker image based on the latest Ubuntu. The image is configured to update the APT package manager, upgrade any installed packages, and echo "Hello, World!" when the container is run.

## Files
- **Dockerfile**: Defines the Docker image with the necessary configurations.
- **README.md**: Documentation for building and running the Docker image.

## Building the Docker Image
To build the Docker image, navigate to the project directory and run the following command:

```
docker build -t hello-world-image .
```

## Running the Docker Container
Once the image is built, you can run the container using the following command:

```
docker run hello-world-image
```

This will output:

```
Hello, World!
```

## Requirements
- Docker must be installed on your machine to build and run the image.

## License
This project is licensed under the MIT License.