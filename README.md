# SpringOfWinds Labs

**Enterprise LLM Alignment Data** — strict JSONL synthetic datasets for training and evaluating LLM agents.

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

---

*Static announcements only. For inquiries, see the dataset pages above.*
