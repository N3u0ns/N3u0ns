# N3ur0ns

Building evidence-driven AI systems for LLM infrastructure and research
automation.

I care about AI systems where claims are checked against artifacts, contracts,
and reproducible evidence instead of being trusted because they sound plausible.

## Current Focus

**SPEAR-Infer** is an artifact-first evidence layer for LLM inference
performance. It normalizes SGLang benchmark artifacts, checks whether runs are
comparable, detects performance changes, builds evidence-linked observations,
and writes deterministic reports for regression analysis.

Status: pre-alpha, preparing for public release.

**Empirical Wizard** is a private AI product for empirical social-science
workflows. It turns uploaded data and a research question into econometric
plans, deterministic Stata/Python/R execution, reproducible Word reports, code
packages, and audit trails.

Status: private product development.

## What I Build

- LLM serving and inference-performance tooling around SGLang/vLLM-style
  artifacts.
- Deterministic evaluation and reporting pipelines where conclusions map back
  to data, logs, and evidence IDs.
- Research automation systems for applied empirical analysis.
- Product-grade backends with explicit contracts, CI, quality gates, and honest
  failure modes.

## Engineering Taste

- Deterministic core first; agents and LLMs belong outside trusted decision
  paths.
- Artifact-first workflows: preserve raw inputs, normalize carefully, and make
  every conclusion traceable.
- Honest capability boundaries: say "unsupported", "insufficient evidence", or
  "diagnostic only" when that is the real state.
- Reproducible outputs: stable schemas, audit trails, tests, and report gates.

## Open-source Interests

I follow and build around:

`SGLang` | `vLLM` | `PyTorch` | `Transformers` | `NumPy` | `Pandas`

## Tech

Python | TypeScript/JavaScript | Flask | Pydantic | Typer | pytest | Docker |
Stata/R/Python data pipelines
