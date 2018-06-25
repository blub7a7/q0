PWD - 3 Manager - 2 Worker

docker network create -d overlay net

docker stack deploy --compose-file=traefik.yml traefik

docker stack deploy --compose-file=wordpress_stack_temp.yml wordpress
