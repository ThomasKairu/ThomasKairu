# Thomas Kairu

**Full-Stack Software Engineer specializing in scalable Python/TypeScript backends, Dockerized Unix environments, and deterministic test automation.**

I build reviewable software systems that run cleanly in isolated Unix containers: API services, React frontends, Bash automation, and PyTest-backed evaluation harnesses. My current portfolio is intentionally aligned with full-stack code-evaluation work: secure routing, dependency hygiene, Docker execution, terminal-first tooling, and tests that catch real edge cases.

## Core Engineering Signals

| Signal | What I demonstrate | Tools |
|---|---|---|
| Backend architecture | Secure API routing, ownership checks, error envelopes, multi-file database models | Python, FastAPI, SQLAlchemy, PostgreSQL |
| Frontend delivery | Typed API client, authenticated workflow UI, production Vite build | React, TypeScript, Vite |
| Unix automation | Log processing, redaction, directory manifests, API probes | Bash, awk, sed, curl, coreutils |
| Test automation | Deterministic assertions, malformed input coverage, path-safety checks, performance regression tests | PyTest, subprocess testing, coverage |
| Containerization | Alpine-based Dockerfiles with clear runtime commands and ports | Docker, Docker Compose |

## Pinned Portfolio Repositories

### 1. [`caseflow-fullstack-platform`](https://github.com/ThomasKairu/caseflow-fullstack-platform)
A full-stack review platform with FastAPI, PostgreSQL-ready SQLAlchemy models, React/TypeScript UI, JWT auth, centralized error handling, `.env.example`, Docker Compose, and PyTest coverage for auth, ownership, and deterministic evaluation scoring.

```bash
cd backend
pip install -r requirements.txt
pytest -q
```

### 2. [`unix-log-forensics-cli`](https://github.com/ThomasKairu/unix-log-forensics-cli)
A terminal-driven Bash toolkit that summarizes service logs, extracts anomalies, redacts IP/email values, hashes directory manifests, and probes HTTP APIs using command-line arguments.

```bash
pip install -r requirements.txt
pytest -q
```

### 3. [`deterministic-code-eval-sandbox`](https://github.com/ThomasKairu/deterministic-code-eval-sandbox)
A standalone Python library for evaluating challenge outputs deterministically, with PyTest coverage for normalization, malformed key/value input, path traversal protection, weighted scoring, and large-output performance.

```bash
pip install -r requirements.txt
pytest -q
```

## Toolbox

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="PyTest" src="https://img.shields.io/badge/PyTest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img alt="Bash" src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white" />
</p>

## How I Work

- Write reproducible setup instructions before implementation details become tribal knowledge.
- Keep secrets out of code and document configuration through `.env.example` files.
- Prefer deterministic tests that verify behavior through public interfaces.
- Containerize projects so reviewers can run them without ambient machine assumptions.
- Use semantic commits such as `feat:`, `test:`, `docs:`, `fix:`, and `chore:` so project history is easy to audit.

## Current Focus

I am deepening my full-stack engineering portfolio around AI-evaluation workflows: secure APIs, Dockerized Unix execution, command-line automation, and automated grading/test harnesses.


