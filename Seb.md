



docker stack deploy registry --compose-file registry.yml

curl localhost:5000/v2/_catalog

docker-compose build

docker-compose push



#docker-compose up -d


docker stack deploy pwd --compose-file docker-compose.yml