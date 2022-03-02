# mailu-config-1.9
mailu 1.9 config default crossplatform


# docker start
docker-compose -p mailu up -d

# create admin user
docker-compose exec admin flask mailu admin user yourdomain.com 'password'

# change directory
change ROOT to your directory install mailu inside .env
