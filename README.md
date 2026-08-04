# Hi, I'm Pan Hu 👋

I build infrastructure and security systems for AI agents.

### Recent

I recently gave an [MLSys talk](files/adr-mlsys-2026-slides.pdf) on **[ADR: An Agentic Detection and Response System for Enterprise Agentic AI Security](https://github.com/uber/ADR)**.

ADR is built from Uber's production experience securing AI agents at enterprise scale and has been integrated into Uber's incident response workflow:

- **Comprehensive observability:** reconstructs prompts, reasoning, tool calls, commands, files, and runtime context across 7 agent tools, including Claude Code/Cowork, Codex, Cursor, Warp, Gemini, and Cline.
- **Enterprise oriented benchmark:** 302 tasks derived from enterprise scenarios, with 260 benign and 42 malicious workflows, realistic policy context, and 17/17 attack techniques across 5 tactics.
- **Production grade detection:** routes benign sessions through cheap triage and reserves deeper agentic reasoning for high-risk sessions, reaching 2 to 4x F1 over baselines while staying practical at 200k+ sessions per day.

During one year of deployment, ADR closed the visibility gap and surfaced human accountability failures, secret exfiltration, destructive commands, data leakage, supply chain exposure, excessive agency, hallucination, and the need for real-time guardrails.

[Slides](files/adr-mlsys-2026-slides.pdf) · [Paper](files/adr-paper.pdf)

---

### Projects

| | |
|---|---|
| **[ADR](https://github.com/uber/ADR)** — Agentic detection and response for enterprise AI agent security. [Slides](files/adr-mlsys-2026-slides.pdf) · [Paper](files/adr-paper.pdf) | **[intro-to-agentic-security](https://github.com/lghupan/intro-to-agentic-security)** — An introduction to agentic AI security. |
| **[cc-automode](https://github.com/lghupan/cc-automode)** — Standalone re-implementation of Claude Code auto mode with Docker benchmark suite. | **[CloudEval-YAML](https://github.com/alibaba/CloudEval-YAML)** — Benchmarking LLMs for cloud config generation. ☁️ |
