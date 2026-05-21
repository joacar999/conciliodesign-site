# Concilio Design

Developer tools and interactive visualizations focused on:

* API integration
* OAuth2 / API security
* OpenAPI tooling
* JWT inspection and token debugging
* API lifecycle and specification comparison
* AI-assisted engineering workflows

Live site:  
https://conciliodesign.se

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
https://web-production-afdbe.up.railway.app/

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
* Beginner-friendly explanations

Live:  
https://conciliodesign.se/oauth2-visualizer.html

---

### JWT Inspector

Decode and inspect JSON Web Tokens directly in the browser.

Features:

* JWT header decoding
* JWT payload inspection
* Expiry and timing analysis
* Scope and role inspection
* Multiple example tokens
* Browser-only processing
* No backend required

Live:  
https://conciliodesign.se/jwt-inspector.html

---

### OpenAPI Diff

Compare two OpenAPI specifications and visualize API changes.

Features:

* Compare OpenAPI versions
* Detect added endpoints
* Detect removed endpoints
* Visualize breaking changes
* Interactive example specifications
* API lifecycle visualization

Live:  
https://conciliodesign.se/openapi-diff.html

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

* GitHub → Vercel automatic deployment pipeline

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

http://localhost:8080

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
* educational visualizations for complex security concepts

---

## Roadmap

Planned future tools include:

* ISO20022 Explorer
* OAuth2 Playground
* API Request Visualizer
* Integration Architecture Visualizer
* Kafka Event Visualizer
* API Security Playground

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
* Backend Integration Engineering
* Cloud Security
* API Lifecycle Management
