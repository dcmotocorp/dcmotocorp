# Telecom Real-Time Analytics Platform

**Stack:** Python, microservices, Kafka, InfluxDB, Docker

## Problem
Operational data from telecom inventory, devices, and application usage needed to be collected and presented for timely analysis.

## My contribution
- Designed and developed 15 Python microservices with separate responsibilities for inventory, telemetry, user management, application catalogues, and per-application network usage.
- Implemented Kafka event-streaming flows that process telemetry and persist time-series records in InfluxDB.
- Built backend APIs supporting live operational dashboards and containerized service deployment.
- Participated in team code reviews and testing practices.

## Outcome
The platform supported near-real-time operational visibility across the service areas above. I am not publishing throughput, customer data, or business metrics that I cannot substantiate publicly.

## Architecture at a glance

```mermaid
flowchart LR
    A[Devices and usage sources] --> B[Python services]
    B --> C[Kafka]
    C --> D[Telemetry processing]
    D --> E[InfluxDB]
    E --> F[Dashboard APIs]
```

This is a high-level description of professional work. The production repository and data are private; this page contains no client source code.
