Setup
^^^^^
- Create htpasswd file to create basic auth
- username:password
- Passwords must be encoded using MD5, SHA1, or BCrypt.

Start Treafik
^^^^^^^^^^^^^
- sudo docker stack deploy -c ~/crm-treafik/traefik.yaml traefik

