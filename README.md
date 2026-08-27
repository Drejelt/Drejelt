# Hi, I'm Drejelt

Junior Infrastructure / DevOps Engineer and Python developer based in Vilnius, Lithuania.

I build Linux infrastructure, networking, monitoring, and automation projects with a focus on reliability, security, and reproducibility.

My main interests are Linux systems, networking, infrastructure automation, observability, and backend tooling. I enjoy understanding how systems behave under failure, automating repetitive operations, and turning manual configurations into reproducible systems.

## Tech Stack

### Systems & Infrastructure

- Linux (primarily Debian)
- Networking: TCP/IP, DNS, NAT, routing, VPN
- WireGuard
- nftables
- SSH
- VPS / self-hosted infrastructure
- Monitoring & observability

### Development & Automation

- Python
- Bash
- Git / GitHub
- REST APIs
- PostgreSQL / MySQL / SQLite
- Docker
- FastAPI
- GitHub Actions / CI fundamentals

### Currently Learning

- Azure / cloud infrastructure
- Terraform / Infrastructure as Code
- Container orchestration
- Cloud networking and security

## Featured Projects

### Netmon — Network & Service Monitoring

A lightweight monitoring platform built to collect network, host, and service telemetry from distributed agents.

The project started as a way to understand monitoring systems beyond simply installing an existing stack: how metrics are collected, transported, stored, queried, and presented.

Highlights:

- Distributed agent/server architecture
- Network and service health checks
- Structured telemetry ingestion
- PostgreSQL storage
- REST API
- Grafana dashboards
- Docker Compose deployment
- Automated testing and CI
- Health and readiness checks

Tech: Python · FastAPI · PostgreSQL · Grafana · Docker · Linux · Networking

---

### NAT Bridge

A self-hosted reverse-tunnelling system for exposing services located behind NAT through a VPS.

Designed around a small control plane and secure service configuration rather than manually maintaining individual tunnels.

Highlights:

- Client/server architecture
- Secure reverse tunnels
- Service and node management
- REST control API
- Per-service authentication
- Configuration validation and reconciliation
- Health checks
- Linux and Android/Termux support

Tech: Python · Linux · Networking · REST API · Reverse Tunnelling

---

### VPN Gateway — WireGuard Wi-Fi / LAN Gateway

Linux-based network gateway designed to route Wi-Fi and LAN clients through WireGuard.

The project focuses on making a traditionally manual network setup reproducible and resilient.

Highlights:

- WireGuard VPN routing
- Wi-Fi access point and LAN support
- DNS leak protection
- nftables firewall
- Kill-switch behaviour
- Automated deployment
- Health checks and configuration validation
- Recovery / rollback-oriented design

Tech: Linux · WireGuard · nftables · Bash · DNS · Networking

---

### VoiceHelper — Local Voice Assistant

A personal Python voice-assistant project combining local speech recognition with deterministic command handling and optional LLM-assisted tool selection.

The project is primarily an experiment in safely integrating AI-assisted routing into an application without giving the model unrestricted execution capabilities.

Highlights:

- Local speech recognition
- Deterministic intent handling
- Optional LLM tool selection
- Restricted tool interface and output validation
- Rate limiting and failure handling
- Latency and token usage telemetry
- FastAPI-based control interface
- Automated tests

Tech: Python · FastAPI · Vosk · REST APIs · LLM APIs

---

### Linux Firewall Automation

An nftables-based firewall configuration focused on safe and reproducible deployment.

Instead of treating firewall configuration as a collection of commands, the project treats changes as an operation that should be validated and recoverable.

Highlights:

- Atomic ruleset application
- IPv4 / IPv6 handling
- Automated validation
- Health checks
- Rollback on failed deployment
- Regression-oriented testing

Tech: nftables · Bash · Linux · Networking

## How I Approach Projects

I prefer projects where I can understand and control the complete system rather than only one isolated component.

A typical workflow for me is:

`build → test → break → investigate → automate → validate → document`

I usually think about a few questions:

- What happens when something fails?
- Can deployment and configuration be reproduced?
- Is there enough information to troubleshoot the system later?

This is why many of my projects naturally involve networking, health checks, logging, validation, testing, and automation.

## Areas of Interest

- Linux Infrastructure
- DevOps / Infrastructure Automation
- Network Engineering
- Monitoring & Reliability Engineering
- Backend & Systems Tooling
- Cloud Infrastructure
- Network & Infrastructure Security

## Contact

- Email: [valentin.chernovol23@gmail.com](mailto:valentin.chernovol23@gmail.com)
- Telegram: [@Sebastian Lex](https://t.me/@riz3PohD)
- LinkedIn: [Valentyn Chernovol](https://www.linkedin.com/in/valentyn-chernovol-6846b2204/)
