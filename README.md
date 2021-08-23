# fantom-docker
Simple `Dockerfile` and `docker-compose` for Fantom

Assumes that data volume is `/data/volumes/fantom`

`docker-compose up -d`

If a new version comes out you can just update the `VERSION` in the `docker-compose.yaml` file and run again with `docker-compose up -d --build`
