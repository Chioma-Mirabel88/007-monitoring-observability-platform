# Troubleshooting Guide

## Prometheus Not Starting

Cause:
Invalid prometheus.yml configuration.

Resolution:
Validate YAML syntax and restart container.

## Grafana Not Accessible

Cause:
Container not running.

Resolution:
docker ps

Check container logs.

docker logs grafana

## Node Exporter Not Reachable

Cause:
Container failure or port conflict.

Resolution:
Verify container status and exposed ports.

## AlertManager Not Starting

Cause:
Invalid alertmanager.yml syntax.

Resolution:
Review configuration and restart container.