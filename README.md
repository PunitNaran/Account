Run: 
COMPOSE_DOCKER_CLI_BUILD=1 DOCKER_BUILDKIT=1 docker-compose build
COMPOSE_DOCKER_CLI_BUILD=1 DOCKER_BUILDKIT=1 docker-compose up

If you have problems with the database_mysql folder I recommend manually accessing the container and chnaging the permissions otherise just delete it the files in the folder
create table is readbale, writable and execulate (chmod 777 ... )

Access mysql database by visiting:
http://localhost:9090/