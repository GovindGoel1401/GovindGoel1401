<!-- GitHub Profile README • GovindGoel1401 -->
<!-- Keep this file named README.md in the public repository GovindGoel1401/GovindGoel1401 -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:050816,35:0F1E46,65:0EA5E9,100:22D3EE&text=GOVIND%20GOEL&fontColor=FFFFFF&fontSize=54&fontAlignY=38&desc=AI%20%2F%20GenAI%20Engineer%20%E2%80%A2%20Agentic%20Systems%20%E2%80%A2%20RAG%20%2F%20GraphRAG%20%E2%80%A2%20Backend%20Engineering&descSize=18&descAlignY=60&animation=fadeIn" width="100%" alt="Govind Goel banner" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=950&lines=I+build+AI+systems+that+retrieve%2C+reason%2C+validate+and+respond;Multi-Agent+Workflows+%7C+RAG+%7C+GraphRAG+%7C+CRAG+%7C+FastAPI;Interested+in+reliability%2C+retrieval+quality%2C+memory+and+orchestration;From+document+Q%26A+to+legal+intelligence+to+autonomous+AI+workflows" alt="Typing SVG" /></a>

<br/>

<a href="mailto:goyalgovind1401@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/GovindGoel1401"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="#-featured-projects"><img src="https://img.shields.io/badge/Featured_Projects-2563EB?style=for-the-badge&logo=githubactions&logoColor=white" alt="Featured Projects" /></a>
<a href="#-system-thinking"><img src="https://img.shields.io/badge/System_Thinking-0F766E?style=for-the-badge" alt="System Thinking" /></a>

<br/>
<br/>

<img src="https://komarev.com/ghpvc/?username=GovindGoel1401&label=PROFILE%20VIEWS&color=0891b2&style=flat-square" alt="profile views" />
<img src="https://img.shields.io/badge/GATE-Qualified_2026-14B8A6?style=flat-square" alt="GATE Qualified 2026" />
<img src="https://img.shields.io/badge/AWS-Cloud_Practitioner-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS Cloud Practitioner" />
<img src="https://img.shields.io/badge/AWS-AI_Practitioner-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS AI Practitioner" />

</div>

---

## 👋 About Me

I’m **Govind Goel**, an **AI / GenAI Engineer** focused on building systems that go beyond a simple prompt-response loop. I’m especially interested in **retrieval quality, knowledge grounding, agent orchestration, workflow routing, memory, and backend integration**.

My work sits at the intersection of **LLMs + multi-agent systems + RAG/GraphRAG + APIs + data systems**. I enjoy designing AI flows that are not only intelligent, but also **structured, explainable, and useful in real-world applications**.

<table>
<tr>
<td width="50%" valign="top">

### 🔭 Current Focus
- Agentic AI workflows using **LangGraph**
- **RAG / GraphRAG / CRAG** system design
- Multi-stage retrieval and validation pipelines
- Reliable AI backends with **FastAPI**

</td>
<td width="50%" valign="top">

### ⚡ Quick Snapshot
- 🎓 **B.Tech** · KIET Group of Institutions
- 💼 **Backend & AI Intern** · Techsage
- 🏅 **GATE Qualified** · 2026
- ☁️ AWS Certified: **Cloud Practitioner** + **AI Practitioner**

</td>
</tr>
</table>

---

## 🧠 What I Actually Like Building

| Area | What I work on |
|:--|:--|
| **🤖 Agentic AI** | Multi-agent workflows, conditional routing, task decomposition, human-in-the-loop loops |
| **🔎 Grounded Generation** | RAG, GraphRAG, corrective retrieval, document-aware response systems |
| **🕸️ Knowledge Intelligence** | Neo4j-based knowledge graphs, graph traversal, hybrid search, context assembly |
| **⚙️ AI Backend Engineering** | FastAPI services, API integration, pipeline orchestration, data flow and reliability |
| **📌 System Thinking** | Memory handling, routing logic, validation, trade-offs between latency and accuracy |

---

## 🏗️ System Thinking

These are the kinds of questions I naturally think about while building AI systems:

- How should retrieval be routed — **vector search, graph search, or both**?
- When should an agent **ask for clarification** instead of hallucinating an answer?
- How do we keep outputs **grounded, explainable, and efficient**?
- What kind of **memory** should persist across steps — temporary context, feedback memory, or graph state?
- Where should validation happen — **before generation, during reasoning, or after response drafting**?

```mermaid
flowchart LR
    A[User Query / Problem] --> B[Intent + Context Understanding]
    B --> C{Best retrieval path?}
    C -->|Semantic search| D[Vector Retrieval]
    C -->|Relationship reasoning| E[Graph Retrieval]
    C -->|Complex query| F[Hybrid Retrieval]
    D --> G[LLM Reasoning]
    E --> G
    F --> G
    G --> H{Need correction / validation?}
    H -->|Yes| I[Corrective Check / Re-ranking / Evidence Review]
    I --> J[Final Response]
    H -->|No| J[Final Response]
```

---

## 🚀 Featured Projects

## 01 · 🤖 Autonomous GenAI Software Engineering System

<a href="https://github.com/GovindGoel1401/Autonomous-GenAI-Software-Engineering-System-Multi-Agent-AI-Platform-"><img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="repository" /></a>
<img src="https://img.shields.io/badge/Status-Phase_1_Implemented-0F766E?style=for-the-badge" alt="status" />
<img src="https://img.shields.io/badge/Core_Idea-Requirement_to_Specification-2563EB?style=for-the-badge" alt="core idea" />

**Goal:** Build an autonomous multi-agent software engineering workflow that can take a natural language requirement and gradually move it toward structured planning, development, testing, and deployment.

**Tech:** `LangGraph` `Gemini API` `Node.js` `JavaScript` `State Checkpointing`

### Why this project stands out
- Moves beyond a single chatbot into a **role-based AI workflow**.
- Uses **human-in-the-loop clarification** instead of blindly assuming requirements.
- Treats software development as a **stateful graph of decisions**, not just a one-shot prompt.

### Current architecture view

```mermaid
flowchart LR
    A[User Software Requirement] --> B[PM Agent]
    B --> C{Enough clarity?}
    C -->|No| D[Clarification Questions]
    D --> E[Human Input]
    E --> B
    C -->|Yes| F[Structured Project Specification]
    F --> G[Token Usage / Trace Summary]

    subgraph Planned Multi-Agent Expansion
        H[Architect Agent]
        I[Coder Agent]
        J[Reviewer Agent]
        K[Debugger Agent]
        L[Tester Agent]
        M[Deployment Agent]
    end

    F -. roadmap .-> H
    H -. roadmap .-> I
    I -. roadmap .-> J
    J -. roadmap .-> K
    K -. roadmap .-> L
    L -. roadmap .-> M
```

### What’s already implemented
- **PM Agent** for converting rough requirements into structured specifications.
- **Conditional routing** for clarification vs final specification generation.
- **Checkpoint/state support** for flow continuity.
- **Usage visibility** through Gemini token tracking.

> **Important:** The repository currently demonstrates the **Phase 1 PM-agent workflow**. The broader autonomous engineering team is the **vision and roadmap**, not something I’m falsely claiming as fully finished.

---

## 02 · ⚖️ JurisMind AI — Legal Reasoning & Decision Intelligence

<img src="https://img.shields.io/badge/Architecture-Multi--Agent_Legal_AI-7C3AED?style=for-the-badge" alt="architecture" />
<img src="https://img.shields.io/badge/Retrieval-Hybrid_Vector_%2B_Graph-0EA5E9?style=for-the-badge" alt="hybrid retrieval" />

**Goal:** Create a legal intelligence system that can process case information, retrieve relevant legal context, reason from multiple perspectives, and generate structured verdict-style outputs.

**Tech:** `LangGraph` `FastAPI` `LLM APIs` `GraphRAG` `Vector Retrieval` `Neo4j` `Pinecone / Chroma / FAISS`

### High-level flow

```mermaid
flowchart LR
    A[Case Input] --> B[Case Interpreter Agent]
    B --> C[Document Intelligence]
    C --> D[Evidence Analyzer]
    D --> E[Legal Research Agent]
    E --> F{Retrieval Layer}
    F -->|Semantic Evidence| G[Vector Search]
    F -->|Legal Relations / Links| H[Graph Search]
    G --> I[Prosecution Agent]
    H --> I
    G --> J[Defense Agent]
    H --> J
    I --> K[Rebuttal Agent]
    J --> K
    K --> L[Judge Agent]
    L --> M[Verdict / Decision Output]
    M --> N[Reflection / Feedback Memory]
```

### Core design thinking
- Different reasoning roles improve **structured analysis** instead of a flat answer.
- Hybrid retrieval helps combine **semantic similarity** with **relationship-aware legal context**.
- Reflection/feedback memory creates a foundation for **iterative improvement**.

### Project highlights
- Designed **multi-agent legal reasoning pipelines**.
- Incorporated **dynamic retrieval routing** for more efficient query processing.
- Focused on **factual grounding, contradiction handling, and context-aware outputs**.

---

## 03 · 🌿 Deepleaf — GraphRAG-Based AI Plant Intelligence System

<img src="https://img.shields.io/badge/Approach-GraphRAG_%2B_CRAG-16A34A?style=for-the-badge" alt="graphrag crag" />
<img src="https://img.shields.io/badge/Outcome-Improved_Reliability-15803D?style=for-the-badge" alt="reliability" />

**Goal:** Combine semantic retrieval and graph reasoning to deliver more intelligent and reliable plant-related recommendations and responses.

**Tech:** `GraphRAG` `CRAG` `Neo4j` `Knowledge Graphs` `Vector Databases`

