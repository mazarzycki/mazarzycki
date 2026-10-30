# Hi, I'm Marek 👋

**Python backend engineer** building APIs and automation with FastAPI, PostgreSQL, Docker and Linux. I'm currently studying networking through a hands-on Ubuntu Server homelab, with a Python-based Network-as-a-Service prototype planned as the next step.

Before moving into engineering, I spent more than a decade in international business development and financial risk intelligence, including roles at the Polish Embassy in Brazil and Refinitiv / World-Check. That background still shapes how I work: I care about systems that are reliable, auditable and useful under real-world constraints, and I'm comfortable in enterprise and compliance-heavy environments.

---

## 🔨 Current project — Linux Networking Homelab

I'm using an Ubuntu Server thin client to build and troubleshoot virtual networks from the ground up. The exercises cover **TCP/IP, subnetting, routing, DNS, DHCP, VLANs, firewalls and traffic analysis** using Linux namespaces, virtual Ethernet pairs, bridges, `tcpdump` and `tc`.

The goal is to understand what happens to packets, how network isolation works and how to diagnose failures—before automating any of it. I'll also use Python to inspect and validate network state as I progress.

*Status: lab guide and exercises prepared; hands-on implementation is the current focus.*

---

## ⏭️ Next project — Mini NaaS (Network Automation with Python)

Once the networking fundamentals are in place, I'll use the same homelab to build a small **Network-as-a-Service (NaaS) prototype**: an API for provisioning, modifying and deleting virtual network connections.

The planned platform combines **FastAPI**, **PostgreSQL** for desired state and operation history, **Redis Streams** for background jobs, and a privileged worker that applies and verifies Linux networking changes. Its design explores idempotent requests, asynchronous provisioning, failure recovery, reconciliation and auditability.

*Status: architecture and implementation plan prepared; development follows the foundational labs. This will be a learning prototype, not a production carrier network.*

---

## 🚀 What I'm focused on

- **Python APIs and automation:** FastAPI, Pydantic, background processing, clear API contracts and reliable workflows
- **Networking fundamentals:** TCP/IP, subnetting, DNS, DHCP, routing, VLANs and how Linux implements virtual networks
- **Stateful systems:** PostgreSQL, SQLAlchemy, Alembic, Redis, idempotency and desired-versus-observed state
- **Linux and containers:** network namespaces, Docker, Compose, debugging, health checks and operational safety
- **Engineering quality:** pytest, CI, observability, threat modelling and auditable changes

---

## 🌐 Live projects

### [CifraGuard](https://cifraguard.com/)
A privacy-focused service for sending sensitive files securely. It explores encryption-aware design and privacy-first architecture while keeping the experience simple.

### [FootyPin](https://footypin.com/)
A map-based tool for finding football stadiums nearby and planning football trips. It explores geospatial data, location-aware interfaces and incremental platform growth, with the goal of deep coverage across leagues and countries.

### [City Weather Lab](https://cityweatherlab.com/)
A lightweight weather analytics tool that tracks conditions across selected cities. It explores API integration, backend data collection and simple visualization on minimal cloud infrastructure.

---

## 🧩 Tech stack

- **Backend:** Python · FastAPI · Pydantic · SQLAlchemy · Alembic · pytest
- **Data:** PostgreSQL · Redis · SQL
- **Infrastructure:** Docker · Docker Compose · Nginx · Linux · Bash · GitHub Actions
- **Cloud:** Azure · Bicep
- **Networking (current labs):** `iproute2` · network namespaces · veth · bridges · VLANs · `tcpdump` · `tc`
- **Also:** JavaScript · PowerShell · HTML/CSS

---

## 🗣️ Languages

Polish (native) · English, Portuguese, Russian (fluent) · Spanish, German (advanced) · Dutch (basic)

---

## 📫 Connect

- LinkedIn: [marek-zarzycki](https://www.linkedin.com/in/marek-zarzycki-414ab62/)
- Blog: [dev.to/marcoz](https://dev.to/marcoz)
- Website: [nubecode.eu](https://nubecode.eu)
