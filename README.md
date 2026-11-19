<div align="center">

# Govind Goel

### AI / GenAI Engineer · Multi-Agent Systems · RAG & GraphRAG · Backend

*I build LLM systems that show their evidence, verify their answers, and ship behind real APIs.*

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3000&pause=900&color=00B4D8&center=true&vCenter=true&width=800&lines=Grounded+LLM+applications%2C+not+just+chatbots;RAG+%7C+GraphRAG+%7C+CRAG+%7C+LangGraph;Python+%7C+FastAPI+%7C+Neo4j+%7C+Vector+Databases;From+AI+research+to+working+backend+systems)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GovindGoel1401)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:goyalgovind1401@gmail.com)
[![GATE](https://img.shields.io/badge/GATE-Qualified_2026-0B7285?style=for-the-badge)](#-achievements--certifications)
[![AWS AI](https://img.shields.io/badge/AWS-AI_Practitioner-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)](#-achievements--certifications)
[![Profile Views](https://komarev.com/ghpvc/?username=GovindGoel1401&color=00b4d8&style=for-the-badge&label=Profile+Views)](https://github.com/GovindGoel1401)

**[Projects](#-featured-projects) · [Skills](#%EF%B8%8F-tech-stack) · [Experience](#-experience) · [Contact](#-lets-build-something-reliable)**

</div>

---

## ⚡ At a Glance

| | |
|---|---|
| 🧠 **What I do** | Design retrieval pipelines, multi-agent workflows, and backend APIs that make LLM output trustworthy |
| 🔬 **Core ideas** | Hybrid vector + graph retrieval · corrective RAG · human-in-the-loop agents · stateful, resumable workflows |
| 🎓 **Education** | B.Tech, KIET Group of Institutions · CGPA **8.3 / 10** (2023 – Present) |
| 🏅 **Credentials** | GATE 2026 Qualified · AWS Certified Cloud Practitioner · AWS Certified AI Practitioner |
| 💼 **Experience** | Backend & AI Intern @ Techsage (Nov 2025 – Jan 2026) |
| 🔭 **Exploring** | Autonomous software-engineering agents · evaluation of GraphRAG/CRAG · AI observability |

> **My thesis:** an LLM answer is only as useful as the evidence behind it. I focus on the layer around the model: retrieval that finds the right context, agents that know when to ask, verify, and correct, and backend services that turn it all into a product.

---

## 🚀 Featured Projects

### ⚖️ JurisMind AI: Legal Reasoning & Decision Intelligence

> A multi-agent platform for legal document understanding, evidence analysis, research, and structured argumentation.

**Stack:** `Python` `FastAPI` `LangGraph` `LLM APIs` `Vector Databases`

```mermaid
flowchart LR
    A[Case Documents] --> B[Retrieval Router]
    B -->|needs context| C[Vector Retrieval]
    B -->|already sufficient| E
    C --> D[Knowledge Context]
    D --> E[Reasoning Agents]
    E --> F[Evidence Analysis]
    F --> G[Structured Legal Output]
```

- **Orchestrated** specialized reasoning agents (case interpretation, evidence analysis, response assembly) with **LangGraph**.
- **Dynamic retrieval routing** skips unnecessary retrieval steps to cut redundant processing.
- **Grounded outputs** by combining vector search with structured knowledge context.

---

### 🌿 Deepleaf: GraphRAG Plant Intelligence System

> Semantic retrieval plus knowledge-graph reasoning for precise, explainable plant recommendations.

**Stack:** `GraphRAG` `CRAG` `Neo4j` `Vector Databases` `Knowledge Graphs`

```mermaid
flowchart LR
    Q[User Query] --> V[Vector Similarity Search]
    Q --> G[Neo4j Graph Traversal]
    V --> M[Context Fusion]
    G --> M
    M --> L[LLM Generation]
    L --> C{CRAG Validation}
    C -->|supported| R[Final Answer]
    C -->|unsupported| X[Corrective Retrieval] --> M
```

- **Hybrid retrieval:** embeddings for semantic match, graph relationships for entity-level reasoning.
- **Corrective RAG (CRAG)** validates and repairs answers to reduce unsupported claims.
- 📈 **~20–25% improvement in response reliability** over the baseline pipeline.

---

### 🤖 Autonomous GenAI Software Engineering System

[![Repository](https://img.shields.io/badge/View_Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/GovindGoel1401/Autonomous-GenAI-Software-Engineering-System-Multi-Agent-AI-Platform-)

> A multi-agent system that turns natural-language requirements into engineering specifications, built to grow into a full idea-to-deployment pipeline.

**Stack:** `Node.js` `LangGraph` `Gemini API` `JavaScript` `State Checkpointing` `Redis`

```mermaid
flowchart LR
    R[Requirement] --> PM[PM Agent]
    PM -->|ambiguous| H[Human Clarification]
    H --> PM
    PM -->|clear| S[Structured Specification]
    S -.-> AR[Architect]
    AR -.-> CO[Coder]
    CO -.-> RV[Reviewer]
    RV -.-> DB[Debugger]
    DB -.-> DP[Deploy]
```

<sub>Solid lines: implemented (Phase 1). Dotted lines: roadmap.</sub>

- **Human-in-the-loop routing:** the graph asks clarifying questions before committing to a spec.
- **Resumable execution** via checkpointing (in-memory or Redis) so interrupted runs can continue.
- **Cost awareness** through Gemini token-usage tracking.
- **Clean architecture:** agents communicate through shared graph state, not direct node-to-node calls.
- **Tested:** graph-skeleton mock tests plus PM-Agent integration tests.

---

### ☁️ IBM Cloud Object Storage Q&A Assistant

> Cloud-backed file storage with a conversational assistant for asking questions about stored documents.

**Stack:** `IBM Cloud` `Cloud Object Storage` `IBM watsonx` `IAM`

- Uploads and manages files in **IBM Cloud Object Storage** with a structured indexing workflow for discovery.
- **watsonx chatbot** answers context-aware questions about stored files.
- **IAM-based access control** protects cloud resources.
- 🏆 Recognized as **Top Performer** in the IBM Cloud Virtual Internship.

---

## 🛠️ Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### AI, LLMs & Agentic Systems
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-222222?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-0077B6?style=for-the-badge)
![GraphRAG](https://img.shields.io/badge/GraphRAG-5A189A?style=for-the-badge)
![CRAG](https://img.shields.io/badge/Corrective_RAG-6A4C93?style=for-the-badge)
![Multi-Agent AI](https://img.shields.io/badge/Multi--Agent_AI-007F86?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLM_Pipelines-414141?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-3D5A80?style=for-the-badge)

### Backend & APIs
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-0B7285?style=for-the-badge)

### Data, Search & Knowledge Graphs
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-111111?style=for-the-badge)
![Chroma](https://img.shields.io/badge/Chroma-FF6B6B?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-1D3557?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Cloud & Developer Tools
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![IBM Cloud](https://img.shields.io/badge/IBM_Cloud-1261FE?style=for-the-badge&logo=ibmcloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</div>

---

## 💼 Experience

### Backend & AI Intern · Techsage
`Nov 2025 – Jan 2026`

- Built and tested backend features covering **API integration, database operations, and HTTP request handling** for internal applications.
- Implemented **RAG-based features** (document retrieval and context-aware response generation), bridging backend services with working AI functionality.

---

## 🏆 Achievements & Certifications

| | |
|---|---|
| 🎯 **GATE 2026** | Qualified |
| ☁️ **AWS Certified Cloud Practitioner** | Cloud fundamentals |
| 🤖 **AWS Certified AI Practitioner** | AI/ML and GenAI on AWS |
| 🌟 **IBM Cloud Virtual Internship** | Top Performer |
| 📘 **Data Structures & Algorithms** | Udemy |

---

## 🎓 Education

**KIET Group of Institutions**: B.Tech · `2023 – Present` · CGPA **8.3 / 10**
**Dehradun Public School**: Higher Secondary · `2022 – 2023` · **88.2%**

---

## 🧭 What I'm Working Toward

- 🔄 Taking the **Autonomous Software Engineering** system beyond Phase 1: Architect, Coder, Reviewer, Debugger, and Deploy agents.
- 📏 Building better **evaluation methods for GraphRAG / CRAG** pipelines.
- 🤝 Deepening **multi-agent orchestration** and human-in-the-loop design.
- 📡 Improving AI application **scalability, observability, and backend reliability**.

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=GovindGoel1401&show_icons=true&theme=tokyonight&hide_border=true" alt="Govind's GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GovindGoel1401&layout=compact&theme=tokyonight&hide_border=true" alt="Most used languages" />

<br/>

<img src="https://streak-stats.demolab.com?user=GovindGoel1401&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />

</div>

---

<div align="center">

## 🤝 Let's Build Something Reliable

*Open to collaborating on AI engineering, retrieval systems, agentic workflows, and backend applications.*

[![Projects](https://img.shields.io/badge/Explore_My_Projects-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GovindGoel1401?tab=repositories)
[![Email](https://img.shields.io/badge/Get_In_Touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:goyalgovind1401@gmail.com)

</div>
