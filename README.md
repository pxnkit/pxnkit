<div align="center">
  <h1>Hi, I'm Pankit Brahmkhatri 👋</h1>

  <p>
    <strong>MSc Computer Science at TU Dresden</strong><br>
    <strong>Student Research Assistant at the Chair of Materials Science and Nanotechnology</strong>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Based_in-Dresden%2C_Germany-0F172A?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Based in Dresden, Germany">
    <img src="https://img.shields.io/badge/Pronouns-he%2Fhim-7C3AED?style=for-the-badge" alt="Pronouns: he/him">
    <img src="https://img.shields.io/badge/Focus-Agent_Search_%26_Memory-0891B2?style=for-the-badge" alt="Focus: agent search and memory">
  </p>

  <p>
    <a href="https://www.linkedin.com/in/pxnkit">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
    </a>
    <a href="mailto:pankitrb@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
    </a>
    <a href="https://nano.tu-dresden.de/member/pankit-ramesh_brahmkhatri">
      <img src="https://img.shields.io/badge/TU_Dresden_Profile-005B9A?style=flat-square&logo=academia&logoColor=white" alt="TU Dresden profile">
    </a>
    <a href="https://scholar.google.com/citations?user=voLyug8AAAAJ&hl=en">
      <img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar">
    </a>
    <a href="https://orcid.org/0009-0001-2184-4005">
      <img src="https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID">
    </a>
  </p>

  <p>
    <a href="https://github.com/pxnkit">
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
    </a>
    <a href="https://www.instagram.com/pxnkit/">
      <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram">
    </a>
    <a href="https://www.threads.com/@pxnkit">
      <img src="https://img.shields.io/badge/Threads-000000?style=flat-square&logo=threads&logoColor=white" alt="Threads">
    </a>
    <a href="https://x.com/pxnkit">
      <img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" alt="X">
    </a>
  </p>
</div>

## About me

I design and evaluate adaptive agent systems that decide when to retrieve evidence, what to retain in memory, how to update from feedback, and when to act or abstain.

My work sits at the intersection of information retrieval, agent memory, test-time learning, and search-guided reasoning. I focus on systems whose decisions remain grounded in evidence, resilient to stale or conflicting memory, and measurable through reproducible experiments.

## Research focus

| Area | Problems I care about |
|---|---|
| **Adaptive evidence seeking** | Query planning, source routing, hybrid retrieval, cross-encoder reranking, provenance, evidence sufficiency, and budget-aware stopping |
| **Agent memory and test-time learning** | Episodic, semantic, and procedural memory; consolidation; temporal validity; forgetting; experience replay; feedback; and online adaptation |
| **Search-guided reasoning** | Best-of-N, beam and tree search, verifier-guided trajectories, process feedback, uncertainty estimation, adaptive compute, and calibrated act or abstain decisions |
| **Reliable agent execution** | Structured tool schemas, durable checkpoints, idempotent actions, pre-action verification, sandboxing, prompt injection testing, and memory poisoning resistance |

## Technical profile

### Core toolkit

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=111827" alt="Transformers">
  <img src="https://img.shields.io/badge/Sentence_Transformers-0F766E?style=flat-square" alt="Sentence Transformers">
  <img src="https://img.shields.io/badge/BM25_%2B_Hybrid_Search-0369A1?style=flat-square" alt="BM25 and hybrid search">
  <img src="https://img.shields.io/badge/FAISS-2563EB?style=flat-square" alt="FAISS">
  <img src="https://img.shields.io/badge/PostgreSQL_%2B_pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL and pgvector">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph">
  <img src="https://img.shields.io/badge/MCP-111827?style=flat-square" alt="Model Context Protocol">
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
</p>

I treat retrieval, memory, reasoning, and execution as one connected system. Each layer needs clear interfaces, traceable decisions, and evaluation that reflects real failure modes.

| Layer | Technologies and methods |
|---|---|
| **Engineering and data contracts** | Python, Git, Linux, PostgreSQL, `uv`, Ruff, mypy, Pydantic, FastAPI, pytest, Docker, and GitHub Actions |
| **Models and adaptation** | PyTorch, Hugging Face Transformers, Datasets, Accelerate, Sentence Transformers, PEFT and LoRA, TRL, vLLM, replay buffers, adapter versioning, and retention or forgetting evaluation |
| **Retrieval and evidence routing** | BM25 and Lucene, dense embeddings, reciprocal-rank fusion, cross-encoder reranking, FAISS, PostgreSQL and pgvector, OpenSearch, filtered ANN and HNSW, query decomposition, source routing, provenance, and evidence-sufficiency stopping |
| **Agent memory and data plane** | Episodic, semantic, and procedural memory; append-only and bi-temporal event stores; PostgreSQL for durable state; Redis for caching; DuckDB with Parquet and Arrow for trajectory data; graph storage when traversal is a core requirement |
| **Agent runtime and reasoning search** | LangGraph or explicit state machines, structured tool schemas, Model Context Protocol, durable checkpoints, timeouts, retries, idempotency, best-of-N, beam and tree search, MCTS, verifier models, uncertainty scoring, and adaptive compute allocation |
| **Evaluation and observability** | `ir_datasets` and BEIR-style corpora, `ir_measures`, pytrec_eval, ranx, Recall@k, MRR, nDCG, MLflow, OpenTelemetry traces, Brier and ECE calibration, risk-coverage curves, latency, and cost budgets |
| **Security and reliable action** | Sandboxed tools, least privilege, ACL-aware retrieval, secrets management, append-only provenance, policy gates, prompt injection tests, memory poisoning tests, and deterministic replay |

## Current research directions

- Learning retrieval and memory policies instead of relying only on fixed RAG pipelines
- Routing information between working context, external memory, and model updates
- Adapting from interaction feedback and failed trajectories while measuring retention and forgetting
- Using retrieval-grounded verification for long-horizon reasoning
- Maintaining memory freshness, provenance, temporal validity, and contradiction handling
- Building poisoning-resistant memory and prompt-injection-aware retrieval
- Calibrating when an agent should search, continue reasoning, act, ask for help, or abstain

## Collaboration

I am interested in collaborating on agent memory benchmarks, learned retrieval policies, test-time adaptation, search-guided reasoning, agent evaluation, and reliable tool-using systems.

I am especially interested in work that combines a clear research question with reproducible systems, measurable failure modes, and honest evaluation.

<p align="center">
  <a href="mailto:pankitrb@gmail.com">
    <img src="https://img.shields.io/badge/Start_a_conversation-Email_me-0891B2?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Pankit">
  </a>
</p>

## GitHub at a glance

<div align="center">
  <a href="https://github.com/pxnkit">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=pxnkit&theme=transparent" alt="Pankit Brahmkhatri's GitHub stats">
  </a>
</div>

---

<div align="center">
  <strong>Building agents that know when to search, remember, learn, act, or abstain.</strong><br>
  <sub>I use <code>pxnkit</code> as my username across platforms.</sub>
</div>

