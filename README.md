# Hi, I'm YIXIN

I build **AI agents, retrieval systems, and production-oriented LLM applications**.

My current focus is on turning LLM prototypes into structured software systems with **tool calling, RAG, context engineering, evaluation, reliability, and observability**.

## Featured Projects

### [Production Knowledge Research Agent](https://github.com/Roxin-ChaI/production-knowledge-research-agent)

A production-oriented **single-agent research system** with a **LangGraph-orchestrated bounded runtime**, combining:

* LangGraph runtime orchestration
* DeepSeek V4 Flash
* PostgreSQL + pgvector
* Hybrid retrieval and Reciprocal Rank Fusion
* Knowledge Search + Web Search
* Evidence grounding and citation verification
* Research planning and evaluation
* Redis async jobs
* OpenTelemetry observability
* Retry, timeout, and deadline reliability
* Docker-based infrastructure
* Real end-to-end validation

The v0.3.0 runtime migration replaces the handwritten agent control loop with LangGraph while preserving the existing ModelClient, ToolExecutor, domain contracts, execution limits, exception semantics, and observability boundaries.

**Quality baseline:** 1057 tests passed<br>
**Latest Real E2E baseline:** 3/3 PASS (v0.2.0)


---

### [Web Research Agent](https://github.com/Roxin-ChaI/web-research-agent)

A focused implementation of a **single-agent ReAct and Tool Calling workflow** using DeepSeek V4 Flash and Web Search.

Built to explore the core mechanics behind:

`LLM → Tool Call → Search → Observation → Reasoning → Final Answer`

without relying on large agent frameworks.

---

### [Context Window Compressor](https://github.com/Roxin-ChaI/context-window-compressor)

A context-engineering library for managing LLM context-window constraints.

Explores:

* Token budgeting
* Context partitioning
* Truncation strategies
* Windowed summarization
* Tool-call preservation
* Compression evaluation

## What I'm Working On

My projects currently focus on four areas:

* **AI Agents** — LangGraph, Tool Calling, ReAct, bounded agent runtimes
* **RAG & Retrieval** — embeddings, pgvector, hybrid retrieval, reranking
* **Context Engineering** — token budgets and context compression
* **AI System Engineering** — evaluation, grounding, reliability, observability, async jobs, Docker

## Engineering Stack

**Languages**

`Python` · `C++`

**AI / LLM**

`LangGraph` · `LLM Agents` · `Tool Calling` · `RAG` · `Embeddings` · `Context Engineering` · `Evaluation` · `Grounding`

**Backend & Data**

`FastAPI` · `PostgreSQL` · `pgvector` · `Redis` · `SQLAlchemy`

**Engineering**

`Docker` · `GitHub Actions` · `OpenTelemetry` · `pytest` · `Ruff` · `mypy`

## Project Progression

My public repositories document a progression from software engineering fundamentals toward increasingly complete AI-agent systems:

`CLI & Backend Engineering`
→ `Tool Calling`
→ `Single-Agent Systems`
→ `Context Engineering`
→ `Retrieval & Evaluation`
→ `Production-Oriented Research Agents`

---

Most of my repositories include tests, documentation, reproducible workflows, and explicit implementation boundaries rather than presenting prototypes as production-ready systems.
