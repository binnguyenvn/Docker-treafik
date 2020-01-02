sudo docker-compose -f ~/crm-treafik/traefik.yaml build

sudo docker stack deploy -c ~/crm-treafik/traefik.yaml traefik

sudo docker stack rm traefik

