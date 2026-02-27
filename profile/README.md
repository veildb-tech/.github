# VeilDB

**Open-source platform for database anonymization and secure sharing across development teams.**

VeilDB helps you safely share production-like databases without exposing sensitive customer data.

---

## Why VeilDB?

Sharing real production databases is risky:
- Personal data leaks
- Compliance violations
- Accidental exposure in local environments

At the same time, development teams need realistic data for:
- Debugging
- QA
- Demos
- Performance testing

VeilDB solves this by automatically anonymizing sensitive data and generating clean, shareable database dumps.

---

## How It Works

VeilDB consists of three components:

- **Service** - Web interface to configure masking rules, permissions, and database sources.
- **Agent** – Runs on your server, processes backups and applies anonymization rules.
- **Client** – Lightweight tool for developers to securely download prepared dumps.

Service → Agent → Client

---

## Demo

![VeilDB Demo](./demo.gif)

The demo shows:
- Creating masking rules
- Triggering a dump
- Downloading the anonymized database
- Verifying the final result

---

## Key Features

- Flexible data masking rules
- Scheduled processing
- Role-based access control
- Multi-server support
- Production-like anonymized dumps

---

## Repositories

- [Service](https://github.com/veildb-tech/service) – Web UI and core management layer  
- [Agent](https://github.com/veildb-tech/agent) – Backup processing and anonymization engine  
- [https://github.com/veildb-tech/client](https://github.com/veildb-tech/client) – CLI application for downloading dumps  

---

## Get Started

Check the [documentation](https://veildb.gitbook.io/veildb-docs/) and install the components you need.

⭐ Star the project if this helps your team.
