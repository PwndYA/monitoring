# Prometheus Grafana Monitoring  

Prometheus Explorer available via localhost:9090/graph  
For JSON Logging add: `logging: *json-logging` to each service  

For Loki usage: 1. Install loki plugin: `docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions`  

## Prerequisites  

### VM 
sudo apt update 
sudo apt install openssh-server  

Docker und compose auf Ubuntu installieren: https://docs.docker.com/engine/install/ubuntu/   

### VSCode Remote SSH und Remote SSH Editing Config Files plugin in VSCode install