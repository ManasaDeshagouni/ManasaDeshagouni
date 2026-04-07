<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=220&section=header&text=Manasa%20Deshagouni&fontSize=42&fontColor=58a6ff&fontAlignY=35&desc=Engineer%20who%20ships%20systems%20that%20think%20·%20Research%20that%20generalizes%20·%20Code%20that%20scales&descSize=14&descColor=8b949e&descAlignY=55&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/deshagounimanasa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://glittering-snickerdoodle-8c9296.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <a href="mailto:manasadprep@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://scholar.google.com"><img src="https://img.shields.io/badge/Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" /></a>
</p>

<br/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=750&height=80&lines=ML+that+auto-heals+production+systems+%E2%80%94+incidents+down+80%25;GenAI+features+serving+5k%2B+users+in+production;Zero-shot+retrieval+research+on+hyperspherical+embeddings" />
</p>

<br/>

## `$ whoami`

```python
class Manasa:
    role      = "M.S. Computer Science @ San José State University"
    prev      = "Software Engineer @ Optum (UnitedHealth Group)"
    research  = "Zero-shot malware attribution via neural fingerprint embeddings"
    ships     = ["production ML", "GenAI features", "backend systems at scale"]
    
    def philosophy(self):
        return "If it doesn't work in production, it doesn't work."
```

<br/>

---

<br/>

## 🏗️ What I Build

<table>
<tr>
<td align="center" width="33%">

### ⚡ Backend Systems
**20+ APIs & UIs shipped**<br/>
Spring Boot · React · Angular<br/>
Kafka · Redis · PostgreSQL<br/>
<br/>
<img src="https://img.shields.io/badge/dual--schema_rollout-0_breakages-2ea44f?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/misconfig_errors-↓31%25-2ea44f?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/MTTR-↓40%25-2ea44f?style=flat-square" />

</td>
<td align="center" width="33%">

### 🧠 Production ML & GenAI
**Stream → Infer → Act**<br/>
FastAPI · ONNX · Kafka · FAISS<br/>
LLaMA-2 · Mistral · RAG · PEFT<br/>
<br/>
<img src="https://img.shields.io/badge/p95_latency-85ms_@_1.2k_msg%2Fs-2ea44f?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/incidents-↓80%25-2ea44f?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/GenAI_MVP-4_weeks_→_prod-2ea44f?style=flat-square" />

</td>
<td align="center" width="33%">

### 🔬 Research
**Zero-shot · Metric Learning**<br/>
PyTorch · Embeddings · FAISS<br/>
ProxyAnchor · Hyperspheres<br/>
<br/>
<img src="https://img.shields.io/badge/cross--domain_retrieval-88.02%25-2ea44f?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/zero--shot_HAR-95.9%25_F1-2ea44f?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/Best_Paper-ICCDS_2024-FFD700?style=flat-square" />

</td>
</tr>
</table>

<br/>

---

<br/>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%">

### 🔔 [NotifyOps](https://github.com/manasa-deshagouni/notifyops)
**Multi-tenant On-call & Incident Alerting SaaS**

> *Pages the right engineer fast. Kills the noise.*

Real-time dedup + correlation engine with idempotent workers, JWT/HMAC-secured ingest, and a React WebSocket console for live ack/resolve. Runs standalone or as a pre-filter ahead of PagerDuty.

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" /> <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />

| Metric | Result |
|--------|--------|
| First-notify p95 | **1.9s @ 350 req/s** |
| Duplicate suppression | **58%** |
| Delivery success | **77% → 94%** |
| DLQ overflow | **< 0.6%** |
| Ack→resolve p95 | **220ms** |

</td>
<td width="50%">

### 🎮 [QuizChronicles](https://github.com/manasa-deshagouni/quizchronicles)
**Interactive Coding + Quiz Platform**

> *Compete. Code. Conquer.*

Modular Spring Boot backend with sandboxed code execution, React + Monaco editor, real-time rooms (10 players), leaderboards, proctor controls over WebSockets, and a timed game-themed solo coding mode.

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" /> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white" /> <img src="https://img.shields.io/badge/Monaco-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" /> <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" />

| Metric | Result |
|--------|--------|
| Submission p95 | **180ms @ 200 users** |
| Fan-out p95 | **120ms @ 800 sockets** |
| Dropped updates | **< 0.5%** |
| Cache speedup | **230 → 140ms (−39%)** |

</td>
</tr>
<tr>
<td width="50%">

### 🧠 [Digital Life Curator](https://github.com/manasa-deshagouni/digital-life-curator)
**Adaptive RAG-based Knowledge Agent**

> *Your second brain, with semantic superpowers.*

Local-first AI agent ingesting PDFs, notes, images, and code. Multimodal embeddings (MiniLM + CLIP), FAISS HNSW index, adaptive retrieval with temporal reranking, and a Streamlit interface for semantic search and Q&A.

<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" /> <img src="https://img.shields.io/badge/CLIP-412991?style=flat-square&logo=openai&logoColor=white" /> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />

| Metric | Result |
|--------|--------|
| Index scale | **100k+ documents** |
| Retrieval latency | **< 500ms** |
| Indexing | **HNSW (FAISS)** |
| Features | **Search · Q&A · Summarize** |

</td>
<td width="50%">

### 🎭 [TruthReaper](https://github.com/manasa-deshagouni/truthreaper)
**Multimodal Voice-Based Behavioral Classifier**

> *Your voice says more than your words.*

