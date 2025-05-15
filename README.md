# 📦 GitHub Repository Naming Standard
This repository provides a standardized naming convention for organizing coding projects. It helps you (and others) quickly understand the **ownership**, **purpose** and **technical domain** of a repository at a glance.

---

## Naming Format
```
<level1>-<level2>-<level3>_<project-name>
```
- Each level is a **5-letter lowercase abbreviation** separated by hyphens.
- The `<project-name>` is lowercase, hyphen-separated and begins with underscore.
- Example: `persn-infom-miscp_repo-naming-convention`

---

## Classification Levels

### Level 1 — Ownership / Context

| Code   | Description                                                |
|--------|------------------------------------------------------------|
| `persn`| Personal projects—individual learning or experimentation   |
| `collb`| Collaborative projects involving peers or small teams      |
| `openp`| Open source or community-focused repositories              |
| `event`| Competition entries such as hackathons, coding challenges  |
| `enter`| Enterprise or client-related projects                      |
| `educa`| Educational content, tutorials, or mentorship resources    |

---

### Level 2 — Project Intent

| Code   | Description                                                                                         |
|--------|-----------------------------------------------------------------------------------------------------|
| `learn`| Experimental or skill-building projects                                                             |
| `build`| Boilerplates, templates, or reusable starter kits                                                   |
| `showc`| Portfolio-quality showcase projects                                                                 |
| `utilt`| Utility scripts, tools, or standalone functionalities                                               |
| `demoa`| Proof-of-concept, demonstrations, or MVPs                                                           |
| `produ`| Production-ready, deployable systems                                                                |
| `tests`| Testing environments, experimental proofs, or sandboxes                                             |
| `infom`| Information-centric projects: documentation, knowledge bases, data catalogs, or reference materials |

---

### Level 3 — Technical Domain

| Code   | Description                                            |
|--------|--------------------------------------------------------|
| `webdv`| Web development: frontend, backend, or full-stack apps |
| `apide`| API development: REST, GraphQL, FastAPI, etc.          |
| `infra`| Infrastructure, DevOps, CI/CD, container orchestration |
| `dengn`| Data engineering: pipelines, ETL, orchestration        |
| `anlyt`| Analytics: dashboards, BI, reporting                   |
| `mlmod`| Machine learning: model development, training          |
| `vizlt`| Data visualization and storytelling                    |
| `autoa`| Automation: bots, schedulers, automated workflows      |
| `pylib`| Python libraries or reusable packages                  |
| `miscp`| Miscellaneous projects outside above domains           |

---

## Project Name Guidelines

- Use **lowercase letters** only.
- Separate words with **hyphens (`-`)** exclusively; avoid underscores or other special characters.
- Choose a **concise and meaningful** name reflecting the project’s core focus.
- Example: `chat-service`, `data-pipeline`, `sales-dashboard`

---

## Sample Repository Names

| Repository Name                              | Description                                      |
|----------------------------------------------|--------------------------------------------------|
| `persn-learn_mlmod_credit-risk`              | Personal project practicing ML credit risk model |
| `openp-build_webdv_flask-starter`            | Community Flask web app starter template         |
| `event-showc_dengn_kaggle-churn-prediction`  | Kaggle competition churn prediction project      |
| `enter-produ_dengn_airflow-pipeline`         | Enterprise-grade Airflow data pipeline           |
| `educa-utilt_anlyt_sql-query-helper`         | Educational SQL query generation utility         |
| `collb-demoa_apide_chat-service`             | Collaborative API demo for a chat application    |

---

## Best Practices

- Enforce consistent lowercase naming and separation conventions.
- Use this structured naming to aid automation, searching, and filtering.
- Document exceptions or special cases clearly in your project README.
- Maintain this standard as part of onboarding and code review processes.
