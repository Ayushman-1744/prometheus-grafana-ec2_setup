# Prometheus + Grafana Monitoring Stack for Docker on EC2

This repository contains a complete monitoring solution using Docker Compose on an EC2 instance.

## Services
- Prometheus (`:9090`)
- Grafana (`:3000`)
- cAdvisor (`:8080`)
- Node Exporter (`:9100`)
- Pushgateway (`:9091`)

## Usage
```bash
sudo systemctl start docker
docker-compose up -d

Open the following ports:
9090, 3000, 8080, 9091, 9100
