<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Ya%C4%9F%C4%B1z%20Akkaya&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Computer%20Engineering%20%C2%B7%20Applied%20AI%20%C2%B7%20Edge%20Vision&descAlignY=55&descSize=18" width="100%" />

<a href="https://github.com/yagizakkaya01">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=36BCF7&center=true&vCenter=true&width=650&lines=Computer+Vision+on+the+edge.;Retrieval-Augmented+Generation+in+production.;From+YOLO+on+a+Jetson+to+RAG+for+500%2B+users." alt="Typing SVG" />
</a>

<br/>

<a href="mailto:yagizakkaya10@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/yagizakkaya01"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/yagizakkaya"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=yagizakkaya01&style=for-the-badge&color=36BCF7&label=PROFILE+VIEWS" />

</div>

<br/>

## 🧭 About Me

```yaml
name:      Yağız Akkaya
role:      Computer Engineering Student @ METU 
focus:     [ Computer Vision, Edge AI, Retrieval-Augmented Generation ]
```

I build systems that **see** and systems that **read** — computer vision models that run on constrained edge hardware, and retrieval pipelines that let people ask questions of documents they'd never have time to open.

Most of my work lives at the awkward, interesting seam between a model that works in a notebook and a system that survives a factory floor: single-label datasets meeting multi-defect reality, detector jitter breaking naïve logic, GPUs that don't exist in the budget.

<br/>

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Computer Vision & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Ultralytics](https://img.shields.io/badge/YOLO11-0B0B0B?style=flat-square&logo=yolo&logoColor=00FFFF)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Jetson](https://img.shields.io/badge/Jetson%20Edge-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OAK-D](https://img.shields.io/badge/Luxonis%20OAK--D-FF6B00?style=flat-square&logo=raspberrypi&logoColor=white)

**LLM & Retrieval**

![LangChain](https://img.shields.io/badge/RAG%20Pipelines-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Vector DB](https://img.shields.io/badge/Vector%20Stores-FF4088?style=flat-square&logo=databricks&logoColor=white)
![BM25](https://img.shields.io/badge/BM25%20%2B%20RRF-8A2BE2?style=flat-square&logo=elasticsearch&logoColor=white)
![Rerankers](https://img.shields.io/badge/Cross--Encoder%20Rerank-FFB300?style=flat-square&logo=huggingface&logoColor=black)

**Platform & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Blender](https://img.shields.io/badge/Blender%20Python-E87D0D?style=flat-square&logo=blender&logoColor=white)

</div>

<br/>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 👁️ [inventory-verification](https://github.com/yagizakkaya01/inventory-verification)
**Edge AI state verification**

A fixed-camera system that answers one deceptively hard question: *is the workspace in the state it should be in?* Right objects, right count, right order.

- Fine-tuned **YOLO11** detector
- **Finite state machine** + temporal smoothing so a passing hand or a single dropped frame never flips the verdict
- Bootstrapped labeling: hand-labeled **50 of 452** images, trained a throwaway model to auto-label the rest, then corrected — a fraction of the annotation hours
- Prototyped on a **Luxonis OAK-D**, headed for **Jetson + TensorRT INT8**

`Python` `YOLO11` `OpenCV` `State Machines`

</td>
<td width="50%" valign="top">

### 🕌 Kervansaray
**ALPR → Cloud → LLM query layer** · *in progress*

Named after the roadside inns where the arrivals and departures of travellers were once written down by hand. This one does it with a camera.

- **Jetson** at the edge reads plates, emits structured JSON events
- Cloud event store feeds a **RAG layer** that answers natural-language questions: *"which plates entered after 22:00 last night?"*
- Active push notifications to the operations desk
- Built on a shared library extracted from earlier RAG work rather than a fork

`Jetson` `ALPR` `RAG` `Event-Driven`

</td>
</tr>
<tr>
<td width="50%" valign="top">



</td>
<td width="50%" valign="top">

###  CILEKAI
**Enterprise RAG for 500+ factory employees**

Built during an AI Engineering internship at Çilek Kids Room: a production document assistant that let the whole plant query internal documentation in plain Turkish.

- Hybrid retrieval — **BM25 + dense + RRF fusion**, cross-encoder reranking
- Turkish text normalization & fuzzy matching
- LLM client with a provider **fallback chain**, observability, RBAC
- **Docker Compose** deployment

`RAG` `FastAPI` `Docker` `Production`

</td>
</tr>
</table>

<details>
<summary><b>🎮 More projects — click to expand</b></summary>

<br/>

| Project | What it is | Stack |
|---|---|---|
| **Yavuzkopter** | A GTA V mod featuring a custom unmanned **coaxial helicopter**, modelled entirely through Blender Python scripting with modular components and game-optimized export | `Blender` `Python` `3D` |
| [**circle-board-game**](https://github.com/yagizakkaya01/circle-board-game) | A 10×10 circular board game with traps and dice mechanics | `C` |
| [**crag-dice-game**](https://github.com/yagizakkaya01/crag-dice-game) | Implementation of the Crag dice game with full scoring logic | `C` |
| [**patient-management-system**](https://github.com/yagizakkaya01/patient-management-system) | Patient records with BMI classification and risk filtering | `C` |
| [**internship-records-system**](https://github.com/yagizakkaya01/internship-records-system) | Record management and analysis over internship datasets | `C` |

</details>

<br/>

## 💼 Experience

```
2026 — present   AI / Computer Vision Intern  ·  Heysem AI
                 Industrial defect detection & edge-deployed inventory
                 verification. Long-tail, few-shot defect classes;
                 single-label data vs. multi-defect production reality.

2026 (Apr-Jul)   ⚖️ Hammurabi
                  **RAG legal assistant for Turkish law**
                  REngineered a high-throughput legal document ingestion pipeline, synchronizing millions of judicial decisions into Qdrant and Meilisearch.

Developed a concurrent search sync engine using PostgreSQL row-level locking for collision-free parallel worker execution.

Boosted embedding speeds by ~30% and optimized VRAM usage by designing a shared OOM-safe cascading encode algorithm (full → half → quarter → one-by-one)

Implemented fault-tolerant recovery mechanisms to prevent CPU spinning and manage document queues during target database outages.
Integrated live pipeline observability via Django WebSockets for real-time operation_id tracking.

Stack: Python, Django ORM, PostgreSQL, Qdrant, Meilisearch, SentenceTransformers, CUDA, PyTorch.

2026 (Jan–Feb)   AI Engineering Intern  ·  Çilek Kids Room
                 Built CILEKAI — a production RAG assistant serving
                 500+ factory employees over internal documentation.

ongoing          B.Sc. Computer Engineering
                 Middle East Technical University, Northern Cyprus Campus
```

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
