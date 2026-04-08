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

I'm **Manasa**, a Master's student in **Computer Science at San José State University** and a **Graduate Research Assistant** working on **zero-shot malware attribution** with metric-learned embeddings.

Previously, I spent 2+ years at **Optum (UnitedHealth Group)** shipping **production ML**, **GenAI features**, and **backend systems** for a secure file-transfer platform.

I care about the part of ML that actually gets used: **retrieval**, **inference**, **guardrails**, **evaluation**, **rollout safety**, and the systems that turn predictions into action.

- 🔬 **Currently researching:** zero-shot retrieval, metric learning, FAISS-based search
- 🧠 **Interested in:** production ML, GenAI/RAG, embeddings, backend systems
- 🤝 **Open to:** SWE, MLE, Applied ML, and Research Engineer roles

---

## `projects/featured`

<table>
<tr><td>

### 🧠 [Digital Life Curator](https://github.com/manasa-deshagouni/digital-life-curator)

```
  ╭──────────────────────────────────────────╮
  │  🔍  "What was that paper about          │
  │       attention mechanisms I read         │
  │       last month?"                        │
  │                                           │
  │  Found 3 results in 47ms                  │
  │  ├── 📄 attention_is_all_you_need.pdf     │
  │  │   ✦ 0.94 relevance · chunk 3/12       │
  │  ├── 📝 transformer_notes.md              │
  │  │   ✦ 0.89 relevance · tagged: #nlp     │
  │  └── 🖼️ architecture_diagram.png          │
  │      ✦ 0.81 relevance · CLIP matched     │
  ╰──────────────────────────────────────────╯
```

**Your second brain, with semantic superpowers.**

A local-first AI agent that ingests everything — PDFs, notes, receipts, images, code snippets — and makes it all searchable by *meaning*, not keywords. Multimodal embeddings (**MiniLM** for text, **CLIP** for images), **FAISS HNSW** index, adaptive retrieval with temporal reranking.

| What it handles | How it performs |
|:---|:---|
| **100k+ documents** indexed | **< 500ms** retrieval |
| 5 features: search, Q&A, summarize, rank, discover | Metadata filtering + temporal reranking |

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" /> <img src="https://img.shields.io/badge/CLIP-412991?style=flat-square&logo=openai&logoColor=white" /> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" /> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />

</td></tr>
</table>

---

<table>
<tr><td>

### 🔔 [NotifyOps](https://github.com/manasa-deshagouni/notifyops)

```
  03:14:22 ⚠  ALERT  disk_full on prod-db-03
  03:14:22 ⚠  ALERT  disk_full on prod-db-03   ← duplicate, suppressed
  03:14:23 ⚠  ALERT  disk_full on prod-db-03   ← duplicate, suppressed
  03:14:24 🔔 PAGED  @sarah (on-call: infra)    ← 1.9s from first alert
  03:14:26 ✅ ACK    @sarah acknowledged         ← 220ms ack→resolve
  
  ┌─────────────────────────────┐
  │ 3 alerts → 1 page → 1 ack  │
  │ 58% noise eliminated       │
  └─────────────────────────────┘
```

**Pages the right engineer. Kills the noise.**

Multi-tenant on-call alerting SaaS with real-time dedup, correlation, and idempotent workers. JWT/HMAC-secured ingest. React + WebSocket console for live ack/resolve. Runs standalone or as a pre-filter ahead of PagerDuty/Opsgenie.

| Metric | Result |
|:---|:---|
| First-notify p95 | **1.9s @ 350 req/s** |
| Duplicate suppression | **58%** |
| Delivery success | **77% → 94%** (retries + backoff + DLQ < 0.6%) |
| Ack→resolve p95 | **220ms** |

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" /> <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />

</td></tr>
</table>

---

<table>
<tr><td>

### 🎭 [TruthReaper](https://github.com/manasa-deshagouni/truthreaper)

```
          AUDIO                          TEXT
            │                              │
   ┌────────▼────────┐          ┌──────────▼──────────┐
   │  Acoustic feats  │          │  DistilBERT + cues  │
   │  → BiLSTM        │          │  → text embedding    │
   └────────┬────────┘          └──────────┬──────────┘
            │         confidence            │
            └──────────┐  ┌────────────────┘
                    ┌──▼──▼──┐
                    │ XGBoost │  ← late fusion
                    │  Fuser  │
                    └────┬───┘
                         │
                    ┌────▼────┐
                    │ TRUTH or │
                    │ DECEPTION│
                    └─────────┘
                    
   accuracy: 89.4%  ·  precision: 93.5%
```

**Your voice says more than your words.**

Multimodal deception detection that fuses *what you say* with *how you say it*. Temporal acoustic features encoded via BiLSTM, transcript text encoded via DistilBERT with explicit lexical/linguistic cues, late-fused through XGBoost for robust classification on short, noisy clips.

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" /> <img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat-square" /> <img src="https://img.shields.io/badge/BiLSTM-FF6F00?style=flat-square" /> <img src="https://img.shields.io/badge/DistilBERT-412991?style=flat-square" />

</td></tr>
</table>

---

<details>
<summary><b>🎮 More builds → QuizChronicles</b></summary>

### [QuizChronicles](https://github.com/manasa-deshagouni/quizchronicles)

```
  ┌─ ROOM: "algo-arena" ──────── 4/10 players ─┐
  │                                              │
  │  🟢 alice    142 pts   solving Q3...         │
  │  🟢 bob      138 pts   submitted ✓  180ms   │
  │  🟡 charlie  120 pts   idle                  │
  │  🟢 you      155 pts   🏆 leading            │
  │                                              │
  │  ⏱️ 02:34 remaining                          │
  │  fan-out: 120ms p95 across 800 sockets       │
  └──────────────────────────────────────────────┘
```

