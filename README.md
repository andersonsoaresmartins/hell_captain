# Hello, Captain! Docker Project

This project creates a basic Docker image that prints "Hello, Captain!" to the console when executed.

## Project Overview

The Dockerfile in this repository uses the `alpine:latest` image as a base and contains a single instruction to print a message before exiting. The project demonstrates how to build and run a minimal Docker container.

## Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.

## How to Use

Follow the steps below to build and run the Docker image:

### Step 1: Clone the Repository

```
git clone https://github.com/andersonsoaresmartins/hello_captain.git
cd hello_captain
```

### Step 2: Build the Docker Image

Run the following command in the root directory where the Dockerfile is located:
```
docker build -t hello_captain .
```

### Step 3: Run the Docker Container

After the image is built, run the container with the following command:
```
docker run hello_captain
```
You should see the following output in your console:

Hello, Captain!

## Project Structure

.

├── Dockerfile

└── README.md


### Dockerfile

The Dockerfile is as follows:

### Use the latest Alpine base image
FROM alpine:latest

### Command to print "Hello, Captain!" and exit
CMD ["echo", "Hello, Captain!"]


### License

This project is licensed under the MIT License. See the LICENSE file for details.

### Project URL
[https://github.com/andersonsoaresmartins/hello_captain
](https://roadmap.sh/projects/basic-dockerfile)


Contributing
Feel free to fork this project, submit issues, or make pull requests. Contributions are welcome!
Contact
If you have any questions or suggestions, please contact me at [asmartins@live.com].
