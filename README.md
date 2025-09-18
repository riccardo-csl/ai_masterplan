# AI Masterplan (Sep 2025 → May 2026)

[![CI](https://github.com/riccardo-csl/ai-masterplan/actions/workflows/ci.yml/badge.svg)](https://github.com/riccardo-csl/ai-masterplan/actions/workflows/ci.yml)

This repository serves as the headquarters of my journey to become an AI & Data Science Engineer.  
It contains the roadmap, weekly logs, and links to the projects developed between September 2025 and May 2026.

---

## Goals
- Develop advanced skills in Machine Learning, Deep Learning, MLOps, and Data Engineering.
- Build end-to-end projects (real data → models → APIs/services → demos).
- Create a clear and professional GitHub portfolio.
- Deliver demos and technical talks within the NYC community.

---

## Main Roadmap

### September 2025 — Setup
- [x] Create `ai-masterplan` repository (CI, linting, tests, pre-commit)
- [ ] Select dataset for the first project (Tabular ML)
- [ ] Write `docs/problem.md` (brief with KPIs and objectives)

### October 2025 — Tabular ML Pipeline
- [ ] EDA and baselines
- [ ] Tree-based models and hyperparameter tuning
- [ ] Model Card v1 + robustness tests
- [ ] Serving with FastAPI + Docker

### November 2025 — Deep Learning Foundations
- [ ] Autodiff and backprop from scratch
- [ ] Tiny language model (makemore-style)
- [ ] PyTorch baseline on real dataset

### December 2025 — MLOps & Infra
(coming soon)

### …
The complete roadmap is described in [docs/roadmap.md](./docs/roadmap.md).

---

## Repository Structure
```
ai-masterplan/
├── docs/            # Weekly logs, roadmap, metrics
├── tests/           # Smoke tests for CI
├── .github/         # Workflow CI/CD
├── pyproject.toml   # Ruff + pytest configurations
├── .pre-commit-config.yaml
└── README.md
```

---

## Local Setup
```bash
git clone git@github.com:riccardo-csl/ai-masterplan.git
cd ai-masterplan
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt  # (if present)
pre-commit install
pytest -q
```

---

## Progress Tracker
- September → Setup
- October → Tabular ML Pipeline
- November → Deep Learning Foundations
- December → MLOps Infra
- January → Enterprise RAG
- February → Forecast Workbench
- March → Optimization Engine
- April → Business AI Control Tower
- May → Polishing & Portfolio

---

## Projects (coming soon)
As projects are created, they will be linked here:

- [ ] Tabular ML Pipeline → (link coming soon)
- [ ] Deep Learning Foundations → (link coming soon)
- [ ] MLOps Infra → (link coming soon)
- [ ] Enterprise RAG → (link coming soon)
- [ ] Forecast Workbench → (link coming soon)
- [ ] Optimization Engine → (link coming soon)
- [ ] Business AI Control Tower → (link coming soon)

---

## Author
Riccardo Casaula — MSc Intelligent Systems @ UCBM & MS Data Science @ Pace University (NYC)  
LinkedIn: https://linkedin.com  
GitHub: https://github.com/riccardo-csl
