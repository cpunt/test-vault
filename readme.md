### To start
First initialize a Docker Swarm:
  docker swarm init
Then initialize stack:
  docker stack deploy -c proxy-docker-compose-stack.yml proxy
  docker stack deploy -c docker-compose.yml dc

### To stop
docker stack rm dc
docker stack rm proxy
