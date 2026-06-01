<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=4000&pause=1000&color=00D4FF&center=true&vCenter=true&width=700&lines=AI+Researcher+→+AI+Engineer;ML+Systems+Engineer;Cloud+Infrastructure+Architect"  alt="typing animation">

<h2>Eric Borba</h2>

<p><em>I work where AI meets infrastructure — because great models need great plumbing.</em></p>

<a href="https://www.linkedin.com/in/ericborba"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
&nbsp;
<a href="mailto:eric.borba@gmail.com"><img src="https://img.shields.io/badge/eric.borba@gmail.com-D14836?style=flat&logo=gmail&logoColor=white"/></a>

</div>

---

## Quick Navigation
- [The Stack I'm Building](#the-stack-im-building)
- [Tech Stack](#tech-stack)
- [Featured Projects](#featured-projects)
- [Currently Learning](#currently)

---

## The Stack I'm Building

```
AI Research (PhD)  →  ML Engineering  →  Cloud Infrastructure for AI (AWS · Terraform)
```

Started in academia studying how systems fail — modeling SSD and HDD reliability at HPC scale, published at ARCS 2024, funded by the EU Horizon 2020 IO-SEA project. That work pushed me toward engineering resilient systems at scale.

I bridge the gap between research innovation and real-world deployment. My focus: building reliable, scalable systems that turn cutting-edge ML into production-grade infrastructure.

**The goal:** speak fluent ML *and* fluent AWS. Own the full path from research to production.

---

## Tech Stack

**AI & Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![ECS Fargate](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazon-ecs&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazon-rds&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logoColor=white)
![SNS](https://img.shields.io/badge/SNS-FF4F8B?style=flat-square&logo=amazon-aws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazon-aws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white)

---

## Featured Projects

### 🔬 [StorageFailurePredictor](https://github.com/EricBorba/StorageFailurePredictor)
ML-driven reliability analysis of SSD and HDD failure in HPC burst buffers. Uses SMART telemetry from ~1M Alibaba SSDs and Backblaze HDDs to dynamically predict Mean Time to Failure (MTTF) using Random Forest and LSTM models.

**Key Achievement:** Achieved 94% prediction accuracy, enabling proactive storage maintenance in high-performance computing environments.

`Python` `MongoDB` `scikit-learn` `XGBoost` `LSTM` — **Published at ARCS 2024 · EU Horizon 2020 IO-SEA**

---

### 🚗 [AccidentPredictorApp](https://github.com/EricBorba/AccidentPredictorApp)
End-to-end ML application that forecasts monthly road accident occurrences using Munich open traffic data. Trained, serialized, and served via a REST API — containerized with Docker and deployed to Heroku.

**Impact:** Demonstrates full ML pipeline: data preprocessing → model training → API serving → cloud deployment.

`Python` `Flask` `Docker` `Heroku` `scikit-learn`

---

### ☁️ [three-tier-architecture-aws](https://github.com/EricBorba/three-tier-architecture-aws)
Production-grade AWS 3-tier architecture: internet-facing ALB → 6 Node.js EC2 instances across 2 AZs with Auto Scaling → data tier. Custom VPC with network segmentation, security group chaining, and CloudWatch monitoring.

**Key Feature:** Fully automated scaling and high availability across multiple availability zones.

`AWS` `VPC` `EC2` `Auto Scaling` `ALB` `CloudWatch` `Terraform`

---

### 📊 [ce-project-2-instrumented-monitored-service](https://github.com/EricBorba/ce-project-2-instrumented-monitored-service)
Production-grade observability stack on AWS. Order processing API (FastAPI + ECS Fargate + RDS PostgreSQL) with structured JSON logging, 8 custom CloudWatch metrics, Golden Signal dashboards, tiered alerting via SNS, Lambda auto-remediation, FinOps cost monitoring, and AI-powered incident analysis using CrewAI. Entire infrastructure as code with Terraform, deployed via GitHub Actions CI/CD.

**Key Feature:** Three failure injection scenarios (error flood, high latency, CPU spike) — each diagnosed using the CloudWatch correlation view and remediated automatically by Lambda, closing the alert loop without human intervention.

`Python` `FastAPI` `ECS Fargate` `RDS PostgreSQL` `CloudWatch` `Lambda` `SNS` `Terraform` `GitHub Actions` `CrewAI`

---

## Currently

- 📜 Pursuing **HashiCorp Terraform Associate** certification
- 🔍 Deepening MLOps: model serving infrastructure, cost optimisation, distributed training on cloud
- 🏗️ Building production-ready AI services on AWS — containerised, observable, and infrastructure-as-code

---

## Let's Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/ericborba)
- 📧 [eric.borba@gmail.com](mailto:eric.borba@gmail.com)
- 🔗 Open to ML Engineering, MLOps, and Cloud Infrastructure roles

---

<div align="center">

![GitHub Stats](https://img.shields.io/badge/GitHub_Stats-Available-brightgreen?style=flat-square&logo=github)
&nbsp;
![Top Languages](https://img.shields.io/badge/Top_Languages-Available-blue?style=flat-square&logo=github)

</div>

---

<p align="center">Last updated: June 2026 | <a href="https://github.com/EricBorba?tab=repositories">View all repositories</a></p>
