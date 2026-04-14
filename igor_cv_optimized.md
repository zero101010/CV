# Igor Araújo

**Senior DevOps Engineer | Platform Engineer | MLOps**

Brasília, Brazil | igotaraujo97@gmail.com | +55 61 99333-6790
[LinkedIn](https://www.linkedin.com/in/igor-sousa-0b95a0145/)

---

## Professional Summary

Senior DevOps Engineer with 7+ years building cloud-native infrastructure on AWS and GCP. Specialized in Kubernetes, Terraform, and CI/CD automation. Currently focused on MLOps — fine-tuning LLMs, RAG pipelines, and GPU infrastructure optimization across multi-cloud environments.

---

## Core Competencies

| Category | Technologies & Skills |
|---|---|
| **Cloud Platforms** | AWS (6 yrs), GCP (4 yrs), Azure (1 yr), Multi-Cloud Architecture |
| **Container Orchestration** | Kubernetes — EKS, GKE (5 yrs), Docker (6 yrs), Helm Charts, Container Security |
| **Infrastructure as Code** | Terraform (4 yrs), CloudFormation, GitOps, Configuration Management |
| **CI/CD & Automation** | GitLab CI/CD (5 yrs), GitHub Actions (3 yrs), CircleCI, ArgoCD, Pipeline Optimization |
| **Programming** | Python (6 yrs), Golang/Go (4 yrs), JavaScript (3 yrs), Node.js (3 yrs), Bash (5 yrs) |
| **MLOps & AI** | LLM Fine-Tuning, RAG Pipelines, Vector Databases — Qdrant, Ollama, Runpod, ML Pipeline Orchestration, Model Serving, Embeddings (1 yr) |
| **Observability & Monitoring** | Prometheus (3 yrs), Grafana (3 yrs), Datadog (3 yrs), SLI/SLO/SLA Monitoring, Alerting, Distributed Tracing |
| **Service Mesh & Networking** | Istio (2 yrs), gRPC, Microservices Architecture, API Gateway |
| **Databases** | MySQL (4 yrs), MongoDB (3 yrs), PostgreSQL, Redis |
| **Streaming & Messaging** | Apache Kafka (1 yr), Event-Driven Architecture |
| **OS & Administration** | Linux Administration (7 yrs), System Reliability, Performance Tuning |
| **Version Control & Collaboration** | Git (7 yrs), GitHub, GitLab, Code Review, Agile/Scrum |
| **Practices** | DevSecOps, Site Reliability Engineering (SRE), Platform Engineering, Cloud-Native Development, Serverless, High Availability, Disaster Recovery, Cost Optimization |

---

## Professional Experience

### Turing — DevOps Engineer / MLOps Engineer
**September 2025 – Present**

- Architected the entire LLM fine-tuning infrastructure from scratch, designing GPU provisioning, environment setup, and data persistence layers for ML researchers and trainers
- Reduced GPU infrastructure costs by 80% (from $100K+/month to ~$20K/month) by evaluating multi-cloud providers and migrating workloads from GCP to Runpod
- Built automated idle-instance management to stop unused GPU instances, preventing unnecessary spend on expensive compute resources
- Designed persistent data layer integrating Runpod instances with GCP Cloud Storage, ensuring researchers never lost training data, with simplified GitHub-based authentication for instance access
- Created purpose-built Docker images pre-configured with ML packages and dependencies for GPU instances, reducing environment provisioning time from ~1 day (GCP) to 8 minutes (Runpod)
- Design and implement CI/CD pipelines to deploy containerized applications on Google Kubernetes Engine (GKE) and other GCP services using Terraform and GitOps practices

### GoodRx — DevOps Engineer / MLOps Engineer
**February 2023 – September 2025**

- Built and maintained an ephemeral environment platform for 100+ microservices, reducing environment provisioning time from few hours to few minutes and accelerating developer feedback loops
- Designed and implemented a Retrieval-Augmented Generation (RAG) pipeline using Python, Qdrant (vector database), and LLM APIs to ingest, embed, and query document data — enabling accurate, data-driven Q&A capabilities for internal teams
- Engineered reproducible ML environments with Docker and Infrastructure as Code, eliminating manual configuration and reducing experiment setup time by 10%
- Orchestrated distributed LLM fine-tuning workloads across multi-cloud providers (AWS, GCP, Runpod), optimizing for high availability and achieving reduction in infrastructure costs
- Monitored system health and model performance using Datadog dashboards, alerts, and custom metrics

### Cyral (USA) — DevOps Engineer
**January 2022 – January 2023**

- Built "Rosie," an internal platform tool that interacted with the Kubernetes API to automatically provision isolated namespaces with all microservices for each developer upon PR creation, with Slack notifications for lifecycle management
- Rosie automated namespace cleanup by notifying developers via Slack when environments were idle, allowing them to extend or delete — saving ~$700/month in unused cluster resources that developers previously forgot to clean up
- Abstracted Kubernetes complexity from developers who were unfamiliar with it, enabling them to test in production-like environments without needing to manage infrastructure directly
- Authored and maintained Kubernetes manifests and Helm charts for deploying Cyral's data security platform across customer environments
- Developed and maintained Infrastructure as Code (Terraform) modules, including a custom Terraform provider written in Golang using gRPC
- Provided hands-on support to enterprise clients for infrastructure configuration, deployment troubleshooting, and ongoing maintenance of Cyral's data management platform

### IBM — Solution Architect
**August 2021 – January 2022**

- Designed cloud-native solutions following DevOps and SRE best practices for enterprise clients on AWS
- Delivered Proof of Concept (POC) implementations using Kubernetes, Java Spring Boot, Golang, Terraform, and AWS services to validate technical feasibility
- Collaborated directly with clients to assess technical challenges and architect tailored infrastructure solutions aligned with business requirements

### Monprospecteur (Canada) — DevOps Engineer (Contract)
**May 2020 – August 2021**

- Led end-to-end infrastructure migration to Kubernetes, containerizing applications with Docker and deploying on managed Kubernetes clusters
- Implemented CI/CD pipelines using GitHub Actions, automating build, test, and deployment workflows for 10+ services
- Applied development expertise to refactor application architecture and establish DevOps best practices across the engineering team

### Mcontigo (Spain) — DevOps Engineer
**August 2020 – August 2021**

- Managed and optimized CI/CD pipelines using GitLab CI, reducing build times by [X]% through caching strategies and pipeline parallelization
- Implemented GitOps workflows using Golang-based automation scripts and Helm charts to manage deployments across multiple environments (dev, staging, production)
- Deployed and managed Istio service mesh for traffic management, observability, and security across microservices
- Built comprehensive monitoring and alerting stack with Prometheus and Grafana, establishing SLIs/SLOs for critical services

### Probono — Software Engineer
**January 2019 – August 2020**

- Developed full-stack applications using React, Node.js, and Python, including data scraping pipelines for automated data collection
- Deployed and managed applications on AWS (ECS, EC2, S3) using Docker containers and CI/CD pipelines with CircleCI
- Championed DevOps culture adoption within the engineering team, introducing containerization and automated deployment practices

---

## Education

- **B.Sc. Software Engineering** — Universidade de Brasília (UnB), 2015 – 2023
- **English as a Second Language (ESL)** — Canadian College, Vancouver, 2022

---

## Certifications

<!-- TODO: Add any certifications you have or are pursuing. High-value ones for your profile:
- AWS Certified Solutions Architect (Associate or Professional)
- AWS Certified DevOps Engineer - Professional
- Google Cloud Professional Cloud DevOps Engineer
- Certified Kubernetes Administrator (CKA)
- HashiCorp Certified: Terraform Associate
-->

---

## Languages

- **Portuguese** — Native
- **English** — Professional proficiency

---

<!--
LINKEDIN KEYWORD OPTIMIZATION NOTES:
The following keywords are embedded throughout this CV to match common recruiter Boolean searches:

Titles: DevOps Engineer, Platform Engineer, MLOps Engineer, Site Reliability Engineer, SRE, Solution Architect, Cloud Engineer
Cloud: AWS, GCP, Azure, Multi-Cloud, Cloud-Native, Serverless
Containers: Kubernetes, Docker, EKS, GKE, Helm, Container Orchestration
IaC: Terraform, Infrastructure as Code, GitOps, CloudFormation
CI/CD: GitHub Actions, GitLab CI, CircleCI, ArgoCD, Pipeline
Languages: Python, Golang, Go, JavaScript, Node.js, Bash
ML/AI: MLOps, LLM, RAG, Fine-Tuning, Vector Database, Embeddings, Model Serving
Monitoring: Prometheus, Grafana, Datadog, Observability, SLI, SLO, SLA
Practices: DevSecOps, SRE, Microservices, High Availability, Disaster Recovery, Agile
Databases: MySQL, MongoDB, PostgreSQL, Redis
Other: Kafka, Istio, gRPC, Service Mesh, API Gateway, Git
-->