Cross-modal deception detection fusing temporal acoustic features (BiLSTM over speech) with text encoding (DistilBERT + linguistic cues). Late-fusion via XGBoost for robust classification on noisy, short-form audio.

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" /> <img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat-square" /> <img src="https://img.shields.io/badge/BiLSTM-FF6F00?style=flat-square" /> <img src="https://img.shields.io/badge/DistilBERT-412991?style=flat-square" />

| Metric | Result |
|--------|--------|
| Accuracy | **89.4%** |
| Precision | **93.5%** |
| Modalities | **Audio + Text** |
| Fusion | **Late (XGBoost)** |

</td>
</tr>
</table>

<br/>

---

<br/>

## 🏭 Production Systems I've Shipped

> *Can't open-source proprietary code — but here's what I built and what it did.*

<table>
<tr>
<td width="15%" align="center">
  <img src="https://img.shields.io/badge/Optum-00857C?style=for-the-badge&logoColor=white" />
</td>
<td>

**Predictive Reliability Engine** — End-to-end stream→inference→action pipeline on a secure file-transfer gateway (5k+ users). Kafka ingestion → FastAPI + ONNX scoring → Spring Boot mitigation gates. Passive→active rollout with 14-day canary, 0 false positives.

</td>
<td width="20%" align="center">
  <img src="https://img.shields.io/badge/incidents-↓80%25-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/p95-85ms-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/diagnosis-↓73%25-2ea44f?style=flat-square" />
</td>
</tr>
<tr>
<td width="15%" align="center">
  <img src="https://img.shields.io/badge/Optum-00857C?style=for-the-badge&logoColor=white" />
</td>
<td>

**GenAI Product Features** — Config explainer + log troubleshooter as Python microservices behind Spring Boot APIs. RAG pipeline with structured output validation, input redaction, tenant-scoped RBAC. Fine-tuned LLaMA-2 & Mistral-7B with PEFT/LoRA.

</td>
<td width="20%" align="center">
  <img src="https://img.shields.io/badge/MVP-4_weeks-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/prod-3_months-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/users-5k%2B-2ea44f?style=flat-square" />
</td>
</tr>
<tr>
<td width="15%" align="center">
  <img src="https://img.shields.io/badge/Optum-00857C?style=for-the-badge&logoColor=white" />
</td>
<td>

**ECG Platform Services** — 20+ React/Angular UIs + Spring Boot REST APIs for encrypted file routing. Dual-schema rollout (0 breakages), Kafka audit views, Java 8→17 modernization, correlation IDs, and guardrails that cut misconfig errors 31%.

</td>
<td width="20%" align="center">
  <img src="https://img.shields.io/badge/build_time-↓22%25-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/MTTR-↓40%25-2ea44f?style=flat-square" /><br/>
  <img src="https://img.shields.io/badge/onboarding-↓60%25-2ea44f?style=flat-square" />
</td>
</tr>
</table>

<br/>

---

<br/>

## 🔬 Active Research

<table>
<tr>
<td width="50%" valign="top">

### 🦠 Neural Fingerprints for Malware
**Graduate Research Assistant @ SJSU**

Learning domain-robust malware image embeddings on a hypersphere using metric-learning objectives (ProxyAnchor, Triplet, SupCon) so unseen malware can be clustered and retrieved by similarity — without retraining.

**Key insight:** Strong in-domain separation ≠ cross-domain generalization. The real bottleneck is representation stability under dataset shift, not loss function choice.

| | |
|---|---|
| Cross-domain retrieval | **88.02%** (MalNet→MalImg) |
| Zero-shot (17 unseen families) | **57–67%** |
| Retrieval engine | **FAISS HNSW** |
| Best loss | **ProxyAnchor** |

</td>
<td width="50%" valign="top">

### 🏃 Cross-Domain Human Activity Recognition
**Zero-shot Pocket HAR Pipeline**

Multi-source domain adaptation for Sitting/Standing/Walking across heterogeneous smartphone sensors. Physics-aware calibration that auto-detects sampling rate, units, and orientation of unseen devices.

**Key insight:** Standing recall collapsed from 99%→0% due to preprocessing-distribution mismatch — not model weakness. Fixing the pipeline fixed the model.

| | |
|---|---|
| Source-domain F1 | **94.1%** (subject-disjoint) |
| Zero-shot transfer | **~95.9%** (UTwente) |
| Standing recall recovery | **0% → ~99%** |
| Datasets | **4 train · 3 zero-shot** |

</td>
</tr>
</table>

<br/>

---

<br/>

## 📄 Publications

| Year | Paper | Venue |
|:----:|-------|-------|
| 🏆 2024 | [**Brain Tumor Detection using Machine Learning**](https://journal.ipem.edu.in/computer_applications/wp-content/uploads/2024/02/paper-3.pdf) | ICCDS 2024 · **Best Paper Award** |
| 2023 | [**Deep Learning Techniques for Detection of Deepfakes**](https://ijsrset.com/home/issue/view/article.php?id=IJSRSET2310102) | IJSRSET (ICSCR 2023) |

<br/>

---

<br/>

## 🛠️ Tech Stack

<p align="center">

**Languages**<br/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />

**Backend & Systems**<br/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=google&logoColor=white" />

**Frontend**<br/>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />

**ML & AI**<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" />
<img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />

**Cloud & DevOps**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />

</p>

<br/>

---

<br/>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=100&section=footer" width="100%"/>
</p>

<p align="center">
  <i>"If it doesn't work in production, it doesn't work."</i>
</p>