```mermaid
flowchart LR
    A[Plant Query / Problem] --> B[Embedding-Based Retrieval]
    A --> C[Knowledge Graph Traversal]
    B --> D[Candidate Context]
    C --> D
    D --> E[Context Fusion]
    E --> F[LLM Response Draft]
    F --> G[CRAG / Corrective Validation]
    G --> H[Improved Final Recommendation]
```

### Why this is interesting
- Uses **graph structure** to capture relationships that pure vector search can miss.
- Adds a **corrective validation step** to reduce hallucinations.
- The project work, as reflected in my resume, reported **~20–25% improvement in reliability**.

---

## 04 · ☁️ IBM Cloud Object Storage Q&A Assistant

<img src="https://img.shields.io/badge/Cloud-IBM_Cloud-1261FE?style=for-the-badge&logo=ibmcloud&logoColor=white" alt="IBM Cloud" />
<img src="https://img.shields.io/badge/Security-IAM_Control-1D4ED8?style=for-the-badge" alt="IAM" />

**Goal:** Build a document-aware Q&A workflow where files stored in IBM Cloud Object Storage can be used securely for contextual question answering.

**Tech:** `IBM Cloud` `Cloud Object Storage` `IAM` `watsonx`

### What it demonstrates
- Cloud-based file storage and retrieval for Q&A use cases.
- Context-aware chatbot interaction over stored documents.
- **IAM-based access control** and structured indexing workflows for safer data access.

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Backend
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />

### GenAI / Orchestration
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-111827?style=for-the-badge" alt="LangGraph" />
<img src="https://img.shields.io/badge/RAG-075985?style=for-the-badge" alt="RAG" />
<img src="https://img.shields.io/badge/GraphRAG-6D28D9?style=for-the-badge" alt="GraphRAG" />
<img src="https://img.shields.io/badge/CRAG-0F766E?style=for-the-badge" alt="CRAG" />
<img src="https://img.shields.io/badge/Multi--Agent_Systems-1D4ED8?style=for-the-badge" alt="Multi-Agent Systems" />
<img src="https://img.shields.io/badge/Prompt_Engineering-7C3AED?style=for-the-badge" alt="Prompt Engineering" />

### Data / Retrieval
<img src="https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j" />
<img src="https://img.shields.io/badge/Pinecone-111827?style=for-the-badge" alt="Pinecone" />
<img src="https://img.shields.io/badge/Chroma-7C3AED?style=for-the-badge" alt="Chroma" />
<img src="https://img.shields.io/badge/FAISS-334155?style=for-the-badge" alt="FAISS" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />

### Cloud & Tools
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/IBM_Cloud-1261FE?style=for-the-badge&logo=ibmcloud&logoColor=white" alt="IBM Cloud" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
<img src="https://img.shields.io/badge/System_Design-0F172A?style=for-the-badge" alt="System Design" />
<img src="https://img.shields.io/badge/API_Integration-1E3A8A?style=for-the-badge" alt="API Integration" />

</div>

---

## 💼 Experience

### Backend and AI Intern — Techsage
`Nov 2025 – Jan 2026`

- Built and tested backend features including **API integrations, database operations, and request handling** for internal applications.
- Implemented introductory **RAG-based AI features** for document retrieval and context-based response generation.
- Gained hands-on experience bridging **backend engineering with practical AI workflows**.

---

## 🏆 Achievements & Certifications

| Category | Details |
|:--|:--|
| **GATE** | Qualified · **2026** |
| **AWS Certifications** | **AWS Certified Cloud Practitioner** · **AWS Certified AI Practitioner** |
| **Recognition** | **Top Performer — IBM Cloud Virtual Internship** |
| **Learning** | **Data Structures & Algorithms — Udemy** |

---

## 📊 GitHub Analytics

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=GovindGoel1401&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub Stats" />
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GovindGoel1401&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com?user=GovindGoel1401&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

## 🎯 Current Direction

- Building stronger intuition around **agent orchestration** and **stateful AI workflows**.
- Going deeper into **retrieval architecture** — vector search, graph search, hybrid strategies, and validation.
- Exploring how to make AI systems more **grounded, reliable, and explainable**.
- Improving at the intersection of **backend systems + AI product engineering**.

---

## 🤝 Let’s Connect

<div align="center">

I’m always interested in **AI engineering**, **GenAI system design**, **RAG/GraphRAG**, and **multi-agent workflow** discussions.

<a href="mailto:goyalgovind1401@gmail.com"><img src="https://img.shields.io/badge/Drop_a_Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="mail" /></a>
<a href="https://github.com/GovindGoel1401"><img src="https://img.shields.io/badge/GitHub_Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="github profile" /></a>

</div>

<!--
Optional upgrades later:
1. Add your LinkedIn URL once available.
2. Replace project headings with exact repo links for JurisMind, Deepleaf, and IBM Cloud project if those repos are public.
3. Add a small hero gif or architecture image if you create one later.
-->
