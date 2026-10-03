<div align="center">

# Hey, I'm Rahul

### Software Engineer | Backend Development | Cloud & DevOps

[

![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)

](https://linkedin.com/in/rahul-yadav-a42316219)
[

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

](https://github.com/Rahulyadav4)
[

![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)

](https://leetcode.com/u/Rahul_Yadavlc/)

</div>

## About me

Backend engineer building scalable backend applications, cloud-native services, and production-grade data platforms. I design systems that are reliable, resilient, and efficient, from high-throughput pipelines processing millions of records to distributed microservices running production workloads.

Currently working with enterprise clients on production distributed backend systems and cloud-based data platforms.

## What I Work With

- **Backend:** Java, Spring Boot, REST APIs, Microservices
- **Cloud & Data:** AWS (Glue, Lambda, S3, Redshift), PySpark, SQL
- **Architecture:** System Design (LLD & HLD), Distributed Systems, Event-Driven Architecture
- **DevOps:** Docker, Kubernetes, Git, CI/CD, GitHub Actions

## Highlights

- Designed an end-to-end microservice for scalability and low latency, following SOLID principles.
- Build for scalability, fault tolerance, observability, and production reliability.
- Built and maintained production data pipelines processing **5M+** records/day.
- Cut pipeline latency by **60%** through workflow and performance optimization.
- Cut production incident resolution time by **40%** through root cause analysis and reliability practices.
- Solved 290+ DSA problems across LeetCode, CodeChef, and HackerEarth.
- LeetCode Rating: 1610
- AWS Certified Cloud Practitioner (2025)

## Interests

Building production-ready software, solving hard backend problems, and going deeper into distributed systems, cloud-native architecture, scalability, and performance engineering.

----

## Technical Skills

### Languages


![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)




![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)




![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)



### Backend Development
- **Framework:** Spring Boot, REST APIs, Microservices Architecture
- **ORM / Auth:** Hibernate / JPA, JWT Authentication
- **Build Tools:** Maven

### Data Engineering
- **Processing:** PySpark, Batch Processing, Incremental Loads
- **Pipeline Design:** ETL Pipelines, Workflow Orchestration, UPSERT Logic, Deduplication, Schema Validation

### Cloud — AWS
- **Compute & Serverless:** AWS Lambda, EC2
- **Storage:** Amazon S3
- **ETL & Analytics:** AWS Glue, Amazon Redshift
- **Eventing:** Amazon EventBridge
- **Architecture Pattern:** Serverless, Event-Driven

### DevOps & Observability
- **Containerization:** Docker
- **Orchestration:** Kubernetes
- **CI/CD:** GitHub Actions
- **Monitoring:** Prometheus, Grafana

### Databases


![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)




![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)




![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)




![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)



---

## 🚀 Projects

### 1. Event-Driven AWS Data Ingestion Pipeline
> `AWS` `PySpark` `Python` `Serverless` `ETL` `Scalable`

[

![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)

](https://github.com/Rahulyadav4/AWS-ETL) - [

![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)

](https://linkedin.com/in/rahul-yadav-a42316219)

A fully serverless, event-driven ETL pipeline on AWS. It ingests raw CSV data, validates and transforms it with PySpark on AWS Glue, and loads clean data into Amazon Redshift, with no persistent servers.

**Key Highlights:**
- Designed an end-to-end serverless pipeline using **AWS Glue, S3, Lambda, EventBridge, and Redshift**
- Implemented **incremental processing** so each batch run handles only new or changed records
- Built **UPSERT-based ingestion** to handle duplicate and late-arriving records
- Enforced **schema validation, null checks, format checks, and deduplication** at the Glue layer
- Split records into **curated (valid)** and **rejected (invalid)** datasets for downstream auditability
- Optimized Redshift ingestion with **COPY operations** and **partition-based processing** for high throughput
- Verified load integrity with **row count checks** across source, staging, and target

**Pipeline Flow:**

---

### 2. Scalable Spring Boot Microservice | Kubernetes + Monitoring
> `Java` `Spring Boot` `Kubernetes` `Docker` `Redis` `MongoDB` `Prometheus` `Grafana`

[

![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)

](https://github.com/Rahulyadav4/backend-app-prod) [

![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)

](https://linkedin.com/in/rahul-yadav-a42316219)

A production-style, cloud-native backend built with Spring Boot microservices, deployed on Kubernetes with full observability, autoscaling, and a Redis cache-aside pattern for fast reads.

**Key Highlights:**
- Built cloud-native microservices handling **3000–5000 req/min** under sustained load
- Cut direct database load by **70–80%** with a **Redis cache-aside pattern**
- Deployed on **Kubernetes (local cluster)** with Docker, using pods, services, and ingress routing
- Configured **Horizontal Pod Autoscaler (HPA)** for load-based scaling
- Added **readiness and liveness probes** for robust health management
- Full observability: **Prometheus** for metrics scraping, **Grafana** for real-time dashboards
- Instrumented metrics via **Micrometer + Spring Boot Actuator**
- Automated build and deployment with **GitHub Actions CI/CD**
- Layered architecture: `Controller → Service → Repository` with JWT-based auth
- Wrote JUnit 5 + Mockito tests across core backend, security, Kafka, configuration, and infrastructure, reaching **98%** instruction and **86%** branch coverage (JaCoCo). Covered authentication, JWT, rate limiting, CRUD, messaging, and configuration paths with isolated, deterministic tests and mocked external dependencies.
- Load-tested on Kubernetes/Minikube with k6 at **100** concurrent VUs for **~3 minutes**: **~94 RPS**, **7.51 ms** median latency, **172 ms P95**, **0** interrupted iterations. Improved high-concurrency stability through liveness-probe tuning and NodePort-based service routing.

**System Architecture:**

---
User → Ingress → Kubernetes Service → Spring Boot Pod ├── Redis (Cache Layer) └── MongoDB (Persistence Layer) └── Micrometer → Prometheus → Grafana

### 3. Policy Consensus Engine (RAG Agentic System)
> `Python` `RAG` `LLM` `Gemini` `FAISS` `PySpark` `Gradio` `Agentic AI`

[

![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)

](https://github.com/Rahulyadav4/RAG_AGENTIC) 🔒 Private Repo — [Request Access via LinkedIn] - [

![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)

](https://linkedin.com/in/rahul-yadav-a42316219)

A fully agentic Retrieval-Augmented Generation (RAG) system. It ingests multiple policy PDFs, builds a semantic vector store, and uses Gemini to surface cross-policy agreements, conflicts, and actionable consensus recommendations.

**Key Highlights:**
- Built an **end-to-end RAG pipeline** with a FAISS vector store and `sentence-transformers` for semantic retrieval across policy documents
- Integrated **Google Gemini 2.5 Flash** for policy summarization, Q&A, and consensus generation
- Implemented **multi-modal ingestion**: extracts text and embedded images from PDFs, with Gemini analyzing visuals (workflows, hierarchies, tables)
- Designed a **weighted consensus engine**: each policy gets an importance weight (1–10) that drives conflict resolution and recommendation priority
- Generated structured summaries: Executive Summary, Priorities, Mandatory Actions, Risks, Agreements, Conflicts, and a one-line consensus
- Built **persistent vector storage** (FAISS index + JSON metadata) that supports incremental policy additions across sessions
- Implemented **semantic chunking and top-K similarity retrieval** for grounded, context-aware answers
- Developed an interactive **Gradio UI** with tabs for policy ingestion, Q&A, and policy management

**System Architecture:**
PDF Upload → Text + Image Extraction (PyMuPDF) ↓ Image Analysis (Gemini Vision) + Text Chunking ↓ Embeddings (sentence-transformers) → FAISS Vector Store ↓ Query → Semantic Retrieval → Gemini LLM → Consensus Answer

## Certifications, Achievements & Contributions

| Badge | Certification | Year |
|---|---|---|
| | AWS Certified Cloud Practitioner | 2025 |
| | HackerRank Advanced SQL Certification | 2025 |
| | HackerRank Software Engineer Certification | 2025 |
| | 290+ DSA Problems — LeetCode, CodeChef, HackerEarth | Ongoing |
| | LeetCode Rating 1610+ | Ongoing |
| | Rank 6392 of ~27,000 in LeetCode Weekly Contest 500 | |
| | Rank 374 of ~40,000 in LeetCode Biweekly Contest 187 | |

---

## Contributions

### Apache ShardingSphere (OSS)
> `Java` `ANTLR` `Grammar Parsing` `JUnit` `Open Source Debugging`

Investigated a reported parsing issue with the `UCASE(name)` function, tracing it from the grammar definition (`BaseRule4.g4`) to the Visitor layer (`VisitorFunctionCall`).

📄 Full investigation log: [ShardingSphere Open Source Investigation Log](https://github.com/Rahulyadav4/opensource)

**Summary:** `UCASE(name)` parses correctly at both grammar and visitor level. The parse tree is generated as expected, so no defect was found.

### Ongoing PRs
> https://github.com/bucket4j/bucket4j/issues/530 — awaiting maintainer response

> https://github.com/resilience4j/resilience4j/issues/1578 — in progress

<h3>📊 GitHub Stats</h3>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rahulyadav4&show_icons=true&theme=radical&count_private=true&cache_seconds=1800" height="180" alt="GitHub Stats" />
</p>

*Open to backend and data engineering roles. Feel free to reach out.*
