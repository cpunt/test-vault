### To start
docker-compose -p proxy -f proxy-docker-compose-stack.yml up

docker-compose -p vault -f docker-compose.yml up

### To stop
docker-compose -p vault down

docker-compose -p proxy down
