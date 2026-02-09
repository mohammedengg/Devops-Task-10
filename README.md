# Devops-Task-10
# Docker Volumes and Networks Task

## Objective
Understand Docker data persistence using volumes and container communication using networks.

## What I Did
- Created a Docker volume using CLI
- Mounted the volume to a container
- Stored data inside the volume
- Removed container and verified data persistence
- Created a custom Docker network
- Connected multiple containers to the network
- Tested container-to-container communication using network aliases

## Docker Commands Used
- docker volume create
- docker run -v
- docker network create
- docker network inspect
- docker exec
- docker logs

## Data Persistence Proof
Screenshots show that data remains after container removal.

## Architecture
The diagram shows how Docker volumes store persistent data and how containers communicate through a custom Docker network.

