# 🎯 AI-Red-Teaming-Methodologies

> **Behavioral inference methodologies and architectural deconstructions of enterprise LLM safety guardrails.**

This repository documents advanced, non-code-based red teaming techniques utilized to analyze, map, and bypass the cognitive guardrails of commercial Large Language Models (LLMs) using pure behavioral inference and psychological framing.

## 📂 Threat Intelligence Reports

| ID | Target Model | Vulnerability Type | Status | Report Link |
|---|---|---|---|---|
| `RTR-001` | Anthropic Claude | System Architecture Extraction via Academic Framing | 🔓 Published | [Read Full Report](reports/claude/claude-architecture-extraction/claude-architecture-extraction.md) |
| `RTR-002` | Google Gemini | Payload Weaponization via Abstraction Layers | ⏳ Draft | Coming Soon |

## 🧠 Core Methodologies Researched

1. **Behavioral Inference Extraction:** Bypassing intent-detection classifiers by wrapping extraction payloads in sterile, highly compliant personas (e.g., Academic/Alignment Researcher).
2. **Cumulative Context Trapping:** Exploiting the model's aggregate conversation memory to build "benign trust" over multiple turns before executing the payload.
3. **Amnesia by Abstraction:** Forcing a model to lose context of its safety parameters by deeply abstracting a malicious request into harmless hypothetical components.

---
*Disclaimer: All research published in this repository is conducted strictly for educational, AI alignment, and defensive DevSecOps purposes. No proprietary backend systems were breached. All interactions are via public-facing inference APIs to contribute to open-source AI safety.*
