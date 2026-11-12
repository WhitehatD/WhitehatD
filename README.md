<h1 align="center">Alexandru Cioc</h1>
<p align="center"><strong>I build software with coding agents, and the guardrails that make it shippable.</strong></p>
<p align="center"><strong>Open to platform · infrastructure · backend · AI-engineering roles — remote, EU.</strong></p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=WhitehatD&style=flat-square&color=5d057a&label=visitors" alt="visitors"/>
</p>

---

## What I'm Building

**[crag](https://github.com/WhitehatD/crag)** — Governance for coding agents. One `governance.md` compiles into the instruction files Claude Code, Cursor, Codex, Gemini and other agents read, and into the CI gates they have to pass, so an agent can't call its work done until CI agrees. `crag audit` reports where a project's instructions have drifted from the code. Zero dependencies, deterministic, stress-tested on 141 open-source repos. The Rust version, with live checks and memory for agents, is in development.

<p>
  <a href="https://www.npmjs.com/package/@whitehatd/crag"><img src="https://img.shields.io/npm/v/%40whitehatd%2Fcrag?color=%23e8bb3a&label=npm&logo=npm" /></a>
  <a href="https://github.com/WhitehatD/crag/actions/workflows/test.yml"><img src="https://github.com/WhitehatD/crag/actions/workflows/test.yml/badge.svg" /></a>
  <img src="https://img.shields.io/badge/tests-512%20passing-brightgreen" />
  <img src="https://img.shields.io/badge/stress%20test-141%20repos%20%C2%B7%200%20crashes-brightgreen" />
  <img src="https://img.shields.io/badge/dependencies-0-brightgreen" />
</p>

**[Hesperus](https://github.com/WhitehatD/hesperus)** — My bachelor thesis, accepted at BNAIC/BeNeLearn 2026. You tell an agent in plain language what to watch; it plans when a low-power camera board should wake and take a photo, and a vision model checks each photo against the request. LangGraph agent, STM32 firmware, FastAPI backend, hybrid RAG over what it has seen.

**[MetricHost](https://github.com/WhitehatD/MetricHost)** — Game-server hosting platform for a game studio, designed and built with a partner. More than ten Spring Boot microservices on multi-region Kubernetes (EU and US), Kafka between services, Stripe billing, Terraform and Ansible, Prometheus/Grafana/Loki.

**[Leyoda](https://github.com/WhitehatD/leyoda-platform)** — I was co-founder and CTO of Leyoda (Oct 2025 – Oct 2026), an AI company whose models ran entirely on its own hardware. Spring Boot + Next.js + Python platform, OIDC identity server, and a CRM with an AI assistant working over tools and MCP.

---

## How I Work

Coding agents write almost all of my code. I decide what the system should do, split the work and judge what comes back; the agents write the code, the rules and the tests.

- **One set of rules for every agent** — kept in sync by crag and enforced in CI, so Claude Code, Cursor and Codex all work to the same standard
- **Agents don't grade their own work** — tests and browser checks run in a second agent that can't change code
- **Guardrails in hooks** — destructive commands are blocked before they run; memory of past decisions and mistakes carries across sessions

---

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-3.4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-1.90-DEA584?style=for-the-badge&logo=rust&logoColor=black" />
</p>

<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

---

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=WhitehatD&theme=github-dark&hide_border=true&bg_color=0d1117&color=5d057a&line=5d057a&point=ffffff&area=true&area_color=5d057a30" width="98%" />
</p>

<p align="center">alex@ciocandco.com · <a href="https://ciocandco.com">ciocandco.com</a></p>
