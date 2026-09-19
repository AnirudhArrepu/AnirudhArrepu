<h1 align="center">Hi, I'm Anirudh Arrepu 👋</h1>
<h3 align="center">Backend & Distributed Systems Engineer · Systems Programming · Agentic AI</h3>

<p align="center">
CSE @ IIT Tirupati &nbsp;|&nbsp; I build the infra layer things run on — ledgers, caches, simulators, agents
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/AnirudhArrepu/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anirudharrepu@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### `whoami`

I like software that has to be *correct*, not just functional — things where a race condition, a lost message, or a bad cache invalidation actually costs someone money or data. That pulls me toward:

- **Distributed systems & backend infra** — consistency, idempotency, rate limiting, consensus, queues
- **Systems programming** — caches, memory hierarchies, pipelines, the stuff underneath the stuff
- **Agentic AI** — LLM-driven pipelines and tools that reason over code/data and take action, not just chat

Currently deep in distributed & scalable systems design, and picking up MLOps / continual learning on the side.

---

### 🛠️ Featured Work

#### ⚙️ Distributed Systems

<table>
<tr>
<td width="100%" valign="top">

**[distriKV](https://github.com/AnirudhArrepu/distriKV)**
A distributed key-value store built around Raft-based consensus for replication, an LSM-tree for persistence, and write-ahead-log recovery for crash safety.
`Distributed Systems · Raft · LSM`

</td>
</tr>
</table>

#### 🧱 Backend Infra

<table>
<tr>
<td width="100%" valign="top">

**[aetherledger](https://github.com/AnirudhArrepu/aetherledger)**
High-throughput, multi-currency double-entry accounting engine. Immutable ledger entries, snapshot-based balance projections, Bellman-Ford-style FX routing, idempotency middleware, Redis-backed distributed sliding-window rate limiting, and a transactional outbox worker for reliable webhook delivery.
`Python · FastAPI · PostgreSQL · Redis`

</td>
</tr>
</table>

#### 💻 Systems Programming

<table>
<tr>
<td width="50%" valign="top">

**[RISC-V-Simulator](https://github.com/AnirudhArrepu/RISC-V-Simulator)**
Cycle-accurate RISC-V simulator modeling a multi-compute-unit architecture: shared fetch unit, two-level cache hierarchy (configurable size/associativity/latency), hardware-modeled `SYNC` barrier synchronization, and a software-managed scratchpad memory with custom `lw_spm`/`sw_spm` instructions.
`Python · Computer Architecture`

</td>
<td width="50%" valign="top">

**[ForgeCC-multibackend-compiler](https://github.com/AnirudhArrepu/ForgeCC-multibackend-compiler)**
A compiler for a custom statically-typed language, built from scratch in C with Flex/Bison. Full frontend (lexer, parser, semantic analysis, IR generation, optimization) feeding a **retargetable backend** — the same optimized IR is lowered to either a Java transpiler or RISC-V assembly.
`C · Flex/Bison · Compilers`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[nachos-project](https://github.com/AnirudhArrepu/nachos-project)**
Extended the NachOS teaching OS with real kernel features across dedicated branches: demand paging, a heap allocator (`malloc` syscall), inter-process `pipe` syscalls, a priority-queue scheduler, a `sleep` syscall, and TLB miss handling — with CI running the OS test suite on every commit.
`C++ · Operating Systems`

</td>
<td width="50%" valign="top">

**[gpumode-software](https://github.com/AnirudhArrepu/gpumode-software)**
Frontend for a GPU-kernel benchmarking platform (**KERN**) — students submit GPU kernels which get judged and ranked. Handles JWT auth, async job polling for submission status, and a live per-question leaderboard.
`React · REST APIs`

</td>
</tr>
</table>

#### 🤖 Agentic AI

<table>
<tr>
<td width="50%" valign="top">

**[truth-ahoy](https://github.com/AnirudhArrepu/truth-ahoy)**
A multi-agent misinformation-detection system. Google ADK agents orchestrate web search (Tavily), deepfake and reverse-image detection via Cloud Vision, and Vertex AI RAG retrieval over a BigQuery-backed corpus to separate fact from fabricated media.
`Python · Google ADK · Gemini · RAG · Vertex AI`

</td>
<td width="50%" valign="top">

**[bugSensei](https://github.com/AnirudhArrepu/bugSensei-Devpost-Rag-n-Roll-Hackathon)**
A RAG-powered troubleshooting agent that turns vague error descriptions into precise, sourced fixes — built to skip the "Google it and hope" loop devs fall into when debugging.
`Python · RAG · LLM Agents`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[PACGBI-Tool-Dev](https://github.com/AnirudhArrepu/PACGBI-Tool-Dev)**
Automated COBOL generation and refactoring pipeline driven off a GitHub issue backlog, using Mistral AI + GitHub Actions. Builds a code knowledge graph to prioritize high-impact changes and drive the agentic refactor loop end-to-end.
`Python · COBOL · LLM Agents · GitHub Actions`

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

#### 🔬 Applied ML / Research

<table>
<tr>
<td width="50%" valign="top">

**[Dream11-InterIIT-TechMeet-13.0](https://github.com/AnirudhArrepu/Dream11-InterIIT-TechMeet-13.0)**
ETL pipeline for raw fantasy-sports data feeding an XGBoost-based fantasy points predictor with best-XI recommendations (MAE: 140.6). Includes a train/test data selection tool and model-metric visualizations.
`Python · XGBoost · ETL`

</td>
<td width="50%" valign="top">

**[Adobe-InterIIT-TechMeet-14.0](https://github.com/AnirudhArrepu/Adobe-InterIIT-TechMeet-14.0)**
AI-powered, Photoshop-style editor built for mobile creative workflows of the future — explores font-aware text editing directly on images and emotion-driven editing, as part of Inter-IIT Tech Meet 14.0.
`Python · AI/Computer Vision`

</td>
</tr>
</table>

---

### 🧰 Tech I reach for

**Systems / Backend:** ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/-C-00599C?style=flat-square&logo=c&logoColor=white) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![FastAPI](https://img.shields.io/badge/-FastAPI-005571?style=flat-square&logo=fastapi) ![Flask](https://img.shields.io/badge/-Flask-000?style=flat-square&logo=flask&logoColor=white) ![NodeJS](https://img.shields.io/badge/-Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)

**Data & Infra:** ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DD0031?style=flat-square&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-4ea94b?style=flat-square&logo=mongodb&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-0db7ed?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Google Cloud](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

**AI / ML:** ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Languages:** ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)

---

### 📊 GitHub Stats



<h2 align="center">GitHub Stats</h2>


<h2 align="center">GitHub Stats</h2>

<p align="center">
  <img
    src="https://raw.githubusercontent.com/AnirudhArrepu/AnirudhArrepu/main/images/userstats.svg"
    alt="Anirudh's GitHub statistics"
    width="600"
  />
</p>

<p align="center">
  <img
    src="https://streak-stats.demolab.com/?user=AnirudhArrepu&theme=gruvbox&hide_border=false"
    alt="GitHub streak stats"
  />
</p>

---

<p align="center"><i>Always down to talk distributed systems, backend architecture, or agentic AI — reach out.</i></p>
