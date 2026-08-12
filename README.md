<h1 align="center">Kristina Barbina</h1>

<p align="center">
  <b>Backend engineer · integration architecture</b><br>
  Java 21 · Spring Boot 3 · PostgreSQL · RabbitMQ · Docker
</p>

<p align="center">
  <a href="https://gitlab.com/kris.barbina"><img alt="GitLab" src="https://img.shields.io/badge/code%20lives%20on-GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white"></a>
  <a href="https://1dh.ru/"><img alt="DataHUB" src="https://img.shields.io/badge/product-DataHUB-2E7D32?style=flat-square"></a>
  <a href="https://www.linkedin.com/in/kristina-barbina/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:kris.barbina@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://t.me/KristinaBarbina"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white"></a>
</p>

<p align="center"><sub><a href="README.ru.md">🇷🇺 По-русски</a></sub></p>

---

### 👋 My code lives on GitLab

I build **DataHUB**, a commercial integration platform. Its repositories, pipelines and reviews are on GitLab — **[gitlab.com/kris.barbina](https://gitlab.com/kris.barbina)**. That's why the contribution graph here is quiet: the work is, the repos are just somewhere else. Happy to walk through the code and architecture in an interview.

### 🚏 DataHUB — data bus for 1C:Enterprise

[1dh.ru](https://1dh.ru/) · [docs.1dh.ru](https://docs.1dh.ru/)

A message-driven integration platform that connects 1C:Enterprise ERP systems with the rest of a corporate landscape — event-based exchange instead of point-to-point scripts.

|  |  |
|---|---|
| **My role** | Architect and sole backend developer; lead of a 4-person product team |
| **Core service** | Java 21, Spring Boot 3.5, Spring MVC, Data JPA / Hibernate, PostgreSQL |
| **Messaging** | RabbitMQ — at-least-once delivery, idempotent handlers, retries, state tracking and recovery after failures |
| **Security** | In-house OAuth2 authorization server, JWT sessions, TLS/mTLS on the edge (Nginx) |
| **Delivery** | Docker / Compose, GitLab CI/CD (hand-written pipelines), Jib on Temurin 21, Flyway migrations, custom release builder for on-prem installs |
| **Quality** | JUnit 5, Testcontainers, WireMock, SonarQube, JaCoCo |
| **Where it runs** | Two on-prem customer installations; SaaS edition going to market |

The architecture started in 2020 as an integration layer for a university-wide accounting system (event exchange over RabbitMQ, files in S3), then was rewritten from scratch as a standalone Java product — in active development since January 2023.

### 🧭 What I'm good at

- **End-to-end backend ownership** — architecture, code, tests, pipelines and releases that other people then run in production.
- **Integration architecture** — asynchronous exchange between heterogeneous enterprise systems: message contracts, idempotency, failure handling, observability.
- **Engineering discipline** — static analysis, automated tests, configuration and deployment as code, reproducible releases.
- **Enterprise domain knowledge** — 19 years in corporate IT: ERP, finance, warehouse, document flow, manufacturing; systems with 500+ users.

### 🧰 Tech I work with

**Backend** — Java 21 · Spring Boot 3 · Spring MVC / WebFlux · Spring Security (OAuth2, JWT) · Hibernate / JPA · Gradle
**Data & messaging** — PostgreSQL · MS SQL · RabbitMQ · Flyway · Caffeine · Bucket4j · S3-compatible storage
**Ops** — Docker & Compose · GitLab CI/CD · Jib · Nginx (reverse proxy, mTLS) · Prometheus · Grafana (Loki, Mimir, Alloy)
**Testing & quality** — JUnit 5 · Testcontainers · WireMock · JaCoCo · SonarQube
**Also in my history** — C# / .NET, ASP.NET (earlier hands-on) · 1C:Enterprise platform, 15+ years at architect level

### 🗂 Track record

- **2023 → now — DataHUB** — own product: architecture and the entire backend.
- **2023–2026 — Smart Batteries (Energon group), technical architect** — integration architecture for a manufacturing group moving off foreign ERP software; development standards and Scrum/Kanban process, static analysis for 1C code via SonarQube, smoke tests with Vanessa Automation, monitoring stack (Prometheus, Grafana, Loki, Mimir, Alertmanager), GitLab CI/CD and infrastructure as code, performance and cluster redesign.
- **2020–2021 — Viktoriya Soft, lead project architect** — new accounting core plus web portal for a large university: normalized object model, two-tier front/back design, ~15 integrations, event exchange over RabbitMQ, files in S3. The DataHUB architecture was born here.
- **2017–2020 — AXELOT, head of internal automation** — ERP financial accounting methods, customer support portal integrated with ERP, foreign-trade accounting, EDI rollout, staff workload planning and bonus calculation; administration of 1C systems with 500+ users.
- **2010–2013 — Techno Puls** — founded and ran an e-commerce business end to end.

### 📬 Open to

Backend and integration engineering (Java, Spring), integration/solution architect roles — remote, contract or full-time.

**[kris.barbina@gmail.com](mailto:kris.barbina@gmail.com)** · [Telegram](https://t.me/KristinaBarbina) · [LinkedIn](https://www.linkedin.com/in/kristina-barbina/) · [GitLab](https://gitlab.com/kris.barbina)
