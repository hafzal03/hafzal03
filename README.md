<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Hafizal%20Ahmed%20Hassan%20Mohammed&fontSize=40&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Software%20Engineer%20%7C%20AI%20Integration%20%26%20Agentic%20Systems&descAlignY=62&descSize=16"/>
</p>

<h1 align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&duration=3000&pause=1000&color=70A5FD&center=true&vCenter=true&width=850&lines=Building+Agentic+AI+Systems;MCP+Servers+%7C+LangChain+%7C+LangGraph+%7C+RAG;Python+%7C+Docker+%7C+Kubernetes+%7C+Azure;Open+to+AI+Engineering+Opportunities+Across+Europe"/>
</h1>

<h4 align="center">Designing agent-facing tools, retrieval pipelines, and cloud-native services that connect AI agents to real systems — with the software engineering discipline to keep them secure, testable, and maintainable.</h4>

<p align="center">
<a href="https://github.com/hafzal03"><img src="https://komarev.com/ghpvc/?username=hafzal03&style=flat-square&color=blue"/></a>
<a href="https://linkedin.com/in/hafzal-ahamed-hasan-mohamed"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="https://hafzal.dev"><img src="https://img.shields.io/badge/Portfolio-hafzal.dev-6E56CF?style=flat-square&logo=vercel&logoColor=white"/></a>
<a href="mailto:hafzalahamed003@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

---

## 👋 About Me

- 🎓 **M.Sc. in Informatics** — Technical University of Košice, Faculty of Electrical Engineering and Informatics (2023–2025)
- 🎓 **B.C.A. (Bachelor of Computer Applications)** — Jamal Mohamed College (Autonomous), India (2020–2023)
- 🤖 AI Engineer — **Khwarizmi Studio**, a personal AI engineering project: an end-to-end agentic AI platform with MCP servers, LangGraph-orchestrated workflows, and multi-provider LLM integration
- 🔎 Deep hands-on experience with **Model Context Protocol (MCP)**, **LangChain**, **LangGraph**, and **Retrieval-Augmented Generation (RAG)**
- 🐳 Comfortable across the full stack — Python backends, REST APIs, Docker/Kubernetes containerization, and CI/CD automation
- 🌍 Based in Bratislava, Slovakia — open to Software Engineering, AI Integration, and AI Agent Engineering roles across Europe
- 🧠 Currently sharpening Azure DevOps, FastAPI, SQLAlchemy, and enterprise cloud security (Key Vault, Managed Identity)

I like turning "we want AI to do X" into a governed, testable system — the kind where the application, not the model, decides what a tool is allowed to do. That's the problem Khwarizmi Studio and most of the projects below are built around.

## 💻 About Me (Python Style)

```python
class Hafzal:
    name = "Hafizal Ahmed Hassan Mohammed"
    location = "Bratislava, Slovakia"
    degree = "M.Sc. Informatics — Technical University of Košice"
    focus = "AI Integration & Agentic Systems"

    core_stack = [
        "Python", "MCP (Model Context Protocol)", "LangChain", "LangGraph",
        "RAG", "Flask", "PostgreSQL", "pgvector", "Docker", "Kubernetes",
        "Git", "GitHub Actions", "Microsoft Azure"
    ]

    currently_learning = [
        "Azure DevOps Pipelines", "FastAPI", "SQLAlchemy",
        "Enterprise Cloud Security (Key Vault, Managed Identity)"
    ]

    def motto(self):
        return "Design the tool, govern the agent, ship it properly."
```

---

## 🛠️ Tech Stack

**AI & Agentic Systems**
Model Context Protocol (MCP) • Agentic Architecture • LangChain • LangGraph • Tool / Function Calling • LLM Integration (Anthropic, Google Gemini) • Retrieval-Augmented Generation (RAG) • Table-Augmented Generation • Vector Search & Embeddings • Prompt Engineering • Structured Outputs

