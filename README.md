# Russell York

**Early-career AI engineering candidate | Founder, [Nyxora AI](https://nyxora-ai.com/) | Preparing for WGU's B.S. in AI Engineering**

I build practical, human-supervised AI systems that connect software engineering, data quality,
model behavior, safety boundaries, and measurable outcomes. My strongest work is documented in the
two end-to-end engineering projects below.

## Featured Engineering Projects

### [Nyxora Outcome Intelligence](https://github.com/Ryork67677/nyxora-outcome-intelligence)

[Repository](https://github.com/Ryork67677/nyxora-outcome-intelligence) | [Recorded dashboard](https://ryork67677.github.io/nyxora-outcome-intelligence/) | [CI](https://github.com/Ryork67677/nyxora-outcome-intelligence/actions/workflows/ci.yml)

An end-to-end analytics and classical machine-learning system that converts reproducible synthetic
lead events into a DuckDB warehouse, reviewed SQL marts, a booking-propensity model, drift and
calibration monitoring, a guarded FastAPI scoring service, and an operational dashboard.

- **Verified build:** 10,000 synthetic leads, 36,173 lifecycle events, and 9/9 data contracts passed
- **Holdout evaluation:** ROC AUC 0.686 versus 0.500 naive; average precision 0.667 versus 0.481 naive
- **Quality gates:** 13 automated tests, 96% measured core coverage, Docker smoke test, and GitHub Actions CI
- **Engineering evidence:** chronological evaluation, probability calibration, monitoring, model cards, API validation, and explicit limitations

### [Nyxora Lead Concierge](https://github.com/Ryork67677/nyxora-lead-concierge)

[Repository](https://github.com/Ryork67677/nyxora-lead-concierge) | [Recorded behavior demo](https://ryork67677.github.io/nyxora-lead-concierge/) | [CI](https://github.com/Ryork67677/nyxora-lead-concierge/actions/workflows/ci.yml)

A privacy-conscious lead qualification and human-handoff API. Deterministic policies handle urgent,
clinical, unsupported, and prompt-injection cases before an optional local language model can rewrite
verified facts. The model cannot override escalation or action routing.

- **Verified build:** 24 automated tests and 94% code coverage
- **Behavior evaluation:** 12/12 reviewed cases passed with 100% safety-case recall
- **Local-model integration:** `qwen3:14b` through Ollama with a deterministic fallback
- **Engineering evidence:** grounded retrieval, structured outputs, consent-gated storage, privacy minimization, evaluation, Docker, and CI

## What these projects demonstrate

- Different model choices for different problems: classical ML for outcome ranking and a constrained local LLM for language generation
- Reproducible data pipelines, reviewed SQL, API contracts, automated tests, behavior evaluations, and deployment artifacts
- Human handoff, fail-closed safety behavior, monitoring, and honest communication of synthetic-data and validation limits
- Ownership of problem framing, system boundaries, architecture decisions, validation criteria, and technical documentation

## Additional system work: Nyxora AI

[Nyxora AI](https://nyxora-ai.com/) is a broader automation project for independent med spas and
aesthetics clinics. I mapped workflows from lead intake through booking, reminders, aftercare,
reviews, rebooking, and reactivation; designed approval queues and exception handoffs; and operated
a self-hosted stack involving n8n, Docker, Caddy, Cloudflare, DNS, operational data stores, and
uptime monitoring. The two featured repositories above are the stronger code-first evidence behind
that broader product direction.

## Technical focus

**Applied in public projects:** Python, FastAPI, SQL, DuckDB, scikit-learn, Ollama, pytest, Ruff,
Docker, GitHub Actions, REST APIs, model evaluation, data contracts, monitoring, and technical documentation.

**Actively developing:** cloud deployment, production observability, authentication and secrets
management, larger evaluation sets, data structures and algorithms, and mathematics for machine learning.

## Professional background

- **Walgreens - Shift Lead (2024-present):** Coordinate daily operations, staffing, safety, customer issues, training, and documentation.
- **AT&T Wireless - Corporate Trainer (2024):** Delivered multi-location training, maintained performance tracking, and partnered with leadership on improvement plans.
- **Framebridge - Trainer (2021-2023):** Led onboarding and coaching while supporting productivity, quality, and repeatable processes.

This background shapes how I engineer systems: I pay attention to handoffs, exceptions, documentation,
user impact, and whether a workflow remains usable when conditions are imperfect.

## Current direction

- Prepare for Western Governors University's [B.S. in AI Engineering](https://www.wgu.edu/online-it-degrees/ai-engineering.html)
- Deepen software, data, cloud, mathematics, and machine-learning foundations
- Move selected portfolio systems from validated local builds toward observable, authenticated deployments
- Maintain an evidence-based [AI Engineer Roadmap](https://github.com/Ryork67677/AI-Engineer-Roadmap)

## Honest scope

I am an early-career candidate, not yet a professional software or ML engineer. These projects use
synthetic data and do not claim production adoption, clinical validation, or real-world model impact.
I use AI tools to accelerate research and implementation while remaining responsible for scope,
architecture, testing, corrections, documentation, and every published claim.
