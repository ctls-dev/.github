# 🌐 CTLS.dev — Modern Engineering for Modern SaaS

**CTLS.dev builds fast, scalable, cloud-native software using a unified engineering system.**
Our architecture standardizes how backend services, frontend apps, and DevOps tooling work together, allowing us to ship confidently and iterate quickly.

We focus on:

* **Quarkus (Java 21)** microservices
* **Flutter Web + Mobile** applications
* **Firebase Authentication** for identity
* **Firestore** for real-time, lightweight data
* **Google Cloud Run** for deployment
* **Cloudflare** for DNS, security, and global access
* **GitHub Actions** for fully automated CI/CD

Every project in this organization follows the same foundational patterns, ensuring reliability, consistency, and a high-quality developer experience.

---

## 🚀 What We Build

CTLS.dev hosts a growing ecosystem of:

* Production-ready microservices
* Admin & operational tools
* Flutter web apps and PWAs
* Automation utilities
* Experimental prototypes and R&D efforts

Our work powers internal systems, SaaS products, and reusable engineering templates.

Some current pillars:

* **admin.ctls.dev** — Admin & management interface
* **ctls-webhook.ctls.dev** — Event ingestion and automation service
* **Flutter Web App** — Primary user interface layer

---

## 🧱 Engineering Principles

All CTLS.dev repositories share a unified approach:

### ✔ Consistent Architecture

We use the same structure across repos—clear API boundaries, typed models, predictable endpoints, and well-organized code.

### ✔ Security by Default

All apps authenticate through Firebase Auth and enforce role-based access and tenant scoping. Secrets are never included in code.

### ✔ Cloud-Native First

Everything is optimized for Cloud Run: stateless services, fast cold starts, minimal resource overhead.

### ✔ Automated Deployment

GitHub Actions handle builds, testing, containerization, and deployment to Google Cloud.

### ✔ Developer Happiness

Templates, scripts, clean naming, and consistent patterns reduce complexity and make onboarding fast.

---

## 🛠 Technology Stack

Our standard stack includes:

**Backend:** Quarkus (Java 21), RESTEasy Reactive, Firestore, Firebase Admin
**Frontend:** Flutter Web / iOS / Android, Firebase Auth, PWA tooling
**DevOps:** Docker, Cloud Run, Artifact Registry, Cloudflare, GitHub Actions
**Data:** Firestore (primary), Postgres (service-specific)
**Identity:** Firebase Auth + custom claims

---

## 📦 Template Repository

We maintain a **CTLS Standard Template**, which includes:

* Unified folder structure
* Quarkus or Flutter starter code
* Firebase Auth integration
* Dockerfile
* Cloud Run configuration
* Reusable GitHub Actions workflows
* Scaffolding scripts for new services

This ensures new projects start clean, secure, and production-ready.

---

## 🌱 Open Source

Over time, parts of the CTLS.dev ecosystem will be open-sourced:

* Starter templates
* DevTools
* Sample microservices
* Utility libraries
* Infrastructure scripts

We believe in sharing patterns that help teams build high-quality SaaS products quickly.

---

## 🤝 Collaboration

We welcome:

* Technical discussions
* Architecture feedback
* Open-source contributions (future)
* Partnerships and integrations

If you're a developer, designer, or product manager interested in modern cloud-native systems, feel free to explore our repos or reach out.

---

## 🧭 Mission

Build opinionated, modern engineering primitives that empower rapid product development — without sacrificing structure, security, or scalability.

---
