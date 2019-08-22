SET COMPOSE_CONVERT_WINDOWS_PATHS=1



## Deployment

```
cd ~/ && \
rm -Rf portainer/ && \
mkdir portainer && cd portainer && \
wget https://raw.githubusercontent.com/regme/Containers/master/Portainer/docker-compose.yml && \
docker-compose up -d

```
