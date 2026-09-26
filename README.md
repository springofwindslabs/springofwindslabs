# SpringOfWinds Labs

**Enterprise LLM Alignment Data** — strict JSONL synthetic datasets for training and evaluating LLM agents.

![Schema Compliance](https://img.shields.io/badge/Schema_Compliance-100.00%25-brightgreen)
![JSON Validity](https://img.shields.io/badge/JSON_Validity-100.00%25-brightgreen)
![Rows Validated](https://img.shields.io/badge/Rows_Validated-28%2C922-blue)

**Validation-first:** every shipped row (28,922 total) passes a deterministic schema validator —
measured, published, and independently reproducible with a stdlib-only script.
→ [Validation evidence](https://github.com/springofwindslabs/springofwinds-datasets/blob/main/evaluation/EVALS.md)

## What we build

| Dataset | Focus | Format |
|---|---|---|
| MCP Agent Trajectory | Multi-step tool-use trajectories for MCP agents | ShareGPT-style JSONL |
| Function Calling (EN) | English function-calling conversations | ShareGPT-style JSONL |
| Function Calling (JA) | Japanese function-calling conversations | ShareGPT-style JSONL |
| Regulatory Compliance CoT | Step-by-step regulatory reasoning | Structured CoT JSONL |

## Where to get them

- 📂 **Schemas & free samples** → [springofwinds-datasets](https://github.com/springofwindslabs/springofwinds-datasets)
- 🤗 **Trial versions (50 rows, free)** → [huggingface.co/springofwindslabs](https://huggingface.co/springofwindslabs)
- 🛒 **Full versions** → [springofwindslabs.gumroad.com](https://springofwindslabs.gumroad.com)

## Quality standards

- Strict JSONL — every line validates against a published schema
- Consistent role/turn structure for direct use in SFT pipelines
- Reproducible generation with documented QA checks
- **Published validation results** — full-corpus pass rates measured on every release, with a
  [reproduction script](https://github.com/springofwindslabs/springofwinds-datasets/blob/main/evaluation/validate_jsonl.py) anyone can run

---

*Static announcements only. For inquiries, see the dataset pages above.*

---

### Enterprise Procurement
For licensing, corporate invoicing, procurement review, or custom commercial agreements:
✉️ springofwindslabs@gmail.com
