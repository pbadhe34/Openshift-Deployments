Stop and remove all docker containers and images

List all containers (only IDs) : docker ps -aq.
Stop all running containers : docker stop $(docker ps -aq)

Remove all containers. docker rm $(docker ps -aq)

Use with caution
Remove all images:  docker rmi $(docker images -q)