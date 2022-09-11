# Dockerizing a NodeJs app

## Configure

To reflect the changes of package.json in docker container,
First delete the already created image of docker-demo and also delete the container. Then go to the volumes and delete all the volumes whose name looks like hash-code

## Run

And to start the docker container, run the following command

    docker compose up
