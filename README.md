# [docker-compose](https://docs.docker.com/compose/)

This repository is to practice docker-compose command to run multiple containers.

I have tested two repository from [docker/awesome-compose](https://github.com/docker/awesome-compose).

1- [WordPress](https://github.com/docker/awesome-compose/tree/master/official-documentation-samples/wordpress)

please check the [wordpress\.pdf](https://github.com/emineozsahin/Docker-test/blob/main/wordpress.pdf) to see the results.

2- [aspnet-mssql](https://github.com/docker/awesome-compose/tree/master/aspnet-mssql)

please check the pdf files [aspnet-mssql.pdf](https://github.com/emineozsahin/Docker-test/blob/main/aspnet-mssql.pdf) to see the results.

```sh
# Generating the containers
## in the Wordpress-compose folder, run the following
docker-compose -f docker-compose-wordpress.yml up

## in the aspnet-mssql, run the following
docker-compose up

# Removing the containers
docker-compose down

# Deleting the images
docker image rm aspnet-mssql-web
docker image rm wordpress
```

