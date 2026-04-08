<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=220&section=header&text=Manasa%20Deshagouni&fontSize=42&fontColor=58a6ff&fontAlignY=35&desc=Production%20ML%20·%20GenAI%20Systems%20·%20Embeddings%20%26%20Retrieval%20·%20Backend%20at%20Scale&descSize=14&descColor=8b949e&descAlignY=55&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/deshagounimanasa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://glittering-snickerdoodle-8c9296.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <a href="mailto:manasadprep@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=I+build+AI+systems+that+survive+contact+with+production." />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/severe_incidents-↓80%25-2ea44f?style=flat-square" />
  <img src="https://img.shields.io/badge/GenAI_MVP-4_weeks_to_prod-2ea44f?style=flat-square" />
  <img src="https://img.shields.io/badge/platform-5k%2B_users-2ea44f?style=flat-square" />
  <img src="https://img.shields.io/badge/inference_p95-85ms-2ea44f?style=flat-square" />
</p>

---

## `~/about`

I’m **Manasa**, a Master's student in **Computer Science at San José State University** and a **Graduate Research Assistant** working on **zero-shot malware attribution** with metric-learned embeddings.

Previously, I spent 2 years at **Optum (UnitedHealth Group)** shipping **production ML**, **GenAI features**, and **backend systems** for a secure platform used by **5k+ users**.

I care about the part of ML that actually gets used: **retrieval**, **inference**, **guardrails**, **evaluation**, **rollout safety**, and the systems that turn predictions into action.

- 🔬 **Currently researching:** zero-shot retrieval, metric learning, FAISS-based search
- 🧠 **Interested in:** production ML, GenAI/RAG, embeddings, backend systems
- 🤝 **Open to:** SWE, MLE, Applied ML, and Research Engineer roles

> **Philosophy:** Research matters. Production proves it.

---

## `impact.log`

- Built an ML system that **reduced severe incidents by ~80%**
- Took **GenAI features from MVP to production in 4 weeks**
- Shipped systems on a platform serving **5k+ users**
- Built low-latency inference workflows with **~85 ms p95**
- Researching **cross-domain generalization** with metric-learned embeddings

---

## `projects/featured`

### 🧠 [Digital Life Curator](https://github.com/manasa-deshagouni/digital-life-curator)
**Adaptive multimodal RAG system**

A local-first knowledge agent for PDFs, notes, images, receipts, and code snippets.

**What it does**
- Generates multimodal embeddings using **MiniLM** for text and **CLIP** for images
- Stores chunk-level vectors and metadata in a **FAISS HNSW** index
- Supports **semantic search**, **contextual Q&A**, **summarization**, **explainable ranking**, and **related-content discovery**

**Highlights**
- **100k+ documents**
- **< 500 ms retrieval latency**
- Adaptive retrieval with **metadata filtering** and **temporal reranking**

**Stack:** `Python` `FAISS` `CLIP` `Streamlit` `Hugging Face`

---

### 🔔 [NotifyOps](https://github.com/manasa-deshagouni/notifyops)
**Multi-tenant on-call and incident alerting SaaS**

A real-time alerting system that pages the right engineer fast and suppresses noisy duplicates.

**What it does**
- Deduplicates and correlates alerts in real time
- Uses idempotent workers and secure ingest with **JWT/HMAC**
- Provides a live **React + WebSocket** console for ack/resolve workflows
- Can run standalone or in front of a paging platform

**Highlights**
- **1.9s first-notify p95 @ 350 req/s**
- **58% duplicate suppression**
- **94% delivery success**
- **220 ms ack→resolve p95**

**Stack:** `Spring Boot` `Kafka` `Redis` `React` `PostgreSQL`

---

### 🎭 [TruthReaper](https://github.com/manasa-deshagouni/truthreaper)
**Multimodal voice-based behavioral classifier**

A cross-modal deception detection system that combines what is said with how it is said.

**What it does**
- Encodes temporal acoustic signals with **BiLSTM**
- Encodes text with **DistilBERT** plus linguistic features
- Uses **late fusion with XGBoost** for robust classification on short, noisy samples

