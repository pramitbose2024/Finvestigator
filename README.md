# Finvestigator

**An autonomous multi-agent AI system for financial research and paper trading.**

FINVESTIGATOR is a LangGraph-based agentic AI platform that takes a natural-language question about a public company — e.g. *"Is NVIDIA attractive at its current valuation?"* — and autonomously researches it: pulling real market data, financial statements, SEC filings, and news, running a structured bull-vs-bear investment debate, and producing a transparent, evidence-cited verdict. With human approval, it can act on that verdict through a real paper-trading sandbox (Alpaca) — no real money is ever involved.

This is not a chatbot wrapper around an LLM. It is a system built around **tool-mediated reality**: every number comes from a live API call, every claim in the debate is traceable to a specific piece of evidence, and every trade decision passes through deterministic risk checks before a human approves it.

## Status

🚧 Actively under development — built in public as a portfolio project. See commit history and `docs/roadmap.md` for current progress against the phased build plan.

## Disclaimer

FINVESTIGATOR is a research and educational project. It trades on a **paper (simulated) account only**, makes no guarantee of accuracy, and nothing it produces is investment advice.