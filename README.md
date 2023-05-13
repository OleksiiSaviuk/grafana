# grafana

For Loggining Docker containers w/PromTrail install [docker driver](https://grafana.com/docs/loki/latest/clients/docker-driver/):
```
   docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions
```
After change the logging driver for container: */etc/docker/daemon.json* (example in [/docker](/docker))
