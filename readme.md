nano ~/crm-treafik/traefik.yaml

sudo docker stack deploy -c ~/crm-treafik/traefik.yaml traefik

sudo docker stack rm traefik

sudo docker-compose -f ~/crm-landing/production.yml build

sudo docker stack deploy -c ~/crm-landing/production.yml landing

sudo docker-compose -f ~/crm-core/production.yml build

sudo docker stack deploy -c ~/crm-core/production.yml bin

