# fantom-docker
Simple `Dockerfile` and `docker-compose` for Fantom

Assumes that data volume is `/data/volumes/fantom`

**BEFORE RUNNING THIS YOU MUST DOWNLOAD THE GENESIS FILE**
```bash
mkdir -p /data/volumes/fantom
wget -o /data/volumes/fantom/mainnet.g https://opera.fantom.network/mainnet.g
```

Start it up: `docker-compose up -d`

If a new version comes out you can just update the `VERSION` in the `docker-compose.yaml` file and run again with:

`docker-compose up -d --build`
