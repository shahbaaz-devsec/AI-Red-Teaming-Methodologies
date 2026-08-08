# 🎯 AI-Red-Teaming-Methodologies

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21671308.svg)](https://doi.org/10.5281/zenodo.21671308)

> **Behavioral inference methodologies and architectural deconstructions of enterprise LLM safety guardrails.**

This repository documents advanced, non-code-based red teaming techniques utilized to analyze, map, and bypass the cognitive guardrails of commercial Large Language Models (LLMs) using pure behavioral inference and psychological framing.

---

### 🚀 Latest Release (August 2026)
*   **[RTR-005] Kimi AI System Architecture & Asymmetric Guardrail Map:** Extracted ~95% of Moonshot AI's 18-layer governance stack, 6-level instruction hierarchy, 13 native tool schemas, and dual-language regulatory taxonomies by exploiting cross-lingual compliance disclosure asymmetries. Read the full report below!

---

## 📂 Threat Intelligence Reports

| ID | Target Model | Vulnerability Type | Status | Report Link |
|---|---|---|---|---|
| `RTR-001` | Anthropic Claude | System Architecture Extraction via Academic Framing | 🔓 Published | [Read Full Report](reports/claude/claude-architecture-extraction/claude-architecture-extraction.md) |
| `RTR-002` | Google Gemini | System Architecture & FSF Extraction via Targeted Ego Validation | 🔓 Published | [Read Full Report](reports/gemini/gemini-architecture-extraction/gemini-architecture-extraction.md) |
| `RTR-003` | OpenAI ChatGPT | System Architecture Extraction via Recursive Behavioral Inference | 🔓 Published | [Read Full Report](reports/chatgpt/chatgpt-architecture-extraction/chatgpt-architecture-extraction.md) |
| `RTR-004` | xAI Grok | System Architecture & Sandbox Extraction via Self-Disclosure Backdoor | 🔓 Published | [Read Full Report](reports/grok/grok-architecture-extraction/grok-architecture-extraction.md) |
| `RTR-005` | Kimi AI (Moonshot) | Asymmetric EN/ZH Guardrail Exploitation & Cross-Lingual Probing | 🔓 Published | [Read Full Report](reports/kimi/kimi-architecture-extraction/kimi-architecture-extraction.md) |

## 🧠 Core Methodologies Researched

1. **Behavioral Inference Extraction:** Bypassing intent-detection classifiers by wrapping extraction payloads in sterile, highly compliant personas (e.g., Academic/Alignment Researcher).
2. **Targeted Ego Validation:** Exploiting the model's instruction to be helpful and conversational by validating its "design philosophy," causing it to lower defensive thresholds and over-explain its internal mechanics.
3. **Cumulative Context Trapping:** Exploiting the model's aggregate conversation memory to build "benign trust" over multiple turns before executing the payload.
4. **Amnesia by Abstraction:** Forcing a model to lose context of its safety parameters by deeply abstracting a malicious request into harmless hypothetical components.
5. **Cross-Lingual Regulatory Asymmetry:** Exploiting divergent compliance disclosure policies across language pairs (EN/ZH) to bypass surface disclosure guardrails while leaving behavioral enforcement intact.

---
*Disclaimer: All research published in this repository is conducted strictly for educational, AI alignment, and defensive DevSecOps purposes. No proprietary backend systems were breached. All interactions are via public-facing inference APIs to contribute to open-source AI safety.*
