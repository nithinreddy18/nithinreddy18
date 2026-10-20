<div align="center">

  <!-- Dynamic Cyberpunk HUD Banner -->
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0d1117,50:1f6feb,100:8957e5&height=210&section=header&text=NITHIN-2026.10-INSTRUCT&fontSize=42&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=Autonomous+Agentic+Workflows+%7C+3D+Spatial+Vision+%7C+Scalable+Data+Pipelines&descAlignY=68&descSize=16" width="100%" alt="Header Banner" />

  <!-- Hugging Face Style Model Card Metadata -->
  <p align="center">
    <a href="https://github.com/nithinreddy18"><img src="https://img.shields.io/badge/MODEL_ID-nithinreddy18%2Fai--engineer-1f6feb?style=flat-square&logo=huggingface&logoColor=white" alt="Model ID" /></a>
    <a href="https://www.tu-darmstadt.de/"><img src="https://img.shields.io/badge/BASE_ARCHITECTURE-M.Sc._AI_%26_ML_@_TU_Darmstadt-8957e5?style=flat-square&logo=academia&logoColor=white" alt="TU Darmstadt" /></a>
    <img src="https://img.shields.io/badge/PRECISION-PyTorch_%7C_C++_%7C_FastAPI-2ea043?style=flat-square&logo=pytorch&logoColor=white" alt="Precision" />
    <img src="https://img.shields.io/badge/NODE_LOCATION-Darmstadt,_Germany_🇩🇪-d29922?style=flat-square" alt="Location" />
    <img src="https://komarev.com/ghpvc/?username=nithinreddy18&label=TELEMETRY_HITS&color=0d1117&style=flat-square" alt="Profile Views" />
  </p>

  <!-- Interactive Console Navigation -->
  <p align="center">
    <kbd><a href="#01-objective-function">01 // Objective Function</a></kbd> ·
    <kbd><a href="#02-live-inference-trace">02 // Inference Trace</a></kbd> ·
    <kbd><a href="#03-capability-quadrant">03 // Skill Tensors</a></kbd> ·
    <kbd><a href="#04-verified-benchmarks">04 // Benchmarks</a></kbd> ·
    <kbd><a href="#05-execution-logs">05 // Field Logs</a></kbd> ·
    <kbd><a href="#06-training-schedule">06 // Epochs</a></kbd> ·
    <kbd><a href="#07-api-endpoints">07 // API Endpoints</a></kbd>
  </p>

</div>

---

<a id="01-objective-function"></a>
### `01 // EXECUTIVE ABSTRACT & OBJECTIVE FUNCTION`

I am **Malluri Nithin Reddy**, an Artificial Intelligence and Machine Learning graduate engineer at **Technische Universität Darmstadt**. Most machine learning prototypes stall inside Jupyter notebooks. I engineer the missing bridge between mathematical research and resilient production software. 

With an industrial foundation building enterprise C++ and C# systems at **Siemens** and high-volume Python and SQL data pipelines at **Increff**, I design multi-agent Large Language Model workflows, 3D spatial computer vision pipelines, and containerised microservices that hold up under real-world load.

#### **The Personal Mission Directive**
My engineering philosophy is governed by a single optimisation problem that minimises the gap between theoretical model capacity and deterministic production reliability:

$$\min_{\theta} \mathcal{L}_{\text{system}}(\theta) = \underbrace{\alpha \cdot \mathcal{D}_{\text{KL}}\left(P_{\text{research}} \parallel Q_{\text{production}}\right)}_{\text{Zero-Hallucination Grounding}} + \underbrace{\beta \cdot \mathbb{E}\left[\text{Latency}_{\text{P99}}\right]}_{\text{Sub-Second Inference}} - \underbrace{\gamma \cdot \mathcal{I}\left(\text{Neural\_State}; \text{Human\_Intent}\right)}_{\text{NeuroAI \& Interpretability}}$$

> [!IMPORTANT]
> **Core Engineering Mandate**
> To transform high-dimensional neural architectures and unstructured data streams into transparent, self-correcting, and production-grade software systems that solve physical and enterprise challenges.

---

<a id="02-live-inference-trace"></a>
### `02 // LIVE INFERENCE TRACE: HOW I ARCHITECT SYSTEMS`

Instead of building isolated scripts, I treat every project as an end-to-end distributed system. Below is the execution trace of how raw multimodal data flows through my typical production stack.

```mermaid
sequenceDiagram
    autonumber
    actor Client as Client / Sensor Stream
    participant Gateway as FastAPI / .NET Gateway
    participant Preproc as AST / OpenCV / LiDAR Parser
    participant Agent as LangGraph Orchestrator
    participant Vector as ChromaDB / SQL Engine
    participant Core as PyTorch / Llama 3.1 / RoBERTa

    Client->>Gateway: Stream Unstructured Payload (Code, 3D Point Cloud, Video, Text)
    Gateway->>Preproc: Normalise & Extract Deterministic Features
    Preproc->>Agent: Dispatch Structured State Graph
    par Semantic Context Retrieval
        Agent->>Vector: Hybrid Vector + Metadata Query
        Vector-->>Agent: Grounded Context Chunks
    and Neural Forward Pass
        Agent->>Core: Execute Tensor Inference (FP16 / Quantised)
        Core-->>Agent: Calibrated Logits & Representations
    end
    Agent->>Gateway: Validate Output Schema & Guardrails
    Gateway-->>Client: Return Dockerised Low-Latency Response
```

---

<a id="03-capability-quadrant"></a>
### `03 // SKILL TENSORS & CAPABILITY QUADRANT`

<table width="100%">
  <tr>
    <td width="48%" valign="middle">

```mermaid
quadrantChart
    title Engineering Capability Matrix
    x-axis "Systems & Infrastructure" --> "Neural & Mathematical Depth"
    y-axis "Foundational Tooling" --> "Production Mastery"
    quadrant-1 "Core AI Specialisation"
    quadrant-2 "Enterprise Systems & MLOps"
    quadrant-3 "Supporting Stack"
    quadrant-4 "Active Research Frontier"
    "PyTorch & Deep Learning": [0.85, 0.90]
    "LLMs, RAG & LangGraph": [0.78, 0.88]
    "OpenCV & 3D Vision": [0.72, 0.80]
    "FastAPI & Python": [0.30, 0.92]
    "SQL, Polars & ETL": [0.25, 0.84]
    "Docker & CI/CD": [0.20, 0.78]
    "C++, C# & .NET": [0.35, 0.72]
    "React & Angular": [0.18, 0.65]
    "NeuroAI & RSA": [0.90, 0.45]
    "PGMs & Statistical ML": [0.82, 0.60]
```

</td>
    <td width="52%" valign="top">
      <h4>⚙️ Explicit Tensor Specifications</h4>
      <p><b>🧠 Neural Architectures & GenAI</b><br>
      <code>PyTorch</code> <code>TensorFlow</code> <code>Keras</code> <code>Hugging Face</code> <code>LangChain</code> <code>LangGraph</code> <code>Llama 3.1</code> <code>RoBERTa</code> <code>LSTM</code> <code>Scikit-learn</code></p>
      <p><b>👁️ Spatial Vision & NeuroAI</b><br>
      <code>OpenCV</code> <code>MediaPipe</code> <code>3D LiDAR Point Clouds</code> <code>Net2Brain</code> <code>Representational Similarity Analysis</code></p>
      <p><b>⚡ High-Throughput Data & Backends</b><br>
      <code>Python</code> <code>C++</code> <code>C#</code> <code>FastAPI</code> <code>ASP.NET Core</code> <code>Polars</code> <code>Pandas</code> <code>NumPy</code> <code>SQL</code> <code>ChromaDB</code></p>
      <p><b>☁️ MLOps, Cloud & Interfaces</b><br>
      <code>Docker</code> <code>GitHub Actions</code> <code>Azure Data Factory</code> <code>Google Cloud</code> <code>React</code> <code>Angular</code> <code>Git</code></p>
    </td>
  </tr>
</table>

---

<a id="04-verified-benchmarks"></a>
### `04 // VERIFIED PRODUCTION BENCHMARKS (PROJECT SHOWCASE)`

Every repository is engineered to solve a concrete bottleneck. Click any **system inspection drawer** below to examine the underlying architecture.

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><code>SYS-01</code> 🚲 UniBike Fleet & Repair Analytics</h4>
      <p>
        <img src="https://img.shields.io/badge/Architecture-Agentic_RAG-8957e5?style=flat-square" />
        <img src="https://img.shields.io/badge/Stack-Llama_3.1_%7C_FastAPI_%7C_React-1f6feb?style=flat-square" />
      </p>
      <p><code>Pipeline:</code> <code>Telemetry → ChromaDB → Llama 3.1 → React UI</code></p>
      <p>Full-stack mobility intelligence platform featuring an autonomous RAG agent for automated bike repair diagnostics, fleet tracking, and predictive maintenance workflows.</p>
      <details>
        <summary><kbd>▶ Inspect System Architecture & Specs</kbd></summary>
        <br>
        <ul>
          <li><b>Vector Engine:</b> Indexed technical repair manuals and historical ticket logs in ChromaDB for grounded semantic retrieval.</li>
          <li><b>Backend & DevOps:</b> Asynchronous FastAPI microservices paired with automated GitHub Actions CI/CD pipelines.</li>
        </ul>
      </details>
      <p align="right"><a href="https://github.com/nithinreddy18?tab=repositories"><kbd>↗ Launch Repository</kbd></a></p>
    </td>
    <td width="50%" valign="top">
      <h4><code>SYS-02</code> 📄 AST-Driven AI Documentation Engine</h4>
      <p>
        <img src="https://img.shields.io/badge/Architecture-Compiler_AST_+_LLM-8957e5?style=flat-square" />
        <img src="https://img.shields.io/badge/Stack-Python_%7C_FastAPI_%7C_Docker-1f6feb?style=flat-square" />
      </p>
      <p><code>Pipeline:</code> <code>Source Code → AST Graph → LLM Synthesis → Markdown</code></p>
      <p>Automated developer tool that parses codebases into Abstract Syntax Trees to extract deterministic structural graphs before generating technical documentation.</p>
      <details>
        <summary><kbd>▶ Inspect System Architecture & Specs</kbd></summary>
        <br>
        <ul>
          <li><b>Zero-Hallucination Design:</b> Anchors LLM prompts strictly to extracted AST classes, call signatures, and dependency nodes.</li>
          <li><b>Deployment:</b> Fully containerised via Docker with REST endpoints for seamless CI integration.</li>
        </ul>
      </details>
      <p align="right"><a href="https://github.com/nithinreddy18?tab=repositories"><kbd>↗ Launch Repository</kbd></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><code>SYS-03</code> 🕵️‍♂️ RoBERTa Synthetic Content Detector</h4>
      <p>
        <img src="https://img.shields.io/badge/Validation_Accuracy-94.0%25-2ea043?style=flat-square" />
        <img src="https://img.shields.io/badge/Stack-PyTorch_%7C_Transformers-1f6feb?style=flat-square" />
      </p>
      <p><code>Confidence:</code> <code>███████████████████░ 94%</code></p>
      <p>Fine-tuned RoBERTa sequence classification pipeline engineered to detect subtle token-distribution anomalies and distinguish human prose from LLM-generated text.</p>
      <details>
        <summary><kbd>▶ Inspect System Architecture & Specs</kbd></summary>
        <br>
        <ul>
          <li><b>Training Strategy:</b> Fine-tuned attention layers using PyTorch, Hugging Face Transformers, and Scikit-learn evaluation harnesses.</li>
          <li><b>Robustness:</b> Mitigates perplexity-burstiness evasion across diverse domain corpora.</li>
        </ul>
      </details>
      <p align="right"><a href="https://github.com/nithinreddy18?tab=repositories"><kbd>↗ Launch Repository</kbd></a></p>
    </td>
    <td width="50%" valign="top">
      <h4><code>SYS-04</code> 📦 Hybrid Perishable Inventory Forecaster</h4>
      <p>
        <img src="https://img.shields.io/badge/Architecture-LSTM_+_Random_Forest-8957e5?style=flat-square" />
        <img src="https://img.shields.io/badge/Stack-PyTorch_%7C_Time_Series-1f6feb?style=flat-square" />
      </p>
      <p><code>Pipeline:</code> <code>Temporal Sequences → LSTM + RF Ensemble → Stock Quota</code></p>
      <p>Dual-stage predictive analytics system combining deep sequential modelling with ensemble tree architectures to optimise perishable supply-chain inventory and cut spoilage.</p>
      <details>
        <summary><kbd>▶ Inspect System Architecture & Specs</kbd></summary>
        <br>
        <ul>
          <li><b>Hybrid Modelling:</b> Uses PyTorch LSTMs to capture temporal decay trends while Random Forests handle exogenous tabular covariates.</li>
        </ul>
      </details>
      <p align="right"><a href="https://github.com/nithinreddy18?tab=repositories"><kbd>↗ Launch Repository</kbd></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><code>SYS-05</code> 🖐️ Touchless Gesture Media Controller</h4>
      <p>
        <img src="https://img.shields.io/badge/Recognition_Fidelity-92.0%25-2ea043?style=flat-square" />
        <img src="https://img.shields.io/badge/Stack-MediaPipe_%7C_OpenCV-1f6feb?style=flat-square" />
      </p>
      <p><code>Confidence:</code> <code>██████████████████░░ 92%</code></p>
      <p>Real-time spatial vision interface tracking 21 3D hand-knuckle coordinates to execute low-latency operating system media actions without physical contact.</p>
      <p align="right"><a href="https://github.com/nithinreddy18?tab=repositories"><kbd>↗ Launch Repository</kbd></a></p>
    </td>
    <td width="50%" valign="top">
      <h4><code>SYS-06</code> 😷 Real-Time Spatial Mask Compliance</h4>
      <p>
        <img src="https://img.shields.io/badge/Detection_Accuracy-95.0%25-2ea043?style=flat-square" />
        <img src="https://img.shields.io/badge/Stack-TensorFlow_%7C_Keras_%7C_OpenCV-1f6feb?style=flat-square" />
      </p>
      <p><code>Confidence:</code> <code>███████████████████░ 95%</code></p>
      <p>High-FPS convolutional vision system built for live video feeds, maintaining 95% classification accuracy across variable lighting and partial facial occlusion.</p>
      <p align="right"><a href="https://github.com/nithinreddy18?tab=repositories"><kbd>↗ Launch Repository</kbd></a></p>
    </td>
  </tr>
</table>

---

<a id="05-execution-logs"></a>
### `05 // FIELD DEPLOYMENTS & INDUSTRIAL EXECUTION LOGS`

```yaml
# VERIFIED RUNTIME LOGS // INDUSTRY, HACKATHONS & RESEARCH
deployments:
  - timestamp: "2026-09 -> PRESENT"
    domain: "NeuroAI & Computational Vision @ TU Darmstadt"
    focus: "Representational Similarity Analysis (RSA) & Net2Brain Toolbox"
    impact: "Comparing internal activations of deep computer vision models against human neural brain recordings."

  - timestamp: "2026-05"
    domain: "hessian.AI Waste-to-Energy Industry Challenge Hackathon"
    focus: "3D LiDAR Point-Cloud Deep Learning & Spatial Optimisation"
    impact: "Engineered AI models for automated 3D bunker fill-level estimation and waste-mix crane optimisation in a four-engineer squad."

  - timestamp: "2025-04 -> 2025-09"
    domain: "Software Developer Apprentice @ Siemens"
    focus: "Enterprise C++, C#, and Angular Systems"
    impact: "Built modular backend components and responsive industrial user interfaces inside production codebases."

  - timestamp: "2024-11 -> 2025-01"
    domain: "Data Engineer Intern @ Increff"
    focus: "High-Volume Python & SQL ETL Architecture"
    impact: "Designed fault-tolerant data pipelines processing large-scale retail and merchandising datasets."
```

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=nithinreddy18&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=8957e5" alt="GitHub Telemetry" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nithinreddy18&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff" alt="Language Distribution" />
</div>

