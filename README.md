# Prometheus Grafana Monitoring with docker-compose
# Still in DEV-Mode but working on it, you can try the custom exporter and configure the alertmanager api like you want.
Prometheus Explorer available via localhost:9090/graph  

For JSON Logging add: `logging: *json-logging` to each service

For Loki usage: 1. Install loki plugin: `docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions`