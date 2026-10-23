# 👋 Hi, I'm Tarun Kumar
**DevOps Engineer | Data Engineering Enthusiast | AI & MLOps Practitioner**

Building secure, observable, and intelligent systems — from CI/CD pipelines to RAG-powered assistants. Bridging infrastructure, data, and AI.

---

## 🚀 About Me

I'm a **DevOps Engineer** with **7+ years total experience** — starting in IT operations and L2/L3 cloud support before moving into infrastructure automation, CI/CD, and Kubernetes. Alongside my DevOps work, I've expanded deeply into **Data Engineering and AI/ML systems**, driven by my **MSc in Artificial Intelligence & Data Science** from Keele University (UK).

My journey spans:
- **🛠️ DevOps & Cloud** — AWS, Terraform, GitHub Actions, Docker, Kubernetes, EKS, Prometheus, Grafana
- **📊 Data Engineering** — ETL pipelines, data lakehouses, Star Schema modelling, SQL, Python, PySpark, Snowflake
- **🤖 AI & MLOps** — RAG systems, vector databases (pgvector), embeddings, LLM integration, MLflow experiment tracking
- **🔒 Security & GRC** — DevSecOps pipelines, secret management, compliance-aligned workflows, vulnerability scanning
- **📈 IT GRC Focus** — Actively building expertise in Governance, Risk, and Compliance frameworks alongside technical delivery

I believe infrastructure and data engineering are converging — and the best platforms will be **secure, observable, and intelligent**.

---

## 🏆 Featured Projects

### 🤖 AI-Powered Incident Triage Bot
**AIOps · GitHub Actions · Ollama · OpenAI · Docker · AWS EC2**
> Automatically detect, diagnose, and alert on CI failures — zero human intervention.
- Dual-LLM architecture: local Ollama (`llama3.1:8b`) for free/offline dev + OpenAI fallback
- GitHub Actions pipeline captures JUnit XML reports **even on failure** via `if: always()`
- Docker-consistent environment: runs identically locally → CI → AWS EC2
- AI outputs severity, root cause, suggested fix, confidence score → emailed automatically
🔗 **[View Project →](https://github.com/tarunkurapati1404/AIops-Incident-Triage)**

---

### 🏦 Fin-Sight AI: RAG-Powered Banking Assistant
**Python · PostgreSQL · pgvector · OpenAI · MLflow · Docker**
> Semantic search + LLM generation for banking customer support — no hallucinations.
- Built full **RAG pipeline**: user question → embedding → vector similarity search → context assembly → grounded response
- `pgvector` stores 1536-dimensional embeddings; cosine similarity retrieves top-3 relevant FAQs
- MLflow tracks every query: latency, token usage, cost, model version
- Docker Compose orchestrates PostgreSQL + app; secrets managed via `.env`
- Also includes **data engineering layer**: 28K+ credit risk records loaded into Star Schema
🔗 **[View Project →](https://github.com/tarunkurapati1404/Fin-Sight-AI)**

---

### ✈️ SkyHigh Airlines DE: End-to-End Data Pipeline
**AWS S3 · Databricks · PySpark · Snowflake · Airflow · Terraform · Power BI**
> Modern data lakehouse processing flight data → executive dashboard.
- Bronze → Silver → Gold layered architecture on AWS S3; partitioned Parquet for performance
- Databricks PySpark cleans and aggregates; Unity Catalog + IAM roles secure access
- Snowflake data warehouse with **Star Schema** (`DIM_AIRLINE`, `DIM_AIRPORT`, `FACT_DAILY_FLIGHT_PERFORMANCE`)
- Apache Airflow containerized via Docker; Terraform provisions cloud infrastructure
🔗 **[View Project →](https://github.com/tarunkurapati1404/SkyHigh_Airlines_DE)**

---

### 🔒 End-to-End DevSecOps Pipeline
**GitHub Actions · Terraform · Ansible · AWS · Bandit · Snyk · Trivy**
> Shift-left security: block vulnerable code before it reaches production.
- SAST + SCA scanning integrated into every pull request
- Terraform provisions EC2 + Security Groups; Ansible deploys & configures
- Secrets via GitHub Encrypted Secrets; `.gitignore` + `.gitattributes` prevent leakage
- Prometheus Node Exporter deployed for observability
🔗 **[View Project →](https://github.com/tarunkurapati1404/AwsDevSecOpsPipeline)**

---

### 🧠 MSc & Data Science Portfolio
| Project | Focus | Tech |
|---|---|---|
| **Civil Infrastructure Damage Detection** | Computer Vision / Object Detection | YOLOv4, Darknet, OpenCV, CUDA, Google Colab — mAP@0.5: **77.7%** |
| **Census Income Analysis** | Data Analysis & SQL | Python, Pandas, SQLite — income prediction & demographic insights |
| **Olist E-commerce DE Pipeline** | ETL & Data Processing | Python, pandas — end-to-end e-commerce data ingestion & transformation |
| **Healthcare DE Project** | Domain-Specific Data Engineering | Python — healthcare dataset processing & analysis |

🔗 **[All Repositories →](https://github.com/tarunkurapati1404?tab=repositories)**

---

## 🛠️ Tech Stack

| Category | Tools & Technologies |
|---|---|
| **Cloud** | AWS (EC2, EKS, S3, VPC, IAM, RDS, CloudWatch), Linux (Ubuntu) |
| **DevOps & CI/CD** | GitHub Actions, Jenkins, Git, Docker, Docker Compose, Kubernetes |
| **Infrastructure as Code** | Terraform, Ansible |
| **Data Engineering** | Python, Pandas, PySpark, SQL, PostgreSQL, Snowflake, Airflow |
| **AI / MLOps** | OpenAI API, Embeddings, pgvector, RAG, MLflow, Jupyter, YOLOv4 |
| **Security & DevSecOps** | Trivy, SonarQube, Snyk, Bandit, OWASP ZAP, GitHub Secrets |
| **Monitoring & Observability** | Prometheus, Grafana, CloudWatch |
| **Visualization** | Power BI, Matplotlib |

---

## 📋 IT GRC & Compliance — Focus Area
I am actively expanding my expertise in **Governance, Risk, and Compliance** alongside technical delivery:
- ✅ DevSecOps pipeline design — aligning engineering workflows with security policy
- ✅ Secret management & access control — least-privilege IAM, encrypted storage
- ✅ Audit-ready infrastructure — Terraform versioning, change traceability
- 🔄 **In Progress:** Understanding ISO 27001, SOC 2, and control mapping for cloud environments
- 🎯 **Goal:** Bridge technical implementation with compliance requirements — building systems that are **secure by design AND compliant by default**

---

## 📌 How I Work
- **Security isn't an afterthought** — it's integrated into the pipeline from day one
- **Reproducibility** — if it runs on my machine, it runs in CI and in the cloud (Docker proves it)
- **Data + Infrastructure = better together** — treating data pipelines with the same rigor as deployment pipelines
- **Explainable AI** — building systems that show *why* they reached a conclusion, not just *what*

---

## 📫 Connect With Me
- 📧 **Email:** tarunasherr@gmail.com
- 🐙 **GitHub:** You're here! ⭐ any project you find interesting — I appreciate the support

---

> *"Building secure, observable, and intelligent systems — one commit at a time."*
