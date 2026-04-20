# SDS 2026 Agentbricks Workshop
Build a production-ready AI agent for financial analysis — starting without code and evolving into a fully custom, code-based system.

### Part one - Agentbricks
Quickly build a working agent using Databricks tools:

- RAG over financial reports
- Structured querying via Genie
- Supervisor to orchestrate both
- Instant results with minimal setup

### Part two - Code-based agent

Rebuild the same system with full control:

- Custom nodes (Normalizer, Supervisor, Refiner, etc.)
- Dynamic routing with LangGraph
- Structured prompting with DSPy
- Fine-grained logic & decision-making

### Evaluation

We evaluate the agent using MLflow GenAI Evaluation with:

- Correctness → factual accuracy
- Relevance → is relevant to the question
- Safety → appropriate responses

This uses an LLM-as-a-Judge approach to score outputs at scale.

### ▶️ Run the Workshop
1. Complete Part 1 (No-Code) to create the supervisor agent
1. Evaluate the supervisor
1. Move to Part 2 (LangGraph Agent)
1. Deploy and evaluate your langgraph agent