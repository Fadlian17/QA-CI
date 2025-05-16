# QA-CI: Cypress BDD Automation with CI/CD

![Cypress](https://img.shields.io/badge/Cypress-E2E_Testing-9e34c2?logo=cypress)
![CI/CD](https://github.com/Fadlian17/QA-CI/actions/workflows/main.yml/badge.svg)

Proyek ini merupakan implementasi pengujian otomatis berbasis **Web UI Automation** untuk website [SauceDemo](https://www.saucedemo.com/) menggunakan **Cypress**, **Cucumber (BDD)**, dan integrasi **CI/CD dengan GitHub Actions**.

---

## 🔧 Teknologi yang Digunakan

- [Cypress](https://www.cypress.io/) — Framework testing untuk end-to-end UI
- [Cucumber](https://cucumber.io/) — Penulisan skenario BDD (Behavior Driven Development)
- [Cypress-Cucumber-Preprocessor](https://github.com/badeball/cypress-cucumber-preprocessor)
- [GitHub Actions](https://docs.github.com/en/actions) — CI/CD pipeline

---

## 📂 Struktur Folder

```bash
QA-CI/
├── .github/workflows/
│   └── main.yml           # CI/CD pipeline (GitHub Actions)
├── cypress/
│   ├── e2e/
│   │   ├── features/      # File .feature BDD
│   │   │   └── login.feature
│   │   └── step_definitions/
│   │       └── loginSteps.js
│   ├── support/
│   │   └── e2e.js         # Support commands dan plugin import
├── cypress.config.js      # Konfigurasi Cypress
├── package.json           # Daftar dependencies dan script
├── README.md              # Dokumentasi proyek
