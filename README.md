<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Ya%C4%9F%C4%B1z%20Akkaya&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Computer%20Engineering%20%C2%B7%20Applied%20AI%20%C2%B7%20Edge%20Vision&descAlignY=55&descSize=18" width="100%" />

<a href="https://github.com/yagizakkaya01">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=36BCF7&center=true&vCenter=true&width=650&lines=Computer+Vision+on+the+edge.;Retrieval-Augmented+Generation+in+production.;From+YOLO+on+a+Jetson+to+RAG+for+500%2B+users." alt="Typing SVG" />
</a>

<br/>

<a href="mailto:yagizakkaya10@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/yagizakkaya01"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/ya%C4%9F%C4%B1z-akkaya"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=yagizakkaya01&style=for-the-badge&color=36BCF7&label=PROFILE+VIEWS" />

</div>

<br/>

## 🧭 About Me

```yaml
name:      Yağız Akkaya
role:      Computer Engineering Student @ METU NCC
focus:     [ Computer Vision, Edge AI, Retrieval-Augmented Generation, High-Throughput Backends ]
```

I build systems that **see** and systems that **read** — computer vision models that run on constrained edge hardware, and retrieval pipelines that let people ask questions of documents they'd never have time to open.

Most of my work lives at the awkward, interesting seam between a model that works in a notebook and a system that survives real production environments: single-label datasets meeting multi-defect reality, detector jitter breaking naïve logic, GPU memory limits under concurrent ingestion, and high-throughput vector indexing.

<br/>

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog%20HDL-555555?style=flat-square&logo=microchip&logoColor=white)

