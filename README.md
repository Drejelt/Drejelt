# Hi, I'm Drejelt

**Junior Infrastructure / DevOps Engineer based in Vilnius, Lithuania.**

I build Linux-based infrastructure, networking, and automation projects with a focus on **reliability, security, and reproducibility**.

My main interests are Linux systems, networking, infrastructure automation, and security. I enjoy understanding how systems behave under failure, automating repetitive operations, and turning manual configurations into reproducible deployments.

## 🛠 Tech Stack

**Systems & Infrastructure**
- Linux (primarily Debian)
- Networking: TCP/IP, DNS, NAT, routing, VPN
- WireGuard
- nftables
- SSH
- VPS / self-hosted infrastructure

**Development & Automation**
- Python
- Bash
- Git
- REST APIs
- PostgreSQL / MySQL / SQLite
- Docker fundamentals

**Currently exploring**
- AWS
- Terraform / Infrastructure as Code
- CI/CD
- Monitoring and observability

## Featured Projects

### VPN Gateway — WireGuard Wi-Fi / LAN Gateway

Linux-based network gateway designed to route Wi-Fi and LAN clients through WireGuard.

The project focuses on making a traditionally manual network setup **reproducible and resilient**.

**Highlights:**
- WireGuard VPN routing
- Wi-Fi access point and LAN support
- DNS leak protection
- nftables firewall
- Kill-switch behaviour
- Automated deployment
- Health checks and configuration validation
- Recovery / rollback-oriented design

**Tech:** Linux · WireGuard · nftables · Bash · DNS · Networking

---

### NAT Bridge

A self-hosted reverse-tunnelling system for exposing services located behind NAT through a VPS.

Designed around a small control plane and secure service configuration rather than manually maintaining individual tunnels.

**Highlights:**
- Client/server architecture
- Secure reverse tunnels
- Service and node management
- REST control API
- Per-service authentication
- Configuration validation and reconciliation
- Linux and Android/Termux support

**Tech:** Python · Linux · Networking · REST API · Reverse Tunnelling

---

### Linux Firewall Automation

An nftables-based firewall configuration focused on safe and reproducible deployment.

Instead of treating firewall configuration as a collection of commands, the project treats changes as an operation that should be **validated and recoverable**.

**Highlights:**
- Atomic ruleset application
- IPv4 / IPv6 handling
- Automated validation
- Health checks
- Rollback on failed deployment
- Regression-oriented testing

**Tech:** nftables · Bash · Linux · Networking

---

### Tranchée

A WWI-themed roguelike game project built with Godot.

While very different from my infrastructure projects, it gives me an environment for working with larger software systems, performance optimisation, state management, debugging, and iterative development.

**Tech:** Godot · Game Systems · Performance Optimisation

## How I Approach Projects

I prefer projects where I can understand and control the complete system rather than only one isolated component.

A typical workflow for me is:

`build → test → break → investigate → automate → validate → document`

I am particularly interested in questions such as:

- What happens when a dependency fails?
- Can deployment be reproduced from scratch?
- Can configuration changes be validated before they cause an outage?
- Can recovery be automated?
- What information would be needed to troubleshoot this six months later?

This is why many of my projects naturally involve networking, health checks, logging, validation, and automation.

## Areas of Interest

- Linux Infrastructure
- Network Engineering
- DevOps / Infrastructure Automation
- Cloud Infrastructure
- Network & Infrastructure Security
- Monitoring and Reliability Engineering

## Contact

- LinkedIn: [Valentyn Chernovol](https://www.linkedin.com/in/valentyn-chernovol-6846b2204/)
- GitHub: [@Drejelt](https://github.com/Drejelt)
