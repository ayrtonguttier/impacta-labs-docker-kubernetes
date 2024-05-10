aula 2

docker network create minha-rede
docker run -d --name=webserver-nginx --network=minha-rede nginx





docker run -it --network=minha-rede ubuntu bash
docker network connect rede container
docker network disconnect rede container
