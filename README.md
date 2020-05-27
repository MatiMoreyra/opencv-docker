# OpenCV Docker
[![Docker Hub Automated Build](https://img.shields.io/docker/cloud/automated/matimoreyra/opencv)](https://hub.docker.com/r/matimoreyra/opencv)
[![Docker Hub Build](https://img.shields.io/docker/cloud/build/matimoreyra/opencv)](https://hub.docker.com/r/matimoreyra/opencv)

Docker image for OpenCV development with C++.

## Deployments

This project is automatically deployed to [matimoreyra/opencv](https://hub.docker.com/repository/docker/matimoreyra/opencv) Docker Hub repository.

## Usage
### Option 1 - Pulling from Docker Hub

1. Pull the image from Docker Hub:
```
docker pull matimoreyra/opencv
```
2. Run in a container:
```
docker run -dit [--name <container_name>] matimoreyra/opencv
```

### Option 2 - Building from Dockerfile:
1. Clone this repo:
```
git clone git@github.com:MatiMoreyra/opencv-docker.git
```
Or just download it from [here](https://github.com/MatiMoreyra/opencv-docker/archive/master.zip).

2. Build the image:

From the folder containing the Dockerfile, run:
```
docker build -t matimoreyra/opencv .
```

3. Run in a container:
```
docker run -dit [--name <container_name>] matimoreyra/opencv
```

