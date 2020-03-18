# Traefik Template!

Create Loadbalancer using **Traefik** deploy with **Docker**

## Setting up
- Create htpasswd file to create basic auth
- username:password
- Passwords must be encoded using MD5, SHA1, or BCrypt.
- Edit traefik.yml to change your domain

## Deployment
- sudo docker stack deploy -c traefik.yaml traefik

## Link
- traefik.domain.com to manage App
