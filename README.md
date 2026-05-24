````markdown
# Concilio Design

<p align="center">
  <img src="https://github.com/user-attachments/assets/eed4e286-44ec-4c8d-8092-f164dbe1b585"
       alt="Concilio Design Integration Studio"
       width="1000" />
</p>

Developer tools and interactive visualizations focused on:

* API integration
* OAuth2 / API security
* OpenAPI tooling
* JWT inspection and token debugging
* API lifecycle and specification comparison
* AI-assisted engineering workflows

Live site:  
https://conciliodesign.se

Repository:
https://github.com/joacar999/conciliodesign-site

---

# Vision

Concilio Design is a lightweight developer tooling platform focused on practical API integration and security workflows.

The goal is to build small, useful and developer-friendly tools that simplify:

* API integration
* OAuth2 and JWT troubleshooting
* OpenAPI analysis
* API lifecycle management
* Integration debugging
* AI-assisted engineering workflows

The project intentionally emphasizes:

* practical usefulness
* simplicity
* fast iteration
* browser-based tooling
* developer-oriented UX
* clear visualization of complex security concepts

---

# Current Tools

## OpenAPI Generator

Generate runnable Python integration clients directly from OpenAPI / Swagger specifications.

### Features

* OpenAPI YAML + JSON support
* Automatic endpoint parsing
* Runnable Python requests clients
* Integration-focused code generation
* Production-oriented API client scaffolding

### Live

https://web-production-afdbe.up.railway.app/

---

## OAuth2 Visualizer

Interactive visual explanation of common OAuth2 authentication flows.

### Currently supports

* Authorization Code Flow
* Client Credentials Flow

### Features

* Token flow visualization
* Security recommendations
* Real-world usage scenarios
* OAuth2 learning/reference tool
* Beginner-friendly explanations
* API security education

### Live

https://conciliodesign.se/oauth2-visualizer.html

---

## JWT Inspector

Decode and inspect JSON Web Tokens directly in the browser.

### Features

* JWT header decoding
* JWT payload inspection
* Expiry and timing analysis
* Scope and role inspection
* Multiple example tokens
* Browser-only processing
* No backend required
* JWT troubleshooting support

### Live

https://conciliodesign.se/jwt-inspector.html

---

## OpenAPI Diff

Compare two OpenAPI specifications and visualize API changes.

### Features

* Compare OpenAPI versions
* Detect added endpoints
* Detect removed endpoints
* Visualize breaking changes
* Interactive example specifications
* API lifecycle visualization
* Contract evolution analysis

### Live

https://conciliodesign.se/openapi-diff.html

---

## Swagger Auth Detector

Analyze OpenAPI and Swagger specifications to understand how API authentication and authorization are configured.

### Features

* Detect OAuth2 flows
* Detect JWT and Bearer authentication
* Detect API key authentication
* Detect OpenID Connect usage
* Analyze endpoint security inheritance
* Identify public endpoints
* Visualize scopes and permissions
* Highlight potential security issues

### Example use cases

* Understanding unfamiliar APIs
* Debugging 401/403 issues
* Reviewing OpenAPI security configuration
* Learning OAuth2/OpenAPI security concepts
* Detecting accidentally public endpoints

### Live

https://conciliodesign.se/swagger-auth-detector.html

---

# Tech Stack

## Frontend

* HTML
* Tailwind CSS
* Vanilla JavaScript

## Infrastructure

* GitHub
* Vercel
* Railway

## Backend Tooling

* Python
* Flask
* OpenAI API

---

# Architecture Direction

A core long-term focus of the project is building a reusable OpenAPI normalization layer.

Vision:

```text
Swagger/OpenAPI
        ↓
Parser
        ↓
Normalized internal model
        ↓
AI enrichment
        ↓
Generators / analyzers / visualizers
```

The goal is to separate:

* parsing
* normalization
* semantic analysis
* visualization
* code generation

This enables reusable tooling across multiple API-related workflows.

---

# Development Workflow

Feature development is performed using Git feature branches.

Typical workflow:

```bash
git checkout -b feature-name
git add .
git commit -m "Add feature"
git push
```

Production deployment:

```text
GitHub → Vercel automatic deployment pipeline
```

---

# Local Development

Clone repository:

```bash
git clone https://github.com/joacar999/conciliodesign-site.git
```

Run locally:

```bash
python -m http.server 8080
```

Open:

```text
http://localhost:8080
```

---

# Project Goals

This repository serves both as:

* a lightweight developer tools platform
* a technical portfolio demonstrating API integration, OAuth2, backend engineering and developer tooling concepts

The project is intentionally designed to remain:

* lightweight
* understandable
* practical
* fast to iterate on
* useful for real-world integration engineers

---

# Roadmap

Planned future tools include:

* OAuth2 Playground
* API Error Decoder
* Scope Analyzer
* API Request Visualizer
* Integration Architecture Visualizer
* Kafka Event Formatter
* Requirements → Test Cases
* API Security Playground
* ISO20022 Explorer

---

# Author

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

