<div align="center">

#  Hey, I'm Rahul

### Software Engineer | Backend Development | Data Engineering | Cloud & DevOps

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-yadav-a42316219)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rahulyadav4)

</div>

--

## About Me

Software Engineer with **2.1+ years of experience** in backend development and data engineering, currently working with enterprise clients **Ford** and **Nissan** on production-grade ETL pipelines and distributed backend systems.

I enjoy building systems that are scalable, reliable, and efficient — whether that's a high-throughput data pipeline processing millions of records, a cloud-native microservice handling thousands of requests per second, or a well-architected Kubernetes deployment with full observability.

- Currently working on production ETL pipelines and distributed backend systems at Tech Mahindra
- Focused on cloud-native architecture, data engineering at scale, and system design
- Solved **220+ DSA problems** across LeetCode, CodeChef, and HackerEarth
- CodeChef rating **1300+**
- AWS Certified Cloud Practitioner (2025)

---

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
- **Orchestration:** Kubernetes (local cluster)
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

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rahulyadav4/AWS-ETL) 🔒 Private Repo — [Request Access via LinkedIn] - [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-yadav-a42316219)


A fully serverless, event-driven ETL pipeline built on AWS that ingests raw CSV data, validates and transforms it using PySpark on AWS Glue, and loads clean data into Amazon Redshift — all orchestrated without a single persistent server.

**Key Highlights:**
- Designed end-to-end serverless pipeline using **AWS Glue, S3, Lambda, EventBridge, and Redshift**
- Implemented **incremental processing** to handle only new/changed records per batch run
- Built **UPSERT-based ingestion** logic to handle duplicate and late-arriving records gracefully
- Enforced **schema validation, null checks, format checks, and deduplication** at the Glue layer
- Separated records into **curated (valid)** and **rejected (invalid)** datasets for downstream auditability
- Optimized Redshift ingestion using **COPY operations** and **partition-based processing** for high throughput
- Final validation with **row count checks** across source, staging, and target to ensure load integrity.

**Pipeline Flow:**

---

### 2. Scalable Spring Boot Microservice | Kubernetes + Monitoring
> `Java` `Spring Boot` `Kubernetes` `Docker` `Redis` `MongoDB` `Prometheus` `Grafana`

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rahulyadav4/backend-app-prod) 🔒 Private Repo — [Request Access via LinkedIn] - [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-yadav-a42316219)


A production-style cloud-native backend system built with Spring Boot microservices, deployed on Kubernetes with full observability, autoscaling, and a Redis cache-aside pattern for high-performance reads.

**Key Highlights:**
- Built cloud-native microservices capable of handling **3,000–5,000 req/s** under sustained load
- Implemented **Redis cache-aside pattern** reducing direct database load by **70–80%**
- Deployed on **Kubernetes (local cluster)** with Docker, using pods, services, and ingress routing
- Configured **Horizontal Pod Autoscaler (HPA)** for automatic load-based scaling
- Set up **readiness and liveness probes** for robust health management
- Full observability stack: **Prometheus** for metrics scraping + **Grafana** for real-time dashboards
- Metrics instrumented via **Micrometer + Spring Boot Actuator**
- Automated build and deployment pipeline via **GitHub Actions CI/CD**
- Layered architecture: `Controller → Service → Repository` with JWT-based auth

**System Architecture:**

---
User → Ingress → Kubernetes Service → Spring Boot Pod ├── Redis (Cache Layer) └── MongoDB (Persistence Layer) └── Micrometer → Prometheus → Grafana


### 3. Policy Consensus Engine (RAG Agentic System)
> `Python` `RAG` `LLM` `Gemini` `FAISS` `PySpark` `Gradio` `Agentic AI`

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rahulyadav4/RAG_AGENTIC) 🔒 Private Repo — [Request Access via LinkedIn] - [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-yadav-a42316219)

A fully agentic Retrieval-Augmented Generation (RAG) system that ingests multiple policy PDF documents, builds a semantic vector store, and uses Gemini LLM to surface cross-policy agreements, conflicts, and actionable consensus recommendations.

**Key Highlights:**
- Built an **end-to-end RAG pipeline** using FAISS vector store and `sentence-transformers` for semantic retrieval across multiple policy documents
- Integrated **Google Gemini 2.5 Flash** for LLM-powered policy summarization, Q&A, and consensus generation
- Implemented **multi-modal ingestion** — extracts both text and embedded images from PDFs, with Gemini analyzing visual content (workflows, hierarchies, tables)
- Designed a **weighted policy consensus engine** — each policy is assigned an importance weight (1–10) that influences conflict resolution and recommendation priority
- Generated structured policy summaries covering Executive Summary, Priorities, Mandatory Actions, Risks, Agreements, Conflicts, and a one-line consensus
- Built **persistent vector storage** using FAISS index + JSON metadata, enabling incremental policy additions across sessions
- Implemented **semantic chunking and retrieval** with top-K similarity search to provide grounded, context-aware answers
- Developed an interactive **Gradio UI** with tabs for policy ingestion, Q&A, and policy management

**System Architecture:**
PDF Upload → Text + Image Extraction (PyMuPDF) ↓ Image Analysis (Gemini Vision) + Text Chunking ↓ Embeddings (sentence-transformers) → FAISS Vector Store ↓ Query → Semantic Retrieval → Gemini LLM → Consensus Answer

## Certifications, Achievements & Contributions

| Badge | Certification | Year |
|---|---|---|
| | AWS Certified Cloud Practitioner | 2025 |
| | HackerRank Advanced SQL Certification | 2025 |
| | HackerRank Software Engineer Certification | 2025 |
| | 220+ DSA Problems — LeetCode, CodeChef, HackerEarth | Ongoing |
| | CodeChef Rating 1300+ | Ongoing |
---


### Apache ShardingSphere
> `Java` `ANTLR` `Grammar Parsing` `JUnit` `Open Source Debugging'

Investigated a reported parsing issue around the `UCASE(name)` function — tracing the flow from grammar definition (`BaseRule4.g4`) through to the Visitor layer (`VisitorFunctionCall`) to confirm correctness.

📄 Full investigation log: [ShardingSphere Open Source Investigation Log](https://github.com/Rahulyadav4/opensource)

**Summary:** Confirmed `UCASE(name)` is parsed correctly at both the grammar and visitor level — parse tree generated as expected, no defect identified.



###ongoing PR
> https://github.com/bucket4j/bucket4j/issues/530
---

<h3>📊 GitHub Stats</h3>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rahulyadav4&show_icons=true&theme=radical&count_private=true&cache_seconds=1800" height="180" alt="GitHub Stats" />
</p>

*Open to backend engineering and data engineering roles. Feel free to reach out.*

</div>
