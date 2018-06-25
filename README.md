Steps:

goto PWD ---> 3 Manager - 2 Worker

git clone https://github.com/blub7a7/q0.git &&                                                                                                      cd q0...

docker network create -d overlay net

docker stack deploy --compose-file=traefik.yml traefik

docker stack deploy --compose-file=wordpress_stack_temp.yml wordpress
