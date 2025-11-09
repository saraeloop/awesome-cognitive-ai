[English](../README.md) | [Español](README.es.md)

# AutoEval Pipeline Template

Example continuous-evaluation harness used throughout **Awesome Cognitive-AI** to keep RAG + agent projects measurable.

## Overview

- **Purpose:** demonstrate how to run deterministic evaluation suites (accuracy, hallucination, latency) whenever prompts or retrieval are updated.  
- **Tech stack:** GitHub Actions + Python evaluator scripts (TruLens/Ragas) + Langfuse traces for regressions.  
- **Artifacts:** `reports/*.json`, `runs/*.jsonl`, and dashboards that can be attached to PRs.

## Key components

1. **Evaluator config** – YAML describing scenarios, data slices, metrics, thresholds.  
2. **Dataset fetcher** – syncs benchmark questions and ground truth answers (e.g., HotpotQA subset).  
3. **Runner** – executes pipelines, logs spans, and uploads artifacts to Langfuse/Braintrust.  
4. **Gatekeeper** – fails CI if guardrail or metric thresholds regress.

## How to reuse

1. Fork the template (coming soon) or copy the workflow snippets below.  
2. Drop your own `dataset/*.jsonl` pairs and adjust metric weights.  
3. Publish `reports/*.md` with summarized findings so regressions stay visible.

```yaml
# .github/workflows/autoeval.yml
name: autoeval
on:
  pull_request:
  workflow_dispatch:
jobs:
  eval:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-python@v5
        with:
          python-version: '3.11'
      - run: pip install -r scripts/requirements-autoeval.txt
      - run: python scripts/run_autoeval.py --config configs/autoeval.yaml
      - uses: actions/upload-artifact@v4
        with:
          name: autoeval-report
          path: reports/
```

> ℹ️ Looking for a maintained starter? Watch this repo for the upcoming `examples/autoeval-pipeline/` drop or open an issue to collaborate.