**Programming Languages**
Python • Java • C++ • JavaScript • TypeScript • SQL

**Backend & APIs**
Flask • REST API design & integration • Backend service development

**Data & Databases**
PostgreSQL • pgvector • MySQL • SQLite • Relational database design • Data validation & processing

**Cloud & DevOps**
Docker • Kubernetes • Microsoft Azure (Static Web Apps, deployment, custom domains) • AWS Fundamentals (Solutions Architect – Associate training) • Git • GitHub • GitHub Actions (CI/CD) • Linux

**Networking**
TCP/IP • DNS • DHCP • VPN • Routing • Switching

**Tools**
Git • GitHub • Virtual Machines • Microsoft Office

---

## 📊 GitHub Statistics

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=hafzal03&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hafzal03&layout=compact&theme=tokyonight&hide_border=true" width="38%"/>
</p>
<p align="center">
<img src="https://streak-stats.demolab.com?user=hafzal03&theme=tokyonight-duo"/>
</p>

---

## 🏆 Featured Projects

### 🧠 Khwarizmi Studio — Agentic AI Platform
*AI Engineer / Developer — Personal AI Engineering Project | May 2026 – Present*

An end-to-end agentic AI platform moving beyond single-call chatbots into a full application architecture spanning retrieval, tool use, workflow orchestration, and structured outputs.

> **Current Status:** The project is currently not publicly hosted due to the ongoing API/LLM inference costs associated with running its AI components at scale.
> **Future Plans:** Development is ongoing, with plans to optimize infrastructure and API usage before moving toward a fully hosted production deployment.

- Built **three MCP servers** — sandboxed code execution, GitHub operations (repo creation, commits, pull requests), and repository search — with the application layer, not the model, governing tool execution and validation
- Orchestrated agent behavior with **LangGraph** (intent classification → retrieval → tool selection → execution → validation → response generation) and used **LangChain** to wire together models, prompts, retrievers, tools, and memory
- Built a **RAG pipeline** with document chunking, embeddings, and PostgreSQL + pgvector similarity search, plus a table-augmented generation path for structured/relational data
- Integrated multiple LLM providers (Anthropic, Google Gemini) behind a provider-agnostic layer with function calling and malformed tool-call handling
- Built a **GitHub App** integration (private-key auth + OAuth) so users can connect their own GitHub accounts
- Containerized the full stack with Docker; built an internal evaluation framework covering 21 quality metrics with a results dashboard
- Applied security practices throughout: secret redaction, credential rotation, tool allowlists, input/output validation, and structured observability (token/latency tracking, failure categorization)

`Python` `MCP` `LangChain` `LangGraph` `Anthropic API` `Gemini API` `PostgreSQL` `pgvector` `Docker` `RAG` `CI/CD` `Microsoft Azure`

### 🌐 Hafzal.dev — Personal AI Engineering Portfolio

A Next.js 15 portfolio with its own RAG-based AI chatbot, **Hafzal AI**, that answers questions about my professional background.

- RAG architecture: portfolio content is chunked, embedded with Google Gemini embeddings, retrieved by cosine similarity, and passed as context to a Gemini LLM — no external vector database
- Fully automated deployment lifecycle: Git → GitHub → GitHub Actions (build/test) → Azure Static Web Apps, with a custom domain, DNS configuration, and HTTPS/SSL
- Server-side environment variable and secret management for API integrations
- Actively maintained — continuing to improve the site and the RAG chatbot

🔗 Live: [hafzal.dev](https://hafzal.dev) · Repo: [github.com/hafzal03/portfolio](https://github.com/hafzal03/portfolio)

`Next.js 15` `TypeScript` `GitHub Actions` `Azure Static Web Apps` `Gemini API` `RAG` `Embeddings`

### 📋 Information System for Computer-Aided Software Engineering (CASE) — Master's Thesis

A web-based information system supporting CASE and project-management activities, built as my M.Sc. diploma project at TUKE.

- Requirements management, dependency tracking with circular-dependency detection, and responsibility assignment via an incidence matrix
- Automated project scheduling and Gantt chart generation, plus a project glossary and structured data import/export
- Verified through defined functional test scenarios covering each module and the dependency-management logic

`Python` `Flask` `Relational Database` `Requirements Engineering` `Software Testing`

### 🛒 Bite Globe E-Commerce Platform

*Built during my time as Technical Operations Assistant at Bite Globe*

A Flask-based platform with REST API integration and SQL-driven data validation, deployed with a multi-container Docker architecture and persistent storage configuration.

`Flask` `PostgreSQL` `Docker` `REST APIs` `SQL`

### ☸️ Docker & Kubernetes Deployment on Microsoft Azure

Containerized and deployed applications using Docker and Kubernetes on Microsoft Azure, including image storage, container orchestration, deployments, services, namespaces, and persistent volumes — applying cloud infrastructure and Linux fundamentals.

`Docker` `Kubernetes` `Microsoft Azure` `Linux`

### 🔒 Secure Client–Server Communication System

A secure C++ client–server system implementing a Diffie-Hellman key exchange for an encrypted communication channel, applying networking, communication protocols, and system architecture principles.

`C++` `Networking` `Diffie-Hellman` `System Architecture`

### ⚡ Parallel Computing Coursework

Master's-level coursework projects in parallel programming, using OpenMP for matrix multiplication and OpenCV-based edge detection, with performance evaluation across implementations.

`OpenMP` `C++` `OpenCV` `Performance Evaluation`

---

## 💼 Professional Experience

**AI Engineer / Developer — Khwarizmi Studio (Personal AI Engineering Project, Remote)** · *May 2026 – Present*
Architecting and building an agentic AI platform end-to-end: MCP servers, LangGraph-orchestrated workflows, multi-provider LLM integration, RAG, and secure, observable infrastructure. Part-time alongside the Bite Globe role through Aug 2026; full-time since Aug 2026.

**Technical Operations Assistant — Bite Globe, Slovakia (Part-time)** · *Jan 2026 – Aug 2026*
Developed and maintained backend applications and internal data workflows using Python, Flask, SQL, and PostgreSQL. Designed and integrated REST APIs, maintained technical documentation, and contributed across the full project lifecycle — requirements, design, development, testing, and deployment. Containerized and deployed applications using Docker and Kubernetes in Linux environments.

---

## 🎓 Education

| Degree | Institution | Year |
|---|---|---|
| M.Sc. in Informatics | Technical University of Košice (TUKE), Faculty of Electrical Engineering and Informatics | 2023 – 2025 |
| Bachelor of Computer Applications (BCA) | Jamal Mohamed College (Autonomous), India | 2020 – 2023 |

**Certifications & Training:**
- AWS Certified Solutions Architect – Associate **Training** — CSTech / SYSTECH (August–September 2022) *(training completed; not the official AWS certification exam)*
- C++ Programming Certificate — Institute of Entrepreneurship and Career Development, Bharathidasan University (February–March 2017), Second Class
- PC Hardware and Troubleshooting (Value-Added Course) — Jamal Mohamed College (Autonomous), Department of Computer Applications, Grade A

---

## 🌱 Currently Learning

Azure DevOps Pipelines • FastAPI • SQLAlchemy • Enterprise Cloud Security (Key Vault, Managed Identity)

## 🎯 What I'm Looking For

- AI-Enabled Software Engineering — MCP servers, agent-facing tools, LLM application integration
- Backend & API Engineering — Python, Flask/FastAPI, secure service design
- Cloud-Native & DevOps — Docker, Kubernetes, Azure, CI/CD automation
- Agentic Architecture — LangChain, LangGraph, RAG, workflow orchestration

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>
</p>

<p align="center"><i>Thanks for reading this far — reach out if you're building something with AI agents, MCP, or cloud-native Python services.</i></p>
