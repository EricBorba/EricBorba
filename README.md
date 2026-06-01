<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3500&pause=1000&color=00D4FF&center=true&vCenter=true&width=760&lines=AI+Researcher+%E2%86%92+AI+Engineer;ML+Systems+Engineer;Cloud+Infrastructure+for+AI" alt="Eric Borba — AI Engineer & Cloud Infrastructure" />

<h1>Eric Borba</h1>

<strong><em>I work where AI meets infrastructure — because great models need great plumbing.</em></strong>

<br>

<a href="https://www.linkedin.com/in/ericborba"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
&nbsp;
<a href="mailto:eric.borba@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
&nbsp;
<img src="https://img.shields.io/github/followers/EricBorba?style=for-the-badge&logo=github&logoColor=white&color=00D4FF&labelColor=0d1117" alt="GitHub followers" />

</div>

---

## The Stack I'm Building

```text
AI Research (PhD)  →  ML Engineering  →  Cloud Infrastructure for AI
                                         (AWS · Terraform · Observability)
```

Started in academia studying **how systems fail** — modeling SSD and HDD reliability at HPC scale, published at **ARCS 2024**, funded by the **EU Horizon 2020 IO-SEA** project. That work pushed me toward engineering resilient systems at scale.

Today I bridge research and deployment: building reliable, **observable**, scalable systems that turn cutting-edge ML into production-grade infrastructure.

> **The goal:** speak fluent ML *and* fluent AWS — own the full path from research to production.

---

## Tech Stack

**AI &amp; Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A5F?style=flat-square&logoColor=white)

**Cloud &amp; Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![ECS Fargate](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazon-ecs&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazon-rds&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazon-aws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white)

**Languages, Data &amp; Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Featured Projects

### 📊 [Instrumented &amp; Monitored Cloud Service](https://github.com/EricBorba/ce-project-2-instrumented-monitored-service)
Production-grade **observability** stack on AWS. An order-processing API (FastAPI · ECS Fargate · RDS) with structured JSON logging, 8 custom CloudWatch metrics, Golden-Signal dashboards, tiered SNS alerting, **Lambda auto-remediation**, FinOps cost monitoring, and AI-powered incident analysis via CrewAI — all infrastructure-as-code with Terraform and shipped through GitHub Actions.

> **Highlight:** three injected failure scenarios (error flood, high latency, CPU spike), each diagnosed from the CloudWatch correlation view and remediated automatically by Lambda — closing the alert loop with no human in it.

`FastAPI` `ECS Fargate` `RDS` `CloudWatch` `Lambda` `SNS` `Terraform` `GitHub Actions` `CrewAI`

---

### ☁️ [Three-Tier Architecture on AWS](https://github.com/EricBorba/three-tier-architecture-aws)
Production-grade AWS 3-tier architecture: internet-facing ALB → 6 Node.js EC2 instances across 2 AZs with Auto Scaling → isolated data tier. Custom VPC with network segmentation, security-group chaining, and CloudWatch monitoring.

> **Highlight:** fully automated scaling and high availability across multiple availability zones.

`AWS` `VPC` `EC2` `Auto Scaling` `ALB` `CloudWatch` `Terraform`

---

### 🔬 [Storage Failure Predictor](https://github.com/EricBorba/StorageFailurePredictor)
ML-driven reliability analysis of SSD and HDD failure in HPC burst buffers. Uses SMART telemetry from ~1M Alibaba SSDs and Backblaze HDDs to predict Mean Time to Failure with Random Forest and LSTM models.

> **Highlight:** 94% prediction accuracy — published at **ARCS 2024**, funded by **EU Horizon 2020 IO-SEA**.

`Python` `MongoDB` `scikit-learn` `XGBoost` `LSTM`

---

### 🚗 [Accident Predictor App](https://github.com/EricBorba/AccidentPredictorApp)
End-to-end ML application forecasting monthly road-accident occurrences from Munich open traffic data — trained, serialized, and served via a REST API, containerized with Docker and deployed to the cloud.

> **Highlight:** the full ML pipeline in one repo — preprocessing → training → API serving → deployment.

`Python` `Flask` `Docker` `scikit-learn`

---

## GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/EricBorba/EricBorba/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/EricBorba/EricBorba/output/github-snake.svg" />
  <img alt="Contribution graph snake animation" src="https://raw.githubusercontent.com/EricBorba/EricBorba/output/github-snake.svg" />
</picture>

</div>

---

## Currently

- 📜 Pursuing the **HashiCorp Terraform Associate** certification
- 🏗️ Building production-ready AI services on AWS — containerized, observable, infrastructure-as-code
- 🔍 Going deeper on **MLOps**: model serving, cost optimization, and distributed training on cloud

---

<div align="center">

**Open to ML Engineering · MLOps · Cloud Infrastructure roles**

<sub>Last updated June 2026 · <a href="https://github.com/EricBorba?tab=repositories">View all repositories →</a></sub>

</div>
