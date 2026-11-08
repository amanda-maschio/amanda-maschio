<h1 align="center">Hi there, I'm Amanda Maschio 👋</h1>

<p align="center">
  <b>Software Developer @ <a href="https://www.metadados.com.br/">Metadados</a></b> · .NET · Angular · TypeScript · Cloud · Spec-Driven Development<br>
  📍 Caxias do Sul - RS, Brazil
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/amanda-maschio/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-amanda--maschio-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/amanda-maschio"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-amanda--maschio-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## About me

- 💼 Full-stack developer at **[Metadados](https://www.metadados.com.br/)**, working across backend, frontend, infrastructure and engineering tooling.
- 🎓 Graduated in **Analysis and Systems Development** at **[UNIFTEC](https://www.ftec.com.br/)** and postgraduate in **Software Architecture** at **FIAP** (8SOAT).
- 🌱 Interested in software architecture, cloud-native systems, developer experience and AI-assisted engineering.

---

## 🧭 How I work

- **Spec before code.** I start from a clear specification, acceptance criteria and recorded decisions (ADRs), so plan, tasks and code are *derived* from what was agreed — not the other way around.
- **Small, traceable deliveries.** One issue → one branch → one reviewed pull request, with [Conventional Commits](https://www.conventionalcommits.org/) and a history that explains *why* each change happened.
- **Tests are part of the delivery.** Unit and integration tests ship with the feature, and CI runs on every pull request — a change is only done when it is verified.
- **Consistent API contracts.** Versioned endpoints, standard error responses (`application/problem+json`), pagination envelopes, health checks and interactive OpenAPI docs, so consumers never have to guess.
- **Security and privacy by default.** Secret scanning in pre-commit hooks, no credentials in the repo, rate limiting, private file storage and LGPD concerns documented from day one.
- **Clean boundaries.** Layered / hexagonal architecture, DDD and CQRS where they pay off, keeping domain rules independent from frameworks and infrastructure.
- **Docs as code.** Architecture, runbooks, configuration and onboarding live next to the code — including `AGENTS.md` guides so AI agents follow the same conventions as people.
- **AI with guardrails.** I use AI agents as part of the workflow, but always with adversarial review, deterministic checks and human approval gates before anything reaches production.

---

## ⭐ Featured work

### 🏭 Software Factory · Metadados

> Private repository — not publicly accessible.

A reusable **software factory** built on top of GitHub Spec Kit, which I maintain. It turns Spec-Driven Development into an operable process for the whole team:

- guided intake so non-technical POs/PMs can describe features and bugs;
- **adversarial critique by AI sub-agents** (engineering, business and UI/UX lenses) before anything is built;
- **two human gates** — the plan and the merge — keeping people accountable for what ships;
- versioned releases automatically synchronized to product repositories;
- a deterministic test suite with **250+ tests** running on **Linux and Windows** in sharded CI.

`Bash` · `Python` · `GitHub Spec Kit` · `GitHub Actions` · `AI agents`

### 🩺 Care Guide — [github.com/care-guide](https://github.com/care-guide)

Ecosystem that centralizes everything relevant to the treatment of **oncology patients** in a single place: doctors, medications, exams, surgeries, symptoms and appointments.

| Repository | Highlights | Stack |
|---|---|---|
| [care-guide-api](https://github.com/care-guide/care-guide-api) | Layered REST API, issue-driven PRs, automated tests in CI, problem+json errors, rate limiting, private file storage, secret-scanning hooks and full docs (architecture, security, LGPD, runbooks) | .NET 10 · EF Core · PostgreSQL · Docker |
| [care-guide-app](https://github.com/care-guide/care-guide-app) | Mobile app with auth gate, secure session storage, typed models via codegen and a tested, scalable structure | Flutter · Dart · Riverpod · Dio |

### 🍔 FIAP Tech Challenge (8SOAT · Group 4) — [github.com/8SOAT-G4-Tech-Challenge](https://github.com/8SOAT-G4-Tech-Challenge)

Postgraduate team project that evolved, phase by phase, from a **hexagonal monolith** into **microservices on AWS**: a self-service ordering system for a fast-food restaurant, followed by a video-processing platform for the final hackathon. Built with DDD and Event Storming, Clean Architecture, tests with Jest, SonarQube analysis and infrastructure as code.

| Repository | Description |
|---|---|
| [order](https://github.com/8SOAT-G4-Tech-Challenge/tech-challenge-order) · [user](https://github.com/8SOAT-G4-Tech-Challenge/tech-challenge-user) · [payment](https://github.com/8SOAT-G4-Tech-Challenge/tech-challenge-payment) | Order, user and payment microservices |
| [hackaton-api](https://github.com/8SOAT-G4-Tech-Challenge/hackaton-api) · [hackaton-converter](https://github.com/8SOAT-G4-Tech-Challenge/hackaton-converter) | Video upload, processing queues, frame extraction and notifications |
| [documentation](https://github.com/8SOAT-G4-Tech-Challenge/tech-challenge-fiap-documentation) | Architecture docs for every phase |

`Node.js` · `TypeScript` · `Fastify` · `Prisma` · `Jest` · `PostgreSQL` · `MongoDB` · `Redis` · `Docker` · `Kubernetes (EKS)` · `Terraform` · `AWS`

### 💉 VaccineC — final undergraduate project (TCC)

A **complete management system for private vaccination clinics**, developed as my final project at UNIFTEC: registrations, quotes, scheduling with next-dose suggestions and SMS reminders, vaccine application with integration to a mock of the national immunization system (SI-PNI), and stock control by batch with automatic write-off.

[VaccineC.BackEnd](https://github.com/VarRgas/VaccineC.BackEnd) · [VaccineC.Web](https://github.com/VarRgas/VaccineC.Web) — `C#` · `.NET` · `Angular` · `TypeScript`

---

## 🛠️ Tech stack

**Languages**<br>
<img src="https://skillicons.dev/icons?i=cs,ts,js,java,html,css" alt="Languages">

**Frameworks & libraries**<br>
<img src="https://skillicons.dev/icons?i=dotnet,angular,nodejs,tailwind" alt="Frameworks">

**Data**<br>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis" alt="PostgreSQL, MongoDB, Redis">

**Cloud, DevOps & tooling**<br>
<img src="https://skillicons.dev/icons?i=azure,docker,kubernetes,terraform,git" alt="Cloud and DevOps">

**Practices**<br>
Spec-Driven Development · Clean Architecture · DDD · CQRS · Microservices · Automated testing · CI/CD · AI-assisted engineering

---

## 📊 GitHub stats

<p align="center">
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=amanda-maschio&theme=transparent" alt="GitHub stats">
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=amanda-maschio&theme=transparent" alt="Top languages by commit">
</p>

---

<p align="center">
  💬 Let's connect on <a href="https://www.linkedin.com/in/amanda-maschio/">LinkedIn</a>!
</p>
