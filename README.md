# Concilio Design

Developer tools and interactive visualizations focused on:

* API integration
* OAuth2 / API security
* OpenAPI tooling
* AI-assisted engineering workflows

Live site:
[https://conciliodesign.se](https://conciliodesign.se)

---

## Current Tools

### OpenAPI Generator

Generate runnable Python integration clients directly from OpenAPI / Swagger specifications.

Features:

* OpenAPI YAML + JSON support
* Automatic endpoint parsing
* Runnable Python requests clients
* Integration-focused code generation

Live:
[https://web-production-afdbe.up.railway.app/](https://web-production-afdbe.up.railway.app/)

---

### OAuth2 Visualizer

Interactive visual explanation of common OAuth2 authentication flows.

Currently supports:

* Authorization Code Flow
* Client Credentials Flow

Features:

* Token flow visualization
* Security recommendations
* Real-world usage scenarios
* OAuth2 learning/reference tool

Live:
[https://conciliodesign.se/oauth2-visualizer.html](https://conciliodesign.se/oauth2-visualizer.html)

---

## Tech Stack

Frontend:

* HTML
* Tailwind CSS
* Vanilla JavaScript

Infrastructure:

* GitHub
* Vercel
* Railway

Backend tooling:

* Python
* Flask
* OpenAI API

---

## Development Workflow

Feature development is performed using Git feature branches.

Typical workflow:

```bash
git checkout -b feature-name
git add .
git commit -m "Add feature"
git push
```

Production deployment:

* GitHub → Vercel (automatic deploy pipeline)

---

## Local Development

Clone repository:

```bash
git clone https://github.com/joacar999/conciliodesign-site.git
```

Run locally:

```bash
python -m http.server 8080
```

Open:
[http://localhost:8080](http://localhost:8080)

---

## Project Goals

This repository is both:

* a lightweight developer tools platform
* a technical portfolio demonstrating API integration, OAuth2, backend engineering and developer tooling concepts

The project intentionally focuses on:

* simplicity
* fast iteration
* practical tooling
* clean developer-oriented UX

---

## Author

Joakim Carlsson
Founder & CEO — Concilio Design AB

Senior Integration Consultant specializing in:

* Azure
* API Security
* OAuth2 / Entra ID
* Python
* SAP Integration
* Enterprise Integration Architecture