Interactive coding + quiz platform with modular Spring Boot backend, sandboxed code execution, React + Monaco editor, real-time rooms, leaderboards, proctor controls over WebSockets, and a timed game-themed solo coding mode.

| Metric | Result |
|:---|:---|
| Submission p95 | **180ms @ 200 users** |
| Fan-out p95 | **120ms @ 800 sockets** |
| Dropped updates | **< 0.5%** |
| Cache speedup | **230 → 140ms (−39%)** |

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" /> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white" /> <img src="https://img.shields.io/badge/Monaco-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" /> <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" />

</details>

---

## `work/production`

> [!NOTE]
> Can't open-source proprietary code — but here's what I built and what it did.

<table>
<tr>
<td width="4%" align="center">⚡</td>
<td><b>Predictive Reliability Engine</b></td>
<td width="38%">

```
Kafka → FastAPI+ONNX → Spring Boot gates
     scoring: p95 85ms @ 1.2k msgs/s

shadow mode → canary (14d, 0 FP) → prod
```

</td>
<td align="right">
  <img src="https://img.shields.io/badge/incidents-↓80%25-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/manual_work-↓70%25-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/diagnosis-↓73%25-2ea44f?style=flat-square" />
</td>
</tr>
<tr>
<td align="center">🤖</td>
<td><b>GenAI Product Features</b></td>
<td>

```
config/logs → sanitize → RAG retrieve
  → LLM (LLaMA-2 / Mistral-7B + LoRA)
  → validate schema → serve
```

</td>
<td align="right">
  <img src="https://img.shields.io/badge/MVP-4_weeks-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/prod-3_months-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/users-5k%2B-2ea44f?style=flat-square" />
</td>
</tr>
<tr>
<td align="center">🔧</td>
<td><b>ECG Platform Services</b></td>
<td>

```
20+ UIs + Spring Boot APIs
dual-schema rollout → 0 breakages
correlation IDs: UI→API→workers
```

</td>
<td align="right">
  <img src="https://img.shields.io/badge/build_time-↓22%25-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/MTTR-↓40%25-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/misconfigs-↓31%25-2ea44f?style=flat-square" />
</td>
</tr>
</table>

---

## `research/active`

<table>
<tr>
<td width="50%" valign="top">

### 🦠 Neural Fingerprints for Malware
**Graduate Research Assistant @ SJSU**

```
malware binary → image → ResNet encoder
  → L2 normalize → hypersphere embedding
  → FAISS HNSW → nearest family match

  train: 47 families (MalNet + MalImg)
  test:  17 unseen families (zero-shot)
```

Learning domain-robust embeddings with **ProxyAnchor**, **Triplet**, and **SupCon** losses so unseen malware can be clustered and retrieved — without retraining.

**Key insight:** Strong in-domain separation ≠ cross-domain generalization. The bottleneck is representation stability under dataset shift, not loss function choice.

| | |
|:---|:---|
| Cross-domain retrieval | **88.02%** (MalNet→MalImg) |
| Strict zero-shot | **57–67%** (17 unseen families) |
| Best loss | ProxyAnchor |

</td>
<td width="50%" valign="top">

### 🏃 Cross-Domain HAR
**Zero-shot Pocket Activity Recognition**

```
4 source datasets (heterogeneous phones)
  → unified calibration pipeline
  → physics-aware temporal model
  → 3 zero-shot target datasets

  standing recall: 0% ──fix pipeline──→ ~99%
```

Multi-source domain adaptation for **Sitting / Standing / Walking**. Physics-aware calibrator auto-detects sampling rate, units, and orientation of unseen sensors.

**Key insight:** Standing recall collapsed to ~0% from preprocessing-distribution mismatch — not model weakness. Fixing the pipeline fixed the model.

| | |
|:---|:---|
| Source-domain F1 | **94.1%** (subject-disjoint) |
| Zero-shot transfer | **~95.9%** (UTwente) |
| Standing recovery | **0% → ~99%** |

</td>
</tr>
</table>

---

## `papers/`

| Year | Paper | Venue |
|:----:|-------|-------|
| 🏆 2024 | [**Brain Tumor Detection using Machine Learning**](https://journal.ipem.edu.in/computer_applications/wp-content/uploads/2024/02/paper-3.pdf) | ICCDS 2024 · **Best Paper Award** |
| 2023 | [**Deep Learning Techniques for Detection of Deepfakes**](https://ijsrset.com/home/issue/view/article.php?id=IJSRSET2310102) | IJSRSET (ICSCR 2023) |

---

## `stack.yml`

```yaml
languages:
  - Java
  - Python
  - Go
  - C++
  - TypeScript
  - SQL

ml_and_ai:
  - PyTorch
  - TensorFlow
  - Transformers
  - ONNX Runtime
  - FAISS
  - PEFT / LoRA
  - LangChain
  - scikit-learn
  - XGBoost

backend_and_systems:
  - Spring Boot
  - Spring Security
  - FastAPI
  - Kafka
  - Redis
  - PostgreSQL
  - MongoDB
  - Docker
  - Kubernetes
  - GCP
  - AWS

frontend:
  - React
  - Angular
  - Tailwind
  - Vite

observability:
  - Grafana
  - Prometheus
  - Selenium / Cucumber
  - JUnit
  - k6
```

---

<p align="center">
  <i>"Research matters. Production proves it."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=100&section=footer" width="100%"/>
</p>
