# Deployment Guide

## Prerequisites

- Docker Desktop
- Docker Compose
- Git
- VS Code

## Clone Repository

git clone <repository-url>

## Navigate to Project

cd 007-monitoring-observability-platform

## Start Services

docker compose up -d

## Verify Services

Prometheus:
http://localhost:9090

Grafana:
http://localhost:3000

AlertManager:
http://localhost:9093

Node Exporter:
http://localhost:9100/metrics

## Stop Services

docker compose down