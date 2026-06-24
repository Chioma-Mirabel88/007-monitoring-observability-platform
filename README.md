# Monitoring & Observability Platform

## Overview

A production-grade monitoring and observability platform built using Prometheus, Grafana, AlertManager, Docker, and Node Exporter.

The platform provides real-time infrastructure monitoring, alerting, and visualization of system performance metrics including CPU, memory, disk, and network utilization.

## Architecture

Node Exporter → Prometheus → AlertManager → Grafana

## Technologies Used

* Prometheus
* Grafana
* AlertManager
* Docker & Docker Compose
* Node Exporter
* Linux

## Key Features

* Infrastructure Monitoring
* Metrics Collection
* Real-Time Dashboarding
* Alert Management
* Incident Detection
* Containerized Deployment

## Monitored Metrics

* CPU Utilization
* Memory Utilization
* Disk Usage
* Network Traffic
* Service Availability

## Project Structure

```text
.
├── alertmanager/
├── docs/
├── grafana/
├── prometheus/
├── screenshots/
├── scripts/
├── docker-compose.yml
└── README.md
```

## Screenshots

### Running Containers

![Running Containers](screenshots/screenshots01-running-containers.png.jpeg)

### Prometheus Targets

![Prometheus Targets](screenshots/screenshots-02%20prometheus%20targets.png.jpeg)

### Grafana Datasource

![Grafana Datasource](screenshots/screenshots%2003-grafana-datasource.png.jpeg)

### Dashboard View 1

![Dashboard View 1](screenshots/screenshots-04-node-exporter-dashboard.png1.jpeg)

### Dashboard View 2

![Dashboard View 2](screenshots/screenshots-04-node-exporter-dashboard.png2.jpeg)

### Dashboard View 3

![Dashboard View 3](screenshots/screenshots-04-node-exporter-dashboard.png3.jpeg)

### Dashboard View 4

![Dashboard View 4](screenshots/screenshots-04-node-exporter-dashboard.png4.jpeg)

### Metrics Dashboard

![Metrics Dashboard](screenshots/screenshots-05-metrics.png.jpeg)

## Deployment

Clone the repository:

```bash
git clone https://github.com/Chioma-Mirabel88/007-monitoring-observability-platform.git
```

Start the monitoring stack:

```bash
docker compose up -d
```

Access services:

* Grafana: http://localhost:3000
* Prometheus: http://localhost:9090
* AlertManager: http://localhost:9093

## Status

Completed

## Future Enhancements

* Slack Alerting
* Microsoft Teams Alerting
* Docker Monitoring with cAdvisor
* Website Monitoring with Blackbox Exporter
* Kubernetes Monitoring
* Automated Backup & Restore
* Infrastructure as Code (Terraform)
* Dashboard Provisioning as Code
