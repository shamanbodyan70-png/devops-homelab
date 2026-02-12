**DevOps Homelab**

**Overview**

This project is a self-learning DevOps homelab built on Ubuntu Server 24.04. The goal is to gain practical infrastructure experience and prepare for junior DevOps roles.

The environment is fully containerized using Docker Compose and includes monitoring, logging, alerting, reverse proxy, and CI/CD tools.

**Architecture**

*  Ubuntu Server 24.04 (bare metal)
*  Services containerized via Docker Compose
*  Reverse proxy using Nginx
*  Monitoring and logging stack deployed as separate services

**Stack**

*  Docker / Docker Compose
*  Prometheus
*  Grafana
*  Alertmanager (Telegram integration)
*  Loki
*  Promtail
*  Nginx (reverse proxy + HTTPS via DuckDNS)
*  Jenkins
*  Gitea

**Implemented Features:**

**Monitoring**

*  Host monitoring via Node Exporter
*  Service monitoring via Prometheus
*  Dashboards in Grafana


**Logging**

*  Centralized log collection via Promtail
*  Log aggregation with Loki

**Alerting**

*  Alertmanager configured with Telegram notifications
*  Reverse Proxy
*  Nginx as reverse proxy
*  HTTPS enabled for selected services (DuckDNS + SSL)

**Security**

*  Disabled root login
*  Disabled password authentication
*  SSH key-based authentication only
*  Custom SSH client configuration for simplified access

**Networking**

*  Practical experience configuring a two-router setup (GPON + OpenWrt)
*  Troubleshooting routing and interface issues
*  Basic understanding of TCP/IP and routing principles

**CI/CD**

*  Jenkins installed and configured
*  Pipeline development in progress

**In Progress**

*  Bash automation scripts
*  Jenkins pipelines
*  Infrastructure structuring and optimization

**Goal**

This project is focused on hands-on DevOps practice:
*  Infrastructure setup
*  Observability implementation
*  Troubleshooting and debugging
*  Secure service exposure
*  Continuous improvement through experimentation

**Lessons Learned**

Applying a bottom-up troubleshooting approach — starting from network interfaces and connectivity, then moving up to services and application layer.


