# Tabish Sayyed

Platform Engineer building internal developer platforms and fixing core engines. Rust, Python, Kubernetes, AWS — focused on distributed systems, cloud cost, and deep-level debugging. I merge code into the Delta Lake kernel and build GPU chargeback systems.P
## Featured Work

### ML-Ready Lakehouse — production data infrastructure

A production-oriented medallion architecture built with Delta Lake, Spark, Airflow, and AWS S3. Implements schema validation, automated data quality checks, and quarantine workflows to prevent unreliable data from reaching downstream ML pipelines. Includes automated Parquet exports for model training workflows.

Built and delivered to a client; MVP sold for **$13,000** in January 2026.

`Python` · `Apache Spark` · `Delta Lake` · `Airflow` · `AWS S3` · `Jinja`

[Showcase repository](https://github.com/Tabish0007/ml-lakehouse-showcase)


### Delta-Doctor — Delta Lake protocol diagnostics CLI

A CLI tool that diagnoses and fixes Delta Lake protocol-level health issues before they cause cryptic errors or silent data corruption. Reads a table's `_delta_log`, checks protocol invariants — writer features, reader/writer version compatibility, checkpoint integrity, and orphaned commits — and reports exactly what's wrong, with actionable fixes instead of a 47-line Java stack trace. Includes `diagnose`, `fix --dry-run`, and recursive `scan` commands with CI-friendly exit codes to fail builds on unhealthy tables.

Installable via `pip install delta-doctor`; works with local filesystem, S3, GCS, and Azure Blob Storage.

`Python` · `Delta Lake` · `CLI` · `Data Engineering`

[GitHub repository](https://github.com/Tabish0007/delta-doctor)


### Agentic Data Analyst — grounded LLM data analysis

A local LLM agent that answers business questions over CSV datasets using sandboxed Python execution and a deterministic grounding gate. Numerical claims must be supported by actual execution output. Includes a reproducible evaluation harness with controlled sampling and evaluation-leakage prevention.

`Python` · `Pandas` · `Ollama` · `Local LLMs` · `Streamlit`

[GitHub repository](https://github.com/Tabish0007/agentic-data-analyst)


### Evolve Generalize — agent evaluation infrastructure

An evaluation harness for measuring cross-benchmark generalization in agent evolution frameworks. Compares baseline performance, cross-benchmark transfer, and target-task upper bounds, with local Ollama inference and an interactive Streamlit dashboard.

`Python` · `Streamlit` · `Ollama` · `LLM Evaluation`

[GitHub repository](https://github.com/Tabish0007/evolve-generalize)


### RobustML — adversarial machine learning

An end-to-end framework for benchmarking model robustness against adversarial attacks, evaluating defense strategies, and analyzing model behavior through an interactive Streamlit interface.

`Python` · `Machine Learning` · `Adversarial Testing` · `Streamlit`

[GitHub repository](https://github.com/Tabish0007/RobustML)

## Production Engineering

**BSH Hausgeräte (Bosch Group) · Data & Business Intelligence Engineering**

Cloud Infrastructure & FinOps Optimization: Led the technical migration of Apache Airflow DAG executions from EC2 to AWS ECS Fargate, scaling down worker nodes and decommissioning idle resources to sustainably reduce monthly cloud operating costs by ~58% (from €3,000 to €1,270).
• End-to-End Platform Engineering (DQNS): Independently architected, developed, and deployed a modular Data Quality Notification System (DQNS) using Python, SQL, Apache Airflow, AWS Redshift, and SAP Datasphere to automate pipeline monitoring and proactive incident management.
• Production Pipeline Observability: Integrated automated Level-1 and Level-2 infrastructure and data quality validations across 40+ production Apache Airflow DAGs and 30+ SAP Datasphere task chains, ensuring high data reliability across enterprise analytics workflows.
• Cross-Functional Architecture & Documentation: Collaborated across platform engineering teams (AWS, SAP Datasphere) and data owners to drive requirements engineering, manage Jira backlogs (Epics, User Stories), and author comprehensive technical documentation across Confluence.
• Enterprise Analytics Delivery: Engineered, tested, and maintained production data solutions supporting high-volume Direct-to-Consumer (D2C) and Order-turnover-analysis OTA) analytics use cases..

**Ignitus · Machine Learning Engineering**

Designed ML deployment architecture and automated infrastructure workflows for production model services.

- Designed and deployed nine FastAPI model services on Kubernetes, with MLflow experiment tracking and model registry.
- Implemented CI/CD and infrastructure automation, alongside drift and latency monitoring for deployed models.
- Automated GCP training pipelines for NLP recommendation models, reducing retraining time from five days to 14 hours.

**Grip Mechatronics · Machine Learning Engineering**

Developed computer-vision inspection systems and deployed ML inference across production edge infrastructure.

- Built C++/Python inspection algorithms for defect segmentation and sub-pixel alignment, achieving 96.4% precision at 45 FPS.
- Deployed 11 inference services on K3s across four edge nodes, with MLflow versioning and under 120 ms round-trip latency.

## What I Work With

| Area | Technologies |
|---|---|
| Languages | Python · SQL · Java · C++ · C · Jinja ·Rust  |
| Data Engineering | Apache Spark · PySpark · Airflow · Kafka · dbt · Delta Lake |
| Cloud & Infrastructure | AWS · GCP · Kubernetes · K3s · Docker · Terraform · Linux |
| ML & MLOps | PyTorch · TensorFlow · MLflow · FastAPI · Model Deployment · Model Monitoring |
| AI Systems | LLM Evaluation · RAG · Agentic Workflows · Ollama · Computer Vision |

**Certifications:** IBM Certified Hybrid Cloud Architect · Lean Six Sigma Black Belt · HackerRank Certified Software Engineer

---

**Portfolio:** https://tabishsayyed.shipstatic.com/  
**LinkedIn:** https://www.linkedin.com/in/tabish-9a033b200/  
**Hugging Face:** https://huggingface.co/SayyedTabish  
**Email:** tabishsayyed.302@gmail.com
