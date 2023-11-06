# monitoring-tools-setup


Setting up entire real time monitoring stack with configuration and targets using single command.


Pre requsites
--------------
Docker

Monitoring Stack
-----------------
1. Prometheus
2. Grafana

Targets
--------

Node expoter (To monitor underlining Linux Os)
Docker metrics (To monitor containers)
Prometheus metrics (To monitor prometheus tool)
Custom Metrics:
rate(http_request_duration_microseconds_count[1m])
rate(node_network_receive_bytes[1m])
engine_daemon_health_checks_total
