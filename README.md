# AWS Monitoring & Alerting System

## Project Overview

This project demonstrates a complete monitoring and alerting solution for an AWS EC2 instance using Prometheus, Grafana, Node Exporter, and Alertmanager.

The system collects infrastructure metrics, visualizes them in Grafana dashboards, and sends email notifications when predefined alert conditions are met.

---

## Architecture

AWS EC2
│
├── Node Exporter
│
├── Prometheus
│
├── Grafana
│
└── Alertmanager
      │
      └── Gmail SMTP

---

## Technologies Used

- AWS EC2
- Ubuntu Linux
- Prometheus
- Grafana
- Node Exporter
- Alertmanager
- Gmail SMTP
- Git

---

## Features

- CPU Monitoring
- Memory Monitoring
- Disk Usage Monitoring
- Network Monitoring
- Prometheus Alert Rules
- Email Notifications
- Grafana Dashboards

---

## Project Structure

```
aws-monitoring-alerting-system/
├── alertmanager/
├── prometheus/
├── screenshots/
├── docs/
└── README.md
```

---

## Screenshots

(Added screenshots.)

---

## Future Enhancements

- Docker Compose
- GitHub Actions CI/CD
- Terraform
- Kubernetes
- Slack Notifications
- Grafana Loki Logging
