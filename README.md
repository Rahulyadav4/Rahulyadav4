<div align="center">

#  Hi, I'm Rahul Yadav

### Software Engineer | Backend Development | Data Engineering | Cloud & DevOps

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-yadav-a42316219)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rahulyadav4)

</div>

---

## 👨‍💻 About Me

Software Engineer with **2+ years of experience** in backend development and data engineering, currently at **Tech Mahindra** working with enterprise clients **Ford** and **Nissan** on production-grade ETL pipelines and distributed backend systems.

I enjoy building systems that are scalable, reliable, and efficient — whether that's a high-throughput data pipeline processing millions of records, a cloud-native microservice handling thousands of requests per second, or a well-architected Kubernetes deployment with full observability.

- 🔭 Currently working on production ETL pipelines and distributed backend systems at Tech Mahindra
- 🌱 Focused on cloud-native architecture, data engineering at scale, and system design
- 🧠 Solved **200+ DSA problems** across LeetCode, CodeChef, and HackerEarth
- 🏆 CodeChef rating **1300+**
- ☁️ AWS Certified Cloud Practitioner (2025)

---

## 🛠️ Technical Skills

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
- **Orchestration:** Kubernetes (Minikube)
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

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rahulyadav4/AWS-ETL)

A fully serverless, event-driven ETL pipeline built on AWS that ingests raw CSV data, validates and transforms it using PySpark on AWS Glue, and loads clean data into Amazon Redshift — all orchestrated without a single persistent server.

**Key Highlights:**
- Designed end-to-end serverless pipeline using **AWS Glue, S3, Lambda, EventBridge, and Redshift**
- Implemented **incremental processing** to handle only new/changed records per batch run
- Built **UPSERT-based ingestion** logic to handle duplicate and late-arriving records gracefully
- Enforced **schema validation, null checks, format checks, and deduplication** at the Glue layer
- Separated records into **curated (valid)** and **rejected (invalid)** datasets for downstream auditability
- Optimized Redshift ingestion using **COPY operations** and **partition-based processing** for high throughput
- Final validation with **row count checks** across source, staging, and target to ensure load integrity

**Pipeline Flow:**

---

### 2. Scalable Spring Boot Microservice | Kubernetes + Monitoring
> `Java` `Spring Boot` `Kubernetes` `Docker` `Redis` `MongoDB` `Prometheus` `Grafana`

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/Rahulyadav4/backend-app-prod)

A production-style cloud-native backend system built with Spring Boot microservices, deployed on Kubernetes with full observability, autoscaling, and a Redis cache-aside pattern for high-performance reads.

**Key Highlights:**
- Built cloud-native microservices capable of handling **3,000–5,000 req/s** under sustained load
- Implemented **Redis cache-aside pattern** reducing direct database load by **70–80%**
- Deployed on **Kubernetes (Minikube)** with Docker, using pods, services, and ingress routing
- Configured **Horizontal Pod Autoscaler (HPA)** for automatic load-based scaling
- Set up **readiness and liveness probes** for robust health management
- Full observability stack: **Prometheus** for metrics scraping + **Grafana** for real-time dashboards
- Metrics instrumented via **Micrometer + Spring Boot Actuator**
- Automated build and deployment pipeline via **GitHub Actions CI/CD**
- Layered architecture: `Controller → Service → Repository` with JWT-based auth

**System Architecture:**

---
User → Ingress → Kubernetes Service → Spring Boot Pod ├── Redis (Cache Layer) └── MongoDB (Persistence Layer) └── Micrometer → Prometheus → Grafana

## 🏆 Certifications & Achievements

| Badge | Certification | Year |
|---|---|---|
| ☁️ | AWS Certified Cloud Practitioner | 2025 |
| 🟢 | HackerRank Advanced SQL Certification | 2025 |
| 🟢 | HackerRank Software Engineer Certification | 2025 |
| 🧠 | 200+ DSA Problems — LeetCode, CodeChef, HackerEarth | Ongoing |
| ⭐ | CodeChef Rating 1300+ | Ongoing |

---

## 📊 GitHub Stats

<div align="center">

![Rahul's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Rahulyadav4&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Rahulyadav4&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*Open to backend engineering and data engineering roles. Feel free to reach out.*

</div>
