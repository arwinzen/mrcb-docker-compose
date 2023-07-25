# mrcb-analytics-backend docker compose scaffolding

This docker compose scaffolding is used as an example of how the mrcb-analytics-backend repo can be integrated for a local setup.

The repository acts as the parent directory for the mrcb-analytics-backend project and looks like this :

/mrcb-backend
    /src
        /mrcb-analytics-backend
            Dockerfile
    docker-compose.yml
    .docker
    mrcb* (executable)

Once the source files have been cloned, run the following commands to build and run the project:

''' bash
docker compose build mrcb
docker compose up -d
'''
