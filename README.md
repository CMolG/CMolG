<div align="center">


  # Carlos Molina Galindo

**Senior Backend & AI Systems Engineer**

Java · Quarkus · GraalVM native · Agent infrastructure (MCP, RAG, harnesses) · Next.js

[![LinkedIn](https://img.shields.io/badge/LinkedIn-cmolg-0D1117?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/cmolg)
[![X](https://img.shields.io/badge/X-cmolgal-0D1117?style=flat-square&logo=x&logoColor=white)](https://x.com/cmolgal)
[![Medium](https://img.shields.io/badge/Medium-cmolg-0D1117?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@cmolg)
[![Email](https://img.shields.io/badge/Email-cmolgaldev@gmail.com-0D1117?style=flat-square&logo=gmail&logoColor=white)](mailto:cmolgaldev@gmail.com)
![Location](https://img.shields.io/badge/Murcia,%20Spain-CET%20·%20Remote-0D1117?style=flat-square&logo=googlemaps&logoColor=white)
![Available](https://img.shields.io/badge/open%20to-contract%20work%20(EU%20/%20US)-10B981?style=flat-square)

`▓▓▒▒░░ ·  ·   ·    ·     ·    ·   ·  · ░░▒▒▓▓`

</div>

<p align="center">
  <img src="https://servingfiles.uk/javadaba_apps_background_reduced.png" alt="Cabecera" width="100%">
</p>

## Hi, I'm Carlos

I'm a senior engineer from Murcia, Spain, working as an independent contractor. Most of my career has been spent inside Java distributed systems — Capgemini, Accenture, and then TuLotero — and the last couple of years putting agentic AI into **production** instead of into demos.

I like the unglamorous half of AI engineering: invariants, guardrails, harnesses, regression tests with mutability, and the boring plumbing that decides whether an agent is a product or a party trick. If something I build ends up being useful to someone else, even better — that's why most of it ends up here in the open.

Right now I'm CTO & Tech Lead at **Javadaba** and **Legally**, and I build in public whenever the work allows it.

<div align="center">

`░▒▓ ─────────────────────────────────────── ▓▒░`

</div>

## What I'm building

| Project | What it is |
| --- | --- |
| **[fluxor-ide](https://github.com/CMolG/fluxor-ide)** | An open-source agentic IDE built on step-DAG flows — roles, mods, triggers, MCP client integration, backlog cards and a notification center. Flows can be containerized and deployed as detached apps exposing MCP over Streamable HTTP, so agents can talk to each other. |
| **[cognitive-skills](https://github.com/CMolG/cognitive-skills)** | A framework that extracts a person's cognitive profile and generates a personalized set of skills from it. |

**Also cooking:** RegWatch, a regulatory radar for Spanish normative sources (BOE, AEAT, TGSS, SEPE) on Drools/Kogito · a dithered component library where nothing is an SVG curve and everything is composed from atoms · a pay-per-use API catalog distributed over MCP.

<div align="center">

`░▒▓ ─────────────────────────────────────── ▓▒░`

</div>

## Shipped, not prototyped

<details open>
<summary><b>Selected production work</b></summary>

<br>

- **TuLotero** (15M+ users, high-concurrency distributed system, #1 downloaded app in the Spanish App Store during the Christmas season) — built the public MCP server; ran the pSEO + GEO + MCP initiative directly with the CEO; integrated a new payment provider from scratch with event-based rollback; built the SPEI microservice on Quarkus (~40k transactions/day); distributed + local Redis caching against a WildFly monolith. Proposed the AI workflow adoption that started internal AI use at the company.
- **Grupo DIA** (Accenture) — 15+ Quarkus microservices in a DDD domain behind a Spring API gateway with caching and multiplexing. Built the payment-methods and customer-addresses services from zero. Saga pattern, Liquibase, Pub/Sub, SQS, SES, BigQuery, testing with Mockito and Karate.
- **BMW Group / Alphabet** (Capgemini) — vehicle shipment management system; first international Scrum team, ended up coordinating it to hit the deadline.
- **Santalucía** (Capgemini) — legacy C++/Java microservices against IBM Informix, JSP backoffice, heavy reporting SQL, high L4 ticket volume.

</details>

<details>
<summary><b>Numbers I can point a commit hash at</b></summary>

<br>

- **+58% throughput** (330 → 520 rps) and **p95 295 ms → 162 ms** on a production web app
- **GraalVM native unlocked**: 0.669 s startup, **−51% build time**
- **−98% serverless invocations** and **−75% compute** on an audio fingerprinting pipeline
- **~68,000 programmatic SEO routes** shipped with 0–10 ms TBT and **CLS 0**
- God component refactored **12,077 → 1,802 lines**; E2E suite **4m12s → 48s**
- Unauthenticated `/mcp` route found and closed, documented with a failing test first

<sub>These come from an empirical pass over my own git history — traceable to commits, and separated from anything estimated. Plenty of that code was co-authored with coding agents; I don't count it as hand-typed production.</sub>

</details>

<div align="center">

`░▒▓ ─────────────────────────────────────── ▓▒░`

</div>

## Stack

**Languages**

![Java](https://img.shields.io/badge/Java%208--25-0D1117?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-0D1117?style=flat-square&logo=javascript&logoColor=white)
![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0D1117?style=flat-square&logo=kotlin&logoColor=white)
![C++](https://img.shields.io/badge/C%20%2F%20C%2B%2B-0D1117?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20%2F%20PL%2FSQL-0D1117?style=flat-square&logo=oracle&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-0D1117?style=flat-square&logo=gnubash&logoColor=white)

**Backend & runtime**

![Quarkus](https://img.shields.io/badge/Quarkus-0D1117?style=flat-square&logo=quarkus&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-0D1117?style=flat-square&logo=springboot&logoColor=white)
![Jakarta EE](https://img.shields.io/badge/Jakarta%20EE-0D1117?style=flat-square&logo=eclipseide&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate%20ORM-0D1117?style=flat-square&logo=hibernate&logoColor=white)
![GraalVM](https://img.shields.io/badge/GraalVM%20native-0D1117?style=flat-square&logo=oracle&logoColor=white)
![WildFly](https://img.shields.io/badge/WildFly-0D1117?style=flat-square&logo=redhat&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-0D1117?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-0D1117?style=flat-square&logo=graphql&logoColor=white)
![Drools](https://img.shields.io/badge/Drools%20%2F%20Kogito-0D1117?style=flat-square&logo=redhat&logoColor=white)

<sub>Spring Batch · EJB · REST · microservices · Domain-Driven Design · API gateway · saga pattern · event-driven architecture · pub/sub</sub>

**AI & agents**

![MCP](https://img.shields.io/badge/MCP%20servers-10B981?style=flat-square&logo=anthropic&logoColor=white)
![LangChain4j](https://img.shields.io/badge/LangChain4j-0D1117?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20pipelines-0D1117?style=flat-square&logo=chainlink&logoColor=white)
![Agentic workflows](https://img.shields.io/badge/agentic%20workflows-0D1117?style=flat-square&logo=probot&logoColor=white)
![Guardrails](https://img.shields.io/badge/guardrails%20%26%20invariants-0D1117?style=flat-square&logo=shieldsdotio&logoColor=white)
![Harnesses](https://img.shields.io/badge/evaluation%20harnesses-0D1117?style=flat-square&logo=testcafe&logoColor=white)

<sub>LLM integration · controlled chain of thought · regression testing with mutation · AI-assisted delivery workflows · clustering algorithms</sub>

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js%2016-0D1117?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React%2019-0D1117?style=flat-square&logo=react&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-0D1117?style=flat-square&logo=react&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-0D1117?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-0D1117?style=flat-square&logo=vite&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-0D1117?style=flat-square&logo=electron&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-0D1117?style=flat-square&logo=turborepo&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-0D1117?style=flat-square&logo=pnpm&logoColor=white)

<sub>Angular / AngularJS · Java JSP</sub>

**Data & messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-0D1117?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-0D1117?style=flat-square&logo=oracle&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-0D1117?style=flat-square&logo=googlebigquery&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-0D1117?style=flat-square&logo=elasticsearch&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase%20%2F%20Firestore-0D1117?style=flat-square&logo=firebase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-0D1117?style=flat-square&logo=rabbitmq&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-0D1117?style=flat-square&logo=liquibase&logoColor=white)

<sub>IBM Informix · Google Pub/Sub · Amazon SQS / SES · Firebase Cloud Messaging</sub>

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-0D1117?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-0D1117?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0D1117?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-0D1117?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-0D1117?style=flat-square&logo=jenkins&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-0D1117?style=flat-square&logo=gitlab&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-0D1117?style=flat-square&logo=apachemaven&logoColor=white)

<sub>Lambda · S3 · SQS · SES · Cognito · CDN · App Engine · Cloud Functions · Pub/Sub · Storage · OAuth · CI/CD pipeline design</sub>

**Quality & observability**

![JUnit](https://img.shields.io/badge/JUnit-0D1117?style=flat-square&logo=junit5&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-0D1117?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-0D1117?style=flat-square&logo=vitest&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0D1117?style=flat-square&logo=pytest&logoColor=white)
![k6](https://img.shields.io/badge/k6%20load%20testing-0D1117?style=flat-square&logo=k6&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-0D1117?style=flat-square&logo=sonarqube&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-0D1117?style=flat-square&logo=grafana&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-0D1117?style=flat-square&logo=kibana&logoColor=white)

<sub>Mockito · Karate · quality gates · code review · L3/L4 support · on-call incident response</sub>

**Payments & integrations**

![Stripe](https://img.shields.io/badge/Stripe-0D1117?style=flat-square&logo=stripe&logoColor=white)
![Google Pay](https://img.shields.io/badge/Google%20Payments-0D1117?style=flat-square&logo=googlepay&logoColor=white)
![SPEI](https://img.shields.io/badge/SPEI-0D1117?style=flat-square&logo=bank&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-0D1117?style=flat-square&logo=slack&logoColor=white)

<sub>Banking file processing (fixed-position mappers) · programmatic SEO</sub>

<div align="center">

`░▒▓ ─────────────────────────────────────── ▓▒░`

</div>

## What I think about

**Harness engineering** as an emerging discipline — the harness as the deterministic partition of the system, while context behaves as a writable partition prone to rot. **Poisoned code**: context poisoning, codebase poisoning, adversarial poisoning, and what a real detection posthook looks like. **Neuro-symbolic invariant inference.** And, further out, what an AI-native OS and its UX should actually feel like.

<div align="center">

`░▒▓ ─────────────────────────────────────── ▓▒░`

## Let's talk

I take contract work in **AI infrastructure**, **fractional CTO** engagements, **performance rescue**, and **Java modernization**. Remote, CET, available to start soon.

[![LinkedIn](https://img.shields.io/badge/Say%20hi%20on%20LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/cmolg)
[![Medium](https://img.shields.io/badge/Read%20me%20on%20Medium-0D1117?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@cmolg)
[![Email](https://img.shields.io/badge/Send%20an%20email-10B981?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cmolgaldev@gmail.com)

</div>

<!--
Optional stats card — uncomment if you want it. It counts every commit, agent-assisted ones included.

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=CMolG&show_icons=true&hide_border=true&bg_color=0D1117&title_color=10B981&text_color=C9D1D9&icon_color=10B981" alt="stats" />
</div>
-->
