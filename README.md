<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3500&pause=1000&color=00D4FF&center=true&vCenter=true&width=760&lines=AI+Cloud+Engineer;AIOps+%C2%B7+Observability+%C2%B7+FinOps+on+AWS;AI+Researcher+%E2%86%92+Engineer+%E2%86%92+Cloud" alt="Eric Borba — AI Cloud Engineer" />

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
AI Research (PhD)  →  ML / AI Engineering  →  Cloud Engineering + AIOps
                                              (AWS · Terraform · Observability · FinOps)
```

Started in academia studying **how systems fail** — modeling SSD and HDD reliability at HPC scale, published at **ARCS 2024**, funded by the **EU Horizon 2020 IO-SEA** project. That work pushed me toward engineering resilient systems at scale.

From there I shipped AI/ML systems to production, then completed the **Ironhack Cloud Engineering Bootcamp** to own the layer underneath them: **AWS** infrastructure-as-code, CI/CD, observability, security and FinOps. Today I build **AI-powered cloud platforms** — where AIOps agents don't just *watch* infrastructure, they **act** on it under a human-in-the-loop.

> **The goal:** a Cloud Engineer who speaks fluent **AWS** *and* fluent **AI** — owning the full path from research to production infrastructure.

---

## Tech Stack

**Cloud &amp; Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![ECS Fargate](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazon-ecs&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-8C4FFF?style=flat-square&logo=amazon-aws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazon-rds&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazon-aws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white)
![WAF](https://img.shields.io/badge/WAF-DD344C?style=flat-square&logo=amazon-aws&logoColor=white)

**AI &amp; Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Amazon_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A5F?style=flat-square&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Languages, Data &amp; Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Featured Projects

### 🤖 [AIOps Observability Platform](https://github.com/EricBorba/ce-capstone-aiops-observability-platform) &nbsp;·&nbsp; *Cloud Engineering Capstone*
A production AWS platform whose core value is an **intelligent operations layer**: CrewAI agents on **Amazon Bedrock** that analyze live infrastructure and take **supervised actions** on it under a **3-tier human-in-the-loop** trust model (analysis · autonomous non-prod · approval-gated). Built on full observability (structured logging, custom CloudWatch metrics, Golden-Signal dashboards, tiered alerting), edge security (CloudFront + WAF + GuardDuty + Config/CloudTrail), an Auth0-authenticated operator console, and FinOps cost controls — all **Terraform** IaC, shipped through **GitHub Actions** (OIDC, no static keys). Deployed and verified in `us-east-1` across 3 AZs.

> **Highlight:** a live operator console with **Approve / Reject** buttons — the human-in-the-loop, demoed end-to-end. ~$145/mo prod run-rate with deliberate FinOps trade-offs. &nbsp;🖥️ [**Live console**](https://d2dp4bm5fu76cq.cloudfront.net)

`Bedrock` `CrewAI` `ECS Fargate` `RDS` `CloudFront` `WAF` `CloudWatch` `Lambda` `Auth0` `Terraform` `GitHub Actions`

---

### ☁️ [Three-Tier Architecture on AWS](https://github.com/EricBorba/three-tier-architecture-aws)
Production-grade AWS 3-tier architecture: internet-facing ALB → 6 Node.js EC2 instances across 2 AZs with Auto Scaling → isolated data tier. Custom VPC with network segmentation, security-group chaining, and CloudWatch monitoring.

> **Highlight:** fully automated scaling and high availability across multiple availability zones.

`AWS` `VPC` `EC2` `Auto Scaling` `ALB` `CloudWatch` `Terraform`

---

### 📊 [Instrumented &amp; Monitored Cloud Service](https://github.com/EricBorba/ce-project-2-instrumented-monitored-service)
The observability foundation the capstone grew from. An order-processing API (FastAPI · ECS Fargate · RDS) with structured JSON logging, 8 custom CloudWatch metrics, Golden-Signal dashboards, tiered SNS alerting, **Lambda auto-remediation**, FinOps cost monitoring, and AI-powered incident analysis via CrewAI — all Terraform IaC, shipped through GitHub Actions.

> **Highlight:** three injected failure scenarios (error flood, high latency, CPU spike), each diagnosed from the CloudWatch correlation view and remediated automatically by Lambda — closing the alert loop with no human in it.

`FastAPI` `ECS Fargate` `RDS` `CloudWatch` `Lambda` `SNS` `Terraform` `CrewAI`

---

### 🔬 [Storage Failure Predictor](https://github.com/EricBorba/StorageFailurePredictor)
ML-driven reliability analysis of SSD and HDD failure in HPC burst buffers. Uses SMART telemetry from ~1M Alibaba SSDs and Backblaze HDDs to predict Mean Time to Failure with Random Forest and LSTM models.

> **Highlight:** 94% prediction accuracy — published at **ARCS 2024**, funded by **EU Horizon 2020 IO-SEA**.

`Python` `MongoDB` `scikit-learn` `XGBoost` `LSTM`

---

> 🧪 **Plus 30+ hands-on labs** from the Ironhack Cloud Engineering Bootcamp — Terraform &amp; GitOps workflows, FinOps cost optimization (EC2 scheduling −67%, VPC endpoints −$297/yr), and security &amp; compliance (CIS, WAF, Config, Vault). [Browse the `ce-` repos →](https://github.com/EricBorba?tab=repositories&q=ce-)

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

- 🎓 Completed the **Ironhack Cloud Engineering Bootcamp** — capstone: the AIOps Observability Platform above
- 📜 Preparing the **AWS Certified Cloud Practitioner** and **HashiCorp Terraform Associate** certifications
- 🏗️ Building production-ready AI services on AWS — containerized, observable, infrastructure-as-code
- 🔍 Going deeper on **AIOps, FinOps and MLOps**: agentic operations, cost optimization, and model serving on cloud

---

<div align="center">

**Open to Cloud Engineer · Cloud Ops · DevOps · AIOps roles — including internships**

<sub>Last updated June 2026 · <a href="https://github.com/EricBorba?tab=repositories">View all repositories →</a></sub>

</div>