**Highlights**
- **89.4% accuracy**
- **93.5% precision**
- Multimodal reasoning over **audio + text**

**Stack:** `PyTorch` `Hugging Face` `BiLSTM` `DistilBERT` `XGBoost`

---

<details>
<summary><b>More builds</b></summary>

### 🎮 [QuizChronicles](https://github.com/manasa-deshagouni/quizchronicles)
Interactive coding + quiz platform with sandboxed code execution, real-time rooms, leaderboards, WebSocket fan-out, and a game-style solo coding mode.

**Highlights**
- **180 ms submission p95 @ 200 users**
- **120 ms fan-out p95 @ 800 sockets**
- **< 0.5% dropped updates**

**Stack:** `Spring Boot` `React` `WebSockets` `Monaco` `k6`

</details>

---

## `work/production`

> [!NOTE]
> I can't open-source proprietary company code, but I can share the architectures, constraints, and measurable outcomes.

### ⚙️ Predictive Reliability Engine @ Optum
Built an end-to-end **stream → inference → action** pipeline on a secure file-transfer gateway.

**Architecture**
- **Kafka** ingestion for live operational telemetry
- **FastAPI + ONNX** for low-latency scoring
- **Spring Boot** mitigation gates for safe workflow actions
- Passive-to-active rollout with guarded remediation

**Impact**
- **~80% reduction** in severe backlog incidents
- **~70% reduction** in manual interventions
- **~85 ms p95** inference latency

---

### 🤖 GenAI Product Features @ Optum
Built two production AI features: a **configuration explainer** and a **log troubleshooting assistant**.

**What I built**
- Python services behind existing APIs
- A **RAG pipeline** over sanitized configs, runbooks, and log timelines
- **Structured output validation**, **fallback handling**, **caching**, and **read-only response policies**
- Fine-tuned **LLaMA-2** and **Mistral-7B** with **PEFT/LoRA**

**Impact**
- **MVP to production in 4 weeks**
- Reduced debugging friction for operators
- Shipped on a platform serving **5k+ users**

---

## `research/active`

### 🦠 Neural Fingerprints for Malware
**Graduate Research Assistant @ SJSU**

Learning domain-robust malware image embeddings on a hypersphere so unseen malware can be clustered and retrieved by similarity — without retraining.

**Current focus**
- Metric-learning objectives such as **ProxyAnchor**, **Triplet**, and **SupCon**
- Stable cross-domain retrieval under dataset shift
- **FAISS HNSW**-based open-set retrieval

**Key idea**
Strong in-domain separation does not guarantee cross-domain generalization. The real challenge is representation stability under shift.

---

### 🏃 Cross-Domain Human Activity Recognition
Built a zero-shot pocket HAR pipeline across heterogeneous smartphone sensors for **Sitting / Standing / Walking**.

**Highlights**
- **94.1% Macro-F1** on source domains
- **~95.9% Macro-F1** on zero-shot transfer
- Recovered **standing recall from ~0% to ~99%** by fixing preprocessing-distribution mismatch

---

## `papers/`

- 🏆 [**Brain Tumor Detection using Machine Learning**](https://journal.ipem.edu.in/computer_applications/wp-content/uploads/2024/02/paper-3.pdf) — **ICCDS 2024, Best Paper Award**
- [**Deep Learning Techniques for Detection of Deepfakes**](https://ijsrset.com/home/issue/view/article.php?id=IJSRSET2310102) — **IJSRSET, ICSCR 2023**

---

## `stack.yml`

```yaml
languages:
  - Python
  - Java
  - Go
  - C++
  - TypeScript
  - SQL

ml_ai:
  - PyTorch
  - TensorFlow
  - Transformers
  - ONNX Runtime
  - FAISS
  - PEFT / LoRA
  - LangChain

systems:
  - FastAPI
  - Spring Boot
  - Kafka
  - Redis
  - PostgreSQL
  - MongoDB
  - Docker
  - Kubernetes
  - GCP

frontend:
  - React
  - Angular
  - Tailwind
```

---

<p align="center">
  <i>"If it doesn't work in production, it doesn't work."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=100&section=footer" width="100%"/>
</p>
