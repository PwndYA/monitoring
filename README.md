# Prometheus Grafana Monitoring with docker-compose

# v1.0 more Prometheus Rules and Dashboards TBA

- Prometheus Explorer available via localhost:9090/graph  

- For JSON Logging add: `logging: *json-logging` to each service

- For Loki usage: 1. Install loki plugin: `docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions`