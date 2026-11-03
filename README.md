<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,6,11,20&height=180&section=header&text=Hi%20%F0%9F%91%8B,%20I'm%20Anmol%20Rajpoot&fontSize=42&fontAlignY=38&animation=twinkling&desc=AI%20Engineer%20%E2%80%A2%20LLM%20Systems%20%7C%20AI%20Agents%20%7C%20RAG%20%7C%20Full-Stack%20AI&descAlignY=62&descSize=18" width="100%" />
</div>

<p align="center">
  <a href="https://readme-typing-svg.herokuapp.com">
    <img src="https://readme-typing-svg.herokuapp.com?size=24&duration=2800&color=00F7FF&center=true&vCenter=true&width=780&lines=AI+Engineer+%7C+LLMs+%26+Multi-Agent+Systems;Fine-Tuning+%E2%80%A2+RAG+%E2%80%A2+MCP+%E2%80%A2+System+Design;Building+End-to-End+Real-World+AI+Architectures;LeetCode+Knight+(Top+5%25+%7C+650%2B+Solved)+%F0%9F%8F%86;I+don't+just+prompt+models+%E2%80%94+I+build+systems.+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://drive.google.com/file/d/1b8CqxKuY6dxMMgAcDl0wRsYY87IyRSiJ/view?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/Resume-Google_Drive-34A853?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume" />
  </a>
  <a href="https://linkedin.com/in/anmol-rajpoot-b5b770290" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://leetcode.com/u/Anmol_1707/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" />
  </a>
  <a href="mailto:rajpootanmol779@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://x.com/Anmolrajpoot25" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
</p>

<br>

<div align="center">
  <table>
    <tr>
      <td align="center">🎓 <b>Education</b><br>B.Tech in CSE (Batch 2027)<br><b>IIIT Bhopal</b></td>
      <td align="center">⚡ <b>Core Focus</b><br>Agent Orchestration, RAG<br><b>LLM Fine-Tuning & SFT</b></td>
      <td align="center">🏆 <b>DSA Milestone</b><br><b>LeetCode Knight</b><br>650+ Problems Solved</td>
      <td align="center">💼 <b>Experience</b><br>AI Intern @ <b>Solvor</b><br>Research @ <b>IIIT Bhopal</b></td>
    </tr>
  </table>
</div>

---

### 💡 Core Philosophy

> *"I don't just prompt models — I architect intelligent, reliable, and evaluatable production systems."*

- 🤖 **Agentic & Foundation Systems:** Hands-on experience developing autonomous multi-agent workflows, Model Context Protocol (MCP) servers, and training custom causal GPT architectures from scratch in PyTorch.
- 🔬 **Evaluations & Alignment:** Fine-tuned `Qwen2.5-7B` with LoRA across 25K+ preference pairs, implementing swap-augmentation pipelines to achieve position-bias invariance and 91% benchmark accuracy.
- 🏗️ **Production-Grade Engineering:** Microservices built with FastAPI, OAuth 2.0 (3LO), Fernet symmetric encryption, Neon PostgreSQL, Docker, and Qdrant/FAISS vector databases.

---

## 🚀 <span style="color:#00F7FF">Engineering Arsenal & Flagship Systems</span>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=100&section=header&text=Architectural%20Blueprints%20%26%20Deep%20Dives&fontSize=24&fontAlignY=45&animation=twinkling" width="100%" />
</div>

<div align="center">
<details open>
<summary style="cursor: pointer; font-size: 1.15em;">
  <b>🔥 CLICK TO EXPAND / COLLAPSE SYSTEM ARCHITECTURES</b>
</summary>

<br>

<div align="left">

### 1️⃣ [LLM as Judge Platform](https://github.com/AnmolRajpoot25/LLM_as_Judge)
> **Fine-tuned LLM evaluation platform with pairwise judging, position-bias elimination, and structured telemetry.**
- **Tech Stack:** `PyTorch 2.x` • `Qwen 2.5-7B` • `PEFT / LoRA (r=16, α=32)` • `FastAPI` • `React 18` • `TypeScript`
- **Key Milestones:** **91% accuracy** on a 100-case hard benchmark; swap-augmentation training eliminates order bias; guarantees 100% valid JSON schema output.

```mermaid
flowchart LR
    subgraph Input["Pairwise Input"]
        A["Prompt + Responses (A, B)"] --> B["Swap Augmentation Engine (B, A)"]
    end

    subgraph FineTunedModel["Fine-Tuned Evaluator"]
        B --> C["Qwen 2.5-7B (LoRA Adapter)"]
        C --> D["Multi-Dimensional Rubric Evaluator"]
    end

    subgraph Decision["Inference & Telemetry"]
        D --> E{"Position Invariance Check"}
        E -->|Consistent| F["Structured JSON Telemetry"]
        E -->|Bias Detected| G["Flagged Calibration Loop"]
    end

    style Input fill:#0d1117,stroke:#00F7FF,stroke-width:2px,color:#fff
    style FineTunedModel fill:#0d1117,stroke:#FFD700,stroke-width:2px,color:#fff
    style Decision fill:#0d1117,stroke:#00FFB3,stroke-width:2px,color:#fff
```

---

### 2️⃣ [Zira Automation Agent](https://github.com/AnmolRajpoot25/Zira_automation_Agent) • [🌐 Live Demo](https://zira-automation-agent.onrender.com/)
> **Autonomous Jira agent executing complex issue lifecycles via authenticated Model Context Protocol (MCP) tool calls.**
- **Tech Stack:** `Gemini 2.5 Flash` • `FastAPI (Asyncio)` • `Model Context Protocol (MCP)` • `OAuth 2.0 (3LO)` • `Neon PostgreSQL` • `Cloudflare Workers` • `Fernet-256`
- **Key Milestones:** Authenticated 4+ step issue workflows; encrypted token storage; 9+ typed MCP Jira tools.

```mermaid
flowchart LR
    subgraph Client["User Interface"]
        U["Natural Language Request"] --> UI["Web Terminal Interface"]
        UI --> AG["FastAPI Gateway"]
    end

    subgraph Reasoning["Agentic Orchestration"]
        AG --> CF["Cloudflare Proxy"]
        CF --> GEM["Gemini 2.5 Flash (Function Calling)"]
        GEM --> MCP["MCP Server (9+ Typed Tools)"]
    end

    subgraph Integration["Secure Execution"]
        MCP --> OAUTH["OAuth 2.0 (3LO) + Fernet Token"]
        OAUTH --> JIRA[("Jira Cloud REST API v3")]
        AG --> NEON[("Neon PostgreSQL (Chat History)")]
    end

    style Client fill:#0d1117,stroke:#00F7FF,stroke-width:2px,color:#fff
    style Reasoning fill:#0d1117,stroke:#8B5CF6,stroke-width:2px,color:#fff
    style Integration fill:#0d1117,stroke:#00FFB3,stroke-width:2px,color:#fff
```

---

### 3️⃣ [GPT-Style LLM from Scratch](https://github.com/AnmolRajpoot25/AI_personal_assistant_LLM_from_scratch)
> **PyTorch implementation of a generative causal language model from byte-pair tokenization to FastAPI serving.**
- **Tech Stack:** `PyTorch 2.x` • `Causal Decoder Blocks` • `Masked Multi-Head Attention` • `BPE (50k Vocab)` • `LayerNorm & GELU` • `FastAPI`
- **Key Milestones:** Implemented token & position embeddings, residual connections, causal masking, pretraining loop, instruction fine-tuning, and top-k/top-p nucleus sampling.

```mermaid
flowchart LR
    A["Raw Text Corpus"] --> B["BPE Tokenizer (50K Vocab)"]
    B --> C["Token + Positional Embeddings"]
    C --> D["Masked Multi-Head Attention Blocks"]
    D --> E["Feed-Forward Networks (GELU + LayerNorm)"]
    E --> F["Pretraining & SFT Loop"]
    F --> G["FastAPI Top-K / Top-P Sampling Engine"]

    style A fill:#0d1117,stroke:#00F7FF,stroke-width:2px,color:#fff
    style D fill:#0d1117,stroke:#FFD700,stroke-width:2px,color:#fff
    style G fill:#0d1117,stroke:#00FFB3,stroke-width:2px,color:#fff
```

---

### 4️⃣ [Medical Chatbot & Semantic RAG](https://github.com/AnmolRajpoot25/medical_chatbot)
> **Document-grounded healthcare assistant with dense vector search, similarity thresholding, and hallucination reduction.**
- **Tech Stack:** `Flask` • `FAISS (IndexFlatL2)` • `Sentence Transformers (all-MiniLM-L6-v2)` • `PyPDF` • `Hugging Face`
- **Key Milestones:** 384-dimensional dense semantic search; semantic overlap chunking; grounded context verification.

```mermaid
flowchart LR
    UQ["User Clinical Query"] --> ST["Sentence Transformer Embeddings"]
    ST --> FAISS[("FAISS Dense Vector Index")]
    FAISS --> CTX["Top-K Medical Knowledge Passages"]
    CTX --> LLM["LLM Grounded Response Generation"]
    LLM --> OUT["Verified Medical Synthesis"]

    style UQ fill:#0d1117,stroke:#00F7FF,stroke-width:2px,color:#fff
    style FAISS fill:#0d1117,stroke:#FFD700,stroke-width:2px,color:#fff
    style OUT fill:#0d1117,stroke:#00FFB3,stroke-width:2px,color:#fff
```

---

### 5️⃣ [Multi-Source Research Agent](https://github.com/AnmolRajpoot25/research-AI_agent)
> **LangGraph-driven cyclical agent coordinating live web searches and scientific arXiv retrieval to formulate cited technical briefs.**
- **Tech Stack:** `LangGraph (Cyclical StateGraph)` • `LangChain v0.3` • `Groq LPU (Llama-3-70B @ 750 t/s)` • `Tavily Search API` • `arXiv REST API` • `Streamlit`
- **Key Milestones:** Autonomous cyclical routing; multi-source factual verification; dynamic abstract synthesis with citations.

```mermaid
flowchart TD
    Q["Research Topic Input"] --> LG{"LangGraph Cyclical Router"}
    
    LG -->|"Academic Theory"| AX["arXiv REST API Tool"]
    LG -->|"Live Web Evidence"| TV["Tavily Search API Tool"]
    
    AX --> EVAL["Groq Llama-3-70B Evidence Extractor"]
    TV --> EVAL
    
    EVAL --> HYP{"Sufficiency Threshold Met?"}
    HYP -->|"Need More Data"| LG
    HYP -->|"Verified"| REP["Structured Markdown Brief with Citations"]

    style Q fill:#0d1117,stroke:#00F7FF,stroke-width:2px,color:#fff
    style LG fill:#0d1117,stroke:#FFD700,stroke-width:2px,color:#fff
    style REP fill:#0d1117,stroke:#00FFB3,stroke-width:2px,color:#fff
```

---

### 6️⃣ [Smart Ingestion & Vector Retrieval Engine](https://github.com/AnmolRajpoot25/smart-ingestion-engine)
> **High-throughput document ingestion with sliding token overlap, SHA-256 deduplication, and Qdrant vector indexing.**
- **Tech Stack:** `Python 3.12 Asyncio` • `Qdrant Vector DB` • `Sentence Transformers` • `PyPDF` • `FastAPI`
- **Key Milestones:** Structure-aware markdown/PDF hierarchy parsing; customizable token overlap windows; batch-optimized dense vector embeddings.

```mermaid
flowchart LR
    DOC["PDF / Markdown / Documents"] --> CHK["Structure-Aware Recursive Chunking"]
    CHK --> DEDUP["SHA-256 Deduplication Hashing"]
    DEDUP --> EMB["Sentence Transformers (all-MiniLM-L6-v2)"]
    EMB --> QDR[("Qdrant Vector DB + Payload Metadata")]
    QDR --> RET["Dense Top-K Context Retrieval"]

    style DOC fill:#0d1117,stroke:#00F7FF,stroke-width:2px,color:#fff
    style QDR fill:#0d1117,stroke:#8B5CF6,stroke-width:2px,color:#fff
    style RET fill:#0d1117,stroke:#00FFB3,stroke-width:2px,color:#fff
```

---

### 7️⃣ Computer Vision & Real-Time Gestures
> **Interactive landmark geometry, skeleton tracking, and trigger state machines.**
- **Tech Stack:** `OpenCV 4` • `MediaPipe Hands (21 3D Landmarks)` • `MediaPipe Pose (33 Landmarks)` • `Face Mesh (468 Points)`
- **Key Milestones:** Real-time 30 FPS frame buffering; spatial landmark Euclidean geometry; state-machine-driven gesture actions.

```mermaid
flowchart LR
    CAM["Camera Stream (30 FPS)"] --> OCV["OpenCV Frame Buffer"]
    OCV --> MP["MediaPipe Spatial Landmark Extractor"]
    MP --> GEO["Euclidean Distance Geometry"]
    GEO --> SM{"Gesture Trigger State Machine"}
    SM --> ACT["OS / Canvas Control Action"]

    style CAM fill:#0d1117,stroke:#00F7FF,stroke-width:2px,color:#fff
    style MP fill:#0d1117,stroke:#FFD700,stroke-width:2px,color:#fff
    style ACT fill:#0d1117,stroke:#00FFB3,stroke-width:2px,color:#fff
```

</div>
</details>
</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="900" />
</p>

## 🛠️ <span style="color:#00FFB3">Technical Skills & Ecosystem</span>

<table align="center" width="100%">
  <tr>
    <td width="30%" valign="top"><b>🤖 AI & Foundation Models</b></td>
    <td width="70%">
      <code>PyTorch 2.x</code> • <code>Hugging Face Transformers</code> • <code>Qwen 2.5</code> • <code>PEFT / LoRA / QLoRA</code> • <code>Causal Attention</code> • <code>BPE Tokenization</code> • <code>SFT & Preference Alignment</code> • <code>Groq LPU</code> • <code>Gemini 2.5</code>
    </td>
  </tr>
  <tr>
    <td width="30%" valign="top"><b>⚡ Agent Orchestration & RAG</b></td>
    <td width="70%">
      <code>LangGraph (Cycle Routing)</code> • <code>LangChain v0.3</code> • <code>Model Context Protocol (MCP)</code> • <code>Qdrant</code> • <code>FAISS</code> • <code>PGVector</code> • <code>ChromaDB</code> • <code>Sentence Transformers</code> • <code>Hybrid Retrieval</code>
    </td>
  </tr>
  <tr>
    <td width="30%" valign="top"><b>🌐 Backend & Systems</b></td>
    <td width="70%">
      <code>Python 3.12 (Asyncio)</code> • <code>FastAPI</code> • <code>Flask</code> • <code>PostgreSQL (Neon)</code> • <code>SQLAlchemy 2.0</code> • <code>OAuth 2.0 (3LO)</code> • <code>Fernet-256 Encryption</code> • <code>Cloudflare Workers</code> • <code>RESTful APIs</code> • <code>Docker</code>
    </td>
  </tr>
  <tr>
    <td width="30%" valign="top"><b>📊 Classical ML & Data Science</b></td>
    <td width="70%">
      <code>Scikit-learn</code> • <code>XGBoost</code> • <code>PyTorch LSTM / Bi-LSTM</code> • <code>Random Forests</code> • <code>Pandas</code> • <code>NumPy</code> • <code>FRED API</code> • <code>EDA & Visualization</code>
    </td>
  </tr>
  <tr>
    <td width="30%" valign="top"><b>👁️ Computer Vision & Web Tools</b></td>
    <td width="70%">
      <code>OpenCV 4</code> • <code>MediaPipe (Hands / Pose / Face Mesh)</code> • <code>JavaScript (ES2024)</code> • <code>Chrome Extensions Manifest V3</code> • <code>Service Workers</code>
    </td>
  </tr>
  <tr>
    <td width="30%" valign="top"><b>🏛️ Computer Science Core</b></td>
    <td width="70%">
      <code>Data Structures & Algorithms (C++)</code> • <code>OOP (SOLID)</code> • <code>Operating Systems</code> • <code>DBMS</code> • <code>Computer Networks</code> • <code>High-Level System Design</code>
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,fastapi,flask,postgres,docker,gcp,linux,git,cpp,js,react,vscode" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="900" />
</p>

