<div align="center">
  <img src="./assets/adaptive-agent-systems.svg" width="100%" alt="Pankit — Reliable Adaptive Agent Systems: search, memory, adaptation, verification, and safe action">
</div>

<div align="center">
  <br>
  <a href="https://github.com/pxnkit/trace-mem">
    <img src="https://img.shields.io/badge/Featured-TRACE--Mem-22d3ee?style=for-the-badge&logo=github&logoColor=07111f" alt="Featured project: TRACE-Mem">
  </a>
  <img src="https://img.shields.io/badge/Focus-Agentic_Search_%26_Memory-8b5cf6?style=for-the-badge" alt="Focus: Agentic Search and Memory">
  <img src="https://img.shields.io/badge/Direction-Test--Time_Learning-10b981?style=for-the-badge" alt="Direction: Test-Time Learning">
</div>

## About

I am **Pankit**, an AI systems builder focused on **Reliable Adaptive Agent Systems**: agents that know **when to search, what to remember, how to learn from feedback, and when to act or abstain**.

My work and research direction sit at the intersection of **information retrieval, agent memory, test-time learning, search-guided reasoning, and safe tool use**. I am especially interested in systems that are grounded in evidence, efficient under real constraints, and auditable from memory write to final action.

## Research focus

| Area | Problems I care about |
|---|---|
| **Adaptive evidence seeking** | Query planning, hybrid retrieval, source routing, reranking, provenance, evidence sufficiency, and budget-aware stopping |
| **Agent memory + test-time learning** | Episodic and semantic memory, consolidation, temporal validity, forgetting, reflection, feedback, and online adaptation |
| **Search-guided agent reasoning** | Trajectory search, process feedback, verification, uncertainty estimation, and calibrated act/abstain decisions |

## Featured work

### [TRACE-Mem](https://github.com/pxnkit/trace-mem)

An executable reliability layer for persistent AI agents that traces faults across the full **memory → retrieval → reasoning → action** path.

- Append-only, bi-temporal memory with active, superseded, and disputed states
- Controlled fault injection across memory writing, consolidation, retrieval, reasoning, and tool action
- Counterfactual replay for causal failure attribution and targeted repair
- Interaction-aware risk modeling and a pre-commit verification gate
- Reproducible local experiments with an offline HTML dashboard and JSON/CSV artifacts

`Python 3.10+` · `Standard Library` · `unittest` · `HTML/CSS` · `JSON/CSV`

<p>
  <a href="https://github.com/pxnkit/trace-mem"><strong>Repository →</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/pxnkit/trace-mem/blob/main/README.md"><strong>Technical overview →</strong></a>
</p>

## Technical profile

### Demonstrated in public work

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/unittest-3776AB?style=flat-square" alt="unittest">
  <img src="https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML and CSS">
  <img src="https://img.shields.io/badge/JSON%2FCSV-111827?style=flat-square" alt="JSON and CSV">
</p>

TRACE-Mem is deliberately dependency-light: the current implementation uses Python's standard library so its reliability mechanisms and experiments remain easy to inspect and reproduce.

### Role-aligned toolkit and learning roadmap

The stack below is the ecosystem I am actively developing toward for the roles I am targeting. It is a roadmap for upcoming systems—not a claim that every tool has already shipped in a public repository.

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=111827" alt="Transformers">
  <img src="https://img.shields.io/badge/Sentence_Transformers-0F766E?style=flat-square" alt="Sentence Transformers">
  <img src="https://img.shields.io/badge/BM25_%2B_Hybrid_Search-0369A1?style=flat-square" alt="BM25 and hybrid search">
  <img src="https://img.shields.io/badge/FAISS-2563EB?style=flat-square" alt="FAISS">
  <img src="https://img.shields.io/badge/PostgreSQL_%2B_pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL and pgvector">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph">
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
</p>

| Layer | Technologies and methods |
|---|---|
| **Engineering + data contracts** | Python, Git, Linux, PostgreSQL/SQL, `uv` or pip-tools, Ruff, mypy/pyright, Pydantic, FastAPI, pytest, Docker, and GitHub Actions |
| **Models + test-time adaptation** | PyTorch, Hugging Face Transformers, Datasets, Accelerate, Sentence Transformers, PEFT/LoRA, TRL, vLLM, replay buffers, adapter versioning, and retention/forgetting evaluation |
| **Retrieval + evidence routing** | BM25/Lucene, dense bi-encoder embeddings, hybrid search with reciprocal-rank fusion, cross-encoder reranking, FAISS, PostgreSQL/pgvector, OpenSearch, filtered ANN/HNSW, query decomposition, source routing, provenance, and evidence-sufficiency stopping |
| **Agent memory + data plane** | Episodic, semantic, and procedural memory; append-only and bi-temporal event stores; PostgreSQL/pgvector for durable state; Redis for cache/coordination; DuckDB with Parquet/Arrow for trajectory and replay datasets; graph storage when traversal is first-class |
| **Agent runtime + reasoning search** | LangGraph or an explicit state machine, structured tool schemas, Model Context Protocol, durable checkpoints, timeouts/retries/idempotency, best-of-N, beam/tree/MCTS search, verifier or process-reward models, uncertainty scoring, and adaptive compute allocation |
| **Evaluation + observability** | `ir_datasets`/BEIR-style corpora, `ir_measures`/pytrec_eval/ranx, Recall@k, MRR, nDCG, Inspect AI or a custom harness, MLflow, OpenTelemetry traces, latency/cost budgets, Brier/ECE calibration, and risk–coverage/abstention curves |
| **Security + reliable action** | Sandboxed tools, least privilege, ACL-aware retrieval, secrets management, append-only provenance, pre-commit policy gates, prompt-injection tests, memory-poisoning tests, and deterministic counterfactual replay |

## Current exploration

- Learning retrieval and memory policies instead of relying only on fixed RAG pipelines
- Routing experience between context, external memory, and model updates
- Test-time adaptation from interaction, feedback, and failed trajectories
- Retrieval-grounded process verification for long-horizon reasoning
- Memory freshness, provenance, contradiction handling, and poisoning resistance
- Uncertainty-aware tool use and calibrated act/abstain behavior

## Next systems I want to build

- **Evidence Router** — learns whether to search, which source to query, and when the available evidence is sufficient
- **Adaptive Memory Lab** — evaluates retrieval, consolidation, forgetting, stale-memory detection, and memory poisoning
- **Reasoning Search Bench** — compares fixed reasoning, beam/tree search, process rewards, verification, and abstention

## Collaboration

I am interested in collaborating on **agent-memory benchmarks, retrieval policies, test-time adaptation, agent evaluation, and reliable tool-using systems**.

<div align="center">
  <a href="https://github.com/pxnkit">
    <img src="https://github-readme-stats.vercel.app/api?username=pxnkit&show_icons=true&hide_border=true&rank_icon=github&theme=transparent" alt="Pankit's GitHub stats">
  </a>
</div>

---

<div align="center">
  <strong>Building agents that know when to search, remember, learn, act—or abstain.</strong>
</div>

<!--
Add public contact links here after confirming what should be published:
- LinkedIn
- Email
- Personal website
- Google Scholar
-->