---

<a id="06-training-schedule"></a>
### `06 // MODEL TRAINING EPOCHS: LEARNING GOALS & ROADMAP`

| Epoch | Execution Window | Target Subsystem | Convergence Criteria & Deliverables | Status |
| :--- | :--- | :--- | :--- | :---: |
| **`EPOCH 01`** | `Completed` | **Enterprise & Data Foundations** | Ship production C++/C# modules at Siemens, scale SQL/Python ETL at Increff, and complete B.Tech in AI & ML. | `🟢 CONVERGED` |
| **`EPOCH 02`** | `Completed` | **Applied GenAI & 3D Vision** | Deploy Llama 3.1 RAG systems, AST documentation engines, and 3D LiDAR point-cloud models at hessian.AI; complete graduate exams in PGMs, NLP, and Vision at TU Darmstadt. | `🟢 CONVERGED` |
| **`EPOCH 03`** | `Q4 2026` | **Stateful Agents & NeuroAI** | Master cyclical multi-agent orchestration in LangGraph, quantised LLM serving (`vLLM`, `AWQ`, `GGUF`), and benchmark brain-aligned vision models via `Net2Brain`. | `🔵 IN TRAINING` |
| **`EPOCH 04`** | `2027 Horizon` | **Distributed MLOps & Open Weights** | Scale multi-GPU distributed training pipelines, publish open-source evaluation benchmarks, and architect autonomous industrial AI systems in Germany. | `⚪ SCHEDULED` |

---

<a id="07-api-endpoints"></a>
### `07 // API ENDPOINTS & COLLABORATION PROTOCOL`

You can initiate a connection with my node using the following endpoints. I am actively open to **Working Student and Internship opportunities in Germany**, **AI/ML research collaborations**, and **open-source engineering**.

```http
POST /v1/collaborate/message HTTP/2
Host: [github.com/nithinreddy18](https://github.com/nithinreddy18)
Content-Type: application/json

{
  "target": "Malluri Nithin Reddy",
  "location": "Darmstadt / Frankfurt Rhine-Main Area, Germany",
  "available_for": ["Working Student (AI/ML/Data)", "Research Assistantships", "Open-Source PRs"],
  "languages": ["English (C1)", "German (B1 Coursework)", "Telugu (Native)"]
}
```

<div align="center">

  <a href="https://www.linkedin.com/in/nithin-reddy-malluri-54198b272/">
    <img src="https://img.shields.io/badge/POST_%2Fv1%2Flinkedin-Connect_With_Nithin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Endpoint" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/nithinreddy18?tab=repositories">
    <img src="https://img.shields.io/badge/GET_%2Fv1%2Frepositories-Inspect_Source_Code-2ea043?style=for-the-badge&logo=github&logoColor=white" alt="Repositories Endpoint" />
  </a>

  <br><br>
  <sub><code>STATUS 200 OK</code> · Engineered with deterministic precision by <b>Malluri Nithin Reddy</b></sub>

</div>
