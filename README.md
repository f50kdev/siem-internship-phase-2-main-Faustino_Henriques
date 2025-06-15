# SOC Detection Simulation Lab - Phase 2

This repository documents security operations center (SOC) detection simulations for common attack techniques. Each simulation includes step-by-step execution guides, detection queries, and sample outputs for Kibana.

## Lab Environment Overview
```mermaid
graph LR
    A[Kali Linux Attacker] --> B[Windows 10 Victim]
    B --> C[Domain Controller]
    B --> D[Elastic Stack]
    D --> E[Kibana Dashboard]
