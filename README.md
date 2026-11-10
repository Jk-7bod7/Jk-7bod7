# Omar Owais (`Jk-7bod7`)

**Automation & Integration Engineer | Workflow Architecture & Reliability**

Applied software engineer specializing in resilient webhook pipelines, workflow automation, API integration, and containerized development stacks.

---

## 🚀 Featured Engineering Project

### [WordPress Contact Form 7 → n8n CRM Integration Lab](https://github.com/Jk-7bod7/wordpress-cf7-n8n-crm-integration-lab)

> **Classification:** *Independent Local Reference Implementation (Synthetic Data & Local Mock CRM)*

A fault-tolerant form intake architecture connecting WordPress Contact Form 7 to n8n and an internal Python FastAPI + SQLite mock CRM, verified with local email delivery via Mailpit:

- **Durable Local Outbox:** MySQL/MariaDB queue buffers submissions on downstream failure with bounded exponential backoff retries.
- **Authenticated Webhooks:** Mutual header authentication (`X-Webhook-Secret`) with strict schema validation.
- **Idempotency & Deduplication:** Cryptographic UUIDv4 keys ensure zero duplicate lead insertions on replay.
- **Local Sandbox Verification:** 100% of lead notifications captured locally in Mailpit without external email transmission.
- **Testing:** 10/10 automated integration tests pass, with end-to-end browser execution verified via Chrome DevTools Protocol.

**Tech Stack:** WordPress 6.6 • Contact Form 7 • n8n 2.46 • Python 3.11 • FastAPI • SQLite • MariaDB 11.4 • Docker Compose • Mailpit

👉 **[View Repository & Implementation Details →](https://github.com/Jk-7bod7/wordpress-cf7-n8n-crm-integration-lab)**

---

## 🛠️ Technical Competencies

- **Automation & Integrations:** n8n Workflow Automation, Webhook Intake Architecture, REST API Design, Idempotent Processing, Outbox Patterns, Error Handling & Retries
- **Backend & Languages:** Python (FastAPI, Uvicorn, Pydantic, unittest), PHP, SQL, Bash / PowerShell
- **Databases & Stores:** SQLite, MariaDB / MySQL, Relational Schema Design
- **Infrastructure & DevOps:** Docker, Docker Compose, Linux, Git Version Control, Mailpit Local SMTP

---

## 📚 Academic & Research Projects

- **[crop-monitoring-cv](https://github.com/Jk-7bod7/crop-monitoring-cv):** Computer vision pipeline for plant health monitoring based on HSV color space segmentation of leaf imagery.
