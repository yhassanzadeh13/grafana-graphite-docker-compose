# Grafana and Graphite Docker Compose
A docker compose file to run both Grafana and Graphite. 

## Steps to run the docker compose:
1. Create a Grafana Docker Volume:
```
 docker volume create --name=grafana-volume
```

2. Build an run the docker compose file:
```
docker-compose up -d
```