**Computer Vision & Edge AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Ultralytics](https://img.shields.io/badge/YOLO11-0B0B0B?style=flat-square&logo=yolo&logoColor=00FFFF)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OAK-D](https://img.shields.io/badge/Luxonis%20OAK--D-FF6B00?style=flat-square&logo=raspberrypi&logoColor=white)

**LLM, Retrieval & Search**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC2626?style=flat-square&logo=qdrant&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00599C?style=flat-square&logo=meta&logoColor=white)
![Meilisearch](https://img.shields.io/badge/Meilisearch-FF4088?style=flat-square&logo=meilisearch&logoColor=white)
![BM25](https://img.shields.io/badge/BM25%20%2B%20RRF-8A2BE2?style=flat-square&logo=elasticsearch&logoColor=white)
![Rerankers](https://img.shields.io/badge/Qwen3--Reranker-FFB300?style=flat-square&logo=huggingface&logoColor=black)

**Backend, Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django%20ORM-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-22B573?style=flat-square&logo=caddy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

<br/>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 👁️ [inventory-verification](https://github.com/yagizakkaya01/inventory-verification)
**Fixed-camera object detection & state control**

A workspace inventory-verification system for defense-industry use cases such as ammunition tracking and assembly-line control, answering: *is the workspace in the valid state?*

- **Detection & Logic:** Fine-tuned a **YOLO11** model paired with a **finite state machine** and temporal smoothing to verify scene state while filtering out detector jitter
- **Bootstrapped Labeling:** Hand-labeled 50 of 452 frames, then trained a model to auto-label the rest, cutting labeling time significantly
- **Edge Deployment:** Deployed to **NVIDIA Jetson** with **TensorRT INT8** quantization for real-time edge inference using a **Luxonis OAK-D** camera

`Python` `YOLO11` `OpenCV` `TensorRT` `NVIDIA Jetson` `Luxonis OAK-D`

</td>
<td width="50%" valign="top">

### 🕌 [kervansaray](https://github.com/yagizakkaya01/kervansaray)
**Hotel parking ALPR & natural-language query system**

End-to-end data-management system for fixed-camera hotel parking entry/exit control, from synthetic data generation to natural-language querying.

- **Backend & Data Pipeline:** Engineered a Flask + PostgreSQL/pgvector backend (Docker, SQLAlchemy, Alembic) with a deterministic synthetic data generator, plate canonicalization, and fuzzy matching
- **LLM Query Layer:** Multi-provider fallback chain (Groq / Gemini / OpenAI) with tool calling for Turkish natural-language operational queries
- **Production Readiness:** Prometheus observability, structured logging, and an interactive public demo with cooldown-protected admin endpoints

`Python` `Flask` `PostgreSQL` `pgvector` `Docker` `Groq/Gemini/OpenAI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛰️ [uav-cuas-datasets](https://github.com/yagizakkaya01/uav-cuas-datasets)
**Spatial-semantic UAV/C-UAS threat mapping & C2 engine**

Evidence-based catalog and 5-layer architecture for a tactical decision-support system that maps drone threats in real-time and replans survivable paths.

- **Evidence-Based Grounding:** Curated catalog of **35+ real, independently verified data sources** (Copernicus DEM, OpenSky Network, DroneRF, ACLED, DoD/NATO doctrine)
- **5-Layer C2 Engine:** Geospatial & sensor ingestion, semantic threat knowledge base (doctrine/TTP RAG), grid/graph algorithms (A\*, terrain masking), radar/RF sensor fusion, and MIL-STD-2525 tactical symbology
- **Threat Surface & Route Replanning:** Mathematical models for multi-threat cost surfaces and dynamic route replanning under active drone threats

`Defense & C-UAS` `Path Planning` `Sensor Fusion` `MIL-STD-2525` `RAG`

</td>
<td width="50%" valign="top">

### 🍓 CILEKAI
**Enterprise RAG document assistant for 500+ employees**

Production-grade RAG system built during AI Engineering internship at Çilek Kids Room, enabling factory personnel to query technical docs, manuals, and spreadsheets with inline citations.

- **Multi-LLM Orchestration:** Integrated 5 LLM providers (Groq Llama 3.3, Google Gemini, GPT-4o, local Ollama) behind an automatic fallback chain for near-100% uptime
- **4-Stage Hybrid Search:** FAISS dense + BM25 keyword matching with RRF score merging, Qwen3-Reranker cross-encoder, and Turkish morphology (accuracy boosted from 0.15 to 0.95)
- **Dual Vector-Store & Caching:** Server-side Qdrant + in-process FAISS with incremental indexing; semantic caching achieved <10ms FAQ latency and reduced API costs by ~30%
- **Enterprise Security:** 5-layer Clean Architecture with department-based RBAC, Prometheus metrics, and Docker Compose deployment

`Python` `Docker Compose` `Qdrant` `FAISS` `Ollama` `Qwen3` `BM25`

</td>
</tr>
</table>

<details>
<summary><b>🎮 More projects & research — click to expand</b></summary>

<br/>

| Project | What it is | Stack |
|---|---|---|
| **Collapse/Blast Match-3 Engine** | High-performance Unity tile-matching engine featuring recursive Flood-Fill/BFS cluster detection ($O(M \times N)$), deterministic Smart Shuffle deadlock resolution, physics-based grid reflow, and object pooling | `Unity` `C#` `Algorithms` |
| **TEKNOFEST 2025 "CENGIZ"** | Unmanned coaxial helicopter designed for disaster-area connectivity and marine monitoring; led rotor configuration analysis and vehicle pre-sizing (**Ranked 5th in Türkiye**, 75.3 pts) | `Aerospace` `UAV Design` `Systems Engineering` |
| **TEKNOFEST 2024 Multipurpose Helicopter** | Modular helicopter design (SAR, Commercial, VIP variants) with a 6-person team (**Ranked 4th in Türkiye**, 78 pts) | `Aeronautics` `Modular Architecture` |
| **Yavuzkopter** | A GTA V mod featuring a custom unmanned coaxial helicopter, modelled entirely through Blender Python scripting with modular components and game-optimized export | `Blender` `Python` `3D Modeling` |
| [**circle-board-game**](https://github.com/yagizakkaya01/circle-board-game) | A 10×10 circular board game with traps and dice mechanics | `C` |
| [**crag-dice-game**](https://github.com/yagizakkaya01/crag-dice-game) | Implementation of the Crag dice game with full scoring logic | `C` |
| [**patient-management-system**](https://github.com/yagizakkaya01/patient-management-system) | Patient records with BMI classification and risk filtering | `C` |
| [**internship-records-system**](https://github.com/yagizakkaya01/internship-records-system) | Record management and analysis over internship datasets | `C` |

</details>

<br/>

## 💼 Experience

### 🏢 **Heysem AI** · *Computer Vision Intern*
`Sep 2026` · *On-site / Hybrid*

- **[Kervansaray](https://github.com/yagizakkaya01/kervansaray) — Hotel Parking License-Plate Recognition & Query System:** Built an end-to-end data-management system for fixed-camera hotel parking entry/exit control, from synthetic data generation to natural-language querying.
  - *Backend & Data Pipeline:* Engineered a Flask + PostgreSQL/pgvector backend (Docker, SQLAlchemy, Alembic) with a deterministic synthetic data generator, plate canonicalization, and fuzzy matching.
  - *LLM Query Layer:* Integrated a Groq/Gemini/OpenAI fallback chain with tool calling for Turkish natural-language queries.
  - *Production Readiness:* Added Prometheus observability, structured logging, and an interactive public demo with cooldown-protected admin endpoints.
- **[Inventory Verification](https://github.com/yagizakkaya01/inventory-verification) — Fixed-Camera Object Detection & State Control:** Developed a workspace inventory-verification system for defense-industry use cases such as ammunition tracking and assembly-line control.
  - *Detection & Logic:* Fine-tuned a YOLO11 model paired with a finite state machine to verify scene state while filtering out detector jitter.
  - *Data Labeling:* Hand-labeled 50 of 452 frames, then bootstrapped a model to auto-label the rest, cutting labeling time significantly.
  - *Edge Deployment:* Deployed to NVIDIA Jetson with TensorRT INT8 quantization for real-time inference using a Luxonis OAK-D camera.
- **Research & Web:** Prototyped a hybrid anomaly-detection pipeline (PatchCore + WinCLIP) for aircraft-part defect classification, and deployed a personal portfolio site ([yagizakkaya.com.tr](https://yagizakkaya.com.tr)) with Caddy reverse-proxy routing and visitor analytics.
- **Technologies:** `Python` `Flask` `PostgreSQL` `pgvector` `YOLO11` `OpenCV` `NVIDIA Jetson` `TensorRT` `Luxonis OAK-D` `Docker` `Groq` `Gemini` `OpenAI`

---

### ⚖️ **Hammurabi AI** · *Backend Engineer (Remote — Full-Time Student)*
`Apr 2026 – Jul 2026` · *Remote*

- **Vector Ingestion & Search Sync Pipeline:** Engineered a high-throughput legal document ingestion and indexing pipeline to synchronize millions of judicial decisions into Qdrant and Meilisearch databases.
- **Database-Driven Ingestion:** Engineered a concurrent search sync engine (`--from-db` mode) using PostgreSQL row-level locking (`select_for_update`) to support parallel worker execution without resource collision.
- **VRAM & Speed Optimization:** Developed a shared OOM-safe cascading encode algorithm (`full → half → quarter → one-by-one`) and single-document batching, reducing padding waste and increasing embedding speed by ~30%.
- **Fault-Tolerant Outage Recovery:** Built connection-outage resilience that automatically releases claimed documents back to `pending_sync` during target database failures and halts after 3 consecutive errors to prevent CPU spinning.
- **Process Lifecycle & OS Management:** Integrated process signal handlers (`SIGINT`/`SIGTERM`/`SIGBREAK`) and resolved a Windows-specific process zombie handle bug using `ctypes` for clean database lock releases on shutdown.
- **Live Observability:** Integrated Qdrant server `operation_id` tracking into Django WebSockets for real-time progress logging and dashboard pipeline statistics monitoring.
- **Technologies:** `Python` `Django ORM` `PostgreSQL` `Qdrant` `Meilisearch` `SentenceTransformers` `CUDA` `PyTorch` `WebSockets`

---

### 🍓 **Çilek Kids Room** · *AI Engineering Intern*
`Jan 2026 – Feb 2026` · *On-site*

- **CilekAI — Enterprise RAG Document Assistant:** Designed and built a production-grade RAG system enabling 500+ factory employees to query internal documents (PDF, Excel, images) with inline citations.
- **Multi-LLM Orchestration:** Integrated 5 LLM providers (Groq Llama 3.3, Google Gemini, GPT-4o, local Ollama) behind an automatic fallback chain to ensure near-100% service uptime.
- **Hybrid Retrieval & Reranking:** Engineered a 4-stage search system combining FAISS semantic search and BM25 keyword matching with RRF score merging, Qwen3-Reranker cross-encoder, and Turkish morphological normalization, boosting accuracy from 0.15 to 0.95.
- **Dual Vector-Store Architecture:** Deployed a hybrid vector database using server-side Qdrant and in-process FAISS, utilizing incremental indexing based on file modification times (`mtime`) and SHA-256 file deduplication.
- **Performance & Semantic Caching:** Achieved <10ms FAQ response times and reduced LLM API costs by ~30% by implementing a FAISS-backed semantic caching layer and Levenshtein-based fuzzy matching.
- **Enterprise Security & Architecture:** Designed a 5-layer Clean Architecture with department-based role-based access control (RBAC), Prometheus-based observability metrics, and Docker Compose multi-service deployment.
- **Technologies:** `Python` `Docker Compose` `Qdrant` `FAISS` `Ollama` `Qwen3` `BM25` `Levenshtein` `Prometheus` `Clean Architecture`

---

### 🎓 **Education**
**Middle East Technical University, NCC** — *Bachelor of Science in Computer Engineering*  
`2021 – Present`
- **Relevant Coursework:** Algorithm Analysis, Database Management and File Structures, C Programming, Data Structures, Python Programming, Linux Basics, Logic Design, Discrete Computational Structures.
- **Engineering Competitions:**
  - *TEKNOFEST 2025 Helicopter Design Competition:* Unmanned coaxial helicopter "CENGIZ" (Graded **75.3**, Ranked **5th place in Türkiye**).
  - *TEKNOFEST 2024 Helicopter Design Competition:* Modular multipurpose helicopter (Graded **78**, Ranked **4th place in Türkiye**).

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=yagizakkaya01&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&title_color=36BCF7&icon_color=36BCF7&text_color=c9d1d9&bg_color=0d1117" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yagizakkaya01&layout=compact&hide_border=true&title_color=36BCF7&text_color=c9d1d9&bg_color=0d1117" />

<img src="https://github-profile-trophy.vercel.app/?username=yagizakkaya01&theme=discord&no-frame=true&no-bg=true&row=1&column=6&margin-w=8" />

</div>

<br/>

## 🌱 Currently

- 🔬 Pushing edge inference further — **TensorRT INT8** quantization, measuring the accuracy/FPS curve honestly instead of quoting the best number
- 📚 Digging into **microservices design** and how retrieval systems should be decomposed
- 🧩 Turning repeated RAG plumbing into a reusable library instead of copy-pasting it into the next project
- 💬 Always up for talking about anomaly detection with almost no anomalies

<br/>

<div align="center">

### 📫 Let's talk

**[yagizakkaya10@gmail.com](mailto:yagizakkaya10@gmail.com)**

<br/>

*"Anyone can train a model. The engineering is everything that happens after."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" />

</div>