## 🎯 <span style="color:#FFD700">Problem Solving & Algorithms</span>

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <a href="https://leetcode.com/u/Anmol_1707/" target="_blank">
          <img src="https://leetcard.jacoblin.cool/Anmol_1707?theme=tokyonight&font=Fira%20Code&ext=activity" alt="LeetCode Stats" />
        </a>
      </td>
      <td align="center" width="50%">
        <p><b>🏆 LeetCode Knight (Top 5%)</b></p>
        <p>
          <img src="https://img.shields.io/badge/Problems_Solved-650%2B-00FFB3?style=for-the-badge&logo=leetcode&logoColor=black" /><br><br>
          <img src="https://img.shields.io/badge/Language-C%2B%2B%20%7C%20Python-00F7FF?style=for-the-badge" /><br><br>
          <a href="https://codolio.com/profile/Anmol2507" target="_blank">
            <img src="https://img.shields.io/badge/View_Codolio_Profile-121212?style=for-the-badge&logo=codeforces&logoColor=00F7FF" alt="Codolio Profile" />
          </a>
        </p>
      </td>
    </tr>
  </table>
</div>

---

## 📈 <span style="color:#8B5CF6">GitHub Telemetry</span>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AnmolRajpoot25&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F7FF&icon_color=00FFB3&text_color=E6EDF3" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AnmolRajpoot25&theme=tokyonight&hide_border=true&background=0D1117&ring=00F7FF&fire=FFD700&currStreakLabel=00FFB3" height="165" alt="GitHub Streak" />
</div>

---

## 💼 Experience & Leadership Highlights

- 🏢 **AI Intern @ Solvor (Nov 2025 – Jan 2026):** Engineered an LLM revision assistant and MCQ generator with LangChain and FastAPI; achieved a **20%+ improvement in response relevance**.
- 🔬 **Research Intern @ IIIT Bhopal (Feb 2026 – Apr 2026):** Conducted short-term solar load forecasting over the Ausgrid dataset (300+ households, 3+ years), benchmarking Random Forest, XGBoost, and PyTorch LSTMs.
- 🎓 **Vice President @ ARC, IIIT Bhopal:** Led career mentorship sessions and coding workshops for **350+ undergraduate students**.

---

## 🤝 Let's Collaborate & Connect

Whether you want to discuss **LLM evaluations**, **agentic workflows**, **distributed AI pipelines**, or open opportunities:

<p align="center">
  <a href="mailto:rajpootanmol779@gmail.com">
    <img src="https://img.shields.io/badge/Email-rajpootanmol779@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://linkedin.com/in/anmol-rajpoot-b5b770290">
    <img src="https://img.shields.io/badge/LinkedIn-Anmol_Rajpoot-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://drive.google.com/file/d/1b8CqxKuY6dxMMgAcDl0wRsYY87IyRSiJ/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-Download_PDF-34A853?style=for-the-badge&logo=googledrive&logoColor=white"/>
  </a>
</p>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=22&duration=3000&color=FFD700&center=true&vCenter=true&width=650&lines=Build+systems,+not+just+models.+%F0%9F%9A%80" />
</div>
