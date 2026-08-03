<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./light.svg">
  <img alt="Vamsitha Gude — Data & AI Platform Engineer" src="./dark.svg">
</picture>

<div align="center">

[![Email](https://img.shields.io/badge/Email-vamsitha7%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vamsitha7@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vamsitha-gude/)
[![GitHub](https://img.shields.io/badge/GitHub-vamsitha07-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vamsitha07)

![AWS Certified Solutions Architect Associate](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Microsoft Certified Azure Data Engineer Associate](https://img.shields.io/badge/Azure-Data_Engineer_Associate-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

</div>

---

## About

I build the full path from raw data to a decision: the cloud infrastructure that
lands and governs it, the self-service platforms that run on top of that
infrastructure, the ML/AI systems built on those platforms, and the analysis that
turns all of it into something a business can act on. Four years in, most of my work
has been taking something messy and manual — financial transaction data, cloud
infrastructure spread across dozens of accounts, decades-old healthcare records — and
turning it into something governed, queryable, and self-serviceable.

I think of a data platform as one system, not four handoffs. The same instincts that
make an ingestion pipeline correct — idempotency, lineage, quality as a gate rather
than an afterthought — are what make a feature store trustworthy, a model reproducible,
and an experiment readable. I like owning problems end to end, and I pick up whatever
is blocking the platform even when it sits outside my formal scope.

**Currently:** Data Engineer @ Vanguard — Chief Technology Office & Chief Data Analytics
Office, Data Engineering and Enterprise Data Storage.

---

## What I work on — the whole data-to-AI value chain

```
  raw data  ──▶  cloud infra  ──▶  data platform  ──▶  ML / AI systems  ──▶  decisions
              (ingest, govern)   (self-serve, catalog)  (features, models)   (analysis, A/B)
```

I move across this chain rather than sitting at one point on it. The projects below are
labeled by where on the chain they live, so you can find your part at a glance.

---

## Skills by discipline

**Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

Redshift (provisioned + serverless, data sharing), S3, Glue, Lambda, Step Functions,
Kinesis, DynamoDB, Athena, EventBridge, SNS/SQS, IAM, KMS, Secrets Manager, CloudTrail,
CloudWatch, X-Ray · ADLS Gen2 · multi-account / multi-region delivery · IAM cross-account
role design.

**Data Engineering & Orchestration**
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)
![Iceberg](https://img.shields.io/badge/Apache_Iceberg-1B75BB?style=flat-square&logo=apache&logoColor=white)

Step Functions & declarative pipeline orchestration (branching, parallel fan-out,
retries, structured failure handling), streaming CDC (Debezium, Kafka, change data feeds,
Auto CDC), SCD Type 1 & 2, medallion architecture, Autoloader, Databricks Asset Bundles,
Parquet internals, compaction / snapshot expiry / time travel, incremental ingestion.
Comfortable extending into Airflow and dbt.

**Platform & Systems Engineering**
![Data Catalog](https://img.shields.io/badge/Unity_Catalog_·_Glue-1B75BB?style=flat-square&logo=databricks&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![OPA](https://img.shields.io/badge/Open_Policy_Agent-7D9199?style=flat-square&logo=openpolicyagent&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

Self-service platform design, audit catalogs & lineage, data-quality control loops
(circuit breakers, failure counters, self-healing), observability & notification services,
GitOps / IaC-driven onboarding, policy-as-code (OPA/Rego), CI/CD (GitHub Actions, Jenkins,
CodePipeline, Azure DevOps), pytest / mypy / ruff / tox quality gates.

**ML / AI & MLOps**
![Bedrock](https://img.shields.io/badge/Amazon_Bedrock-01A88D?style=flat-square&logo=amazonaws&logoColor=white)
![LangChain](https://img.shields.io/badge/LLM_·_RAG-000000?style=flat-square&logo=chainlink&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

LLM agents (ReAct, tool calling, structured extraction) on Amazon Bedrock / Claude,
RAG patterns, feature stores feeding predictive models, model packaging & serving
(FastAPI + Docker), experiment tracking (MLflow). Building out the served-model half of
the pipeline in the projects below.

**Data Science & Statistics**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

Curated datasets & feature stores for predictive modeling and reporting, data profiling
& validation frameworks, analytical SQL, experimentation and A/B analysis, translating a
statistical result into a written business recommendation.

---

## Portfolio map

Featured work, tagged by where it sits on the raw-data → decision chain. Items marked
🏢 are production systems I built at work (described here, code proprietary); items marked
🛠 are public repos you can open and run.

| Project | Cloud/Infra | Data Eng | Platform | ML/AI | Data Sci |
|---|:--:|:--:|:--:|:--:|:--:|
| 🏢 Self-service data-sharing platform (AWS, Step Functions, OPA) | ✅ | ✅ | ✅ | | |
| 🏢 Continuous data-consistency engine (self-healing, circuit breakers) | ✅ | ✅ | ✅ | | |
| 🏢 CDC → lakehouse ingestion (Databricks, Auto CDC, SCD2) | | ✅ | | | |
| 🏢 NL-to-config LLM agent (Bedrock, Claude, ReAct + tool calling) | | | ✅ | ✅ | |
| 🏢 Healthcare mainframe → governed schemas (Azure Databricks) | ✅ | ✅ | | | ✅ |
| 🛠 *Public builds landing soon — see "Currently building" below* | | | | | |

---

## Currently building (public repos, in progress)

- **cloud-lakehouse-iac** — Terraform-provisioned ingestion pipeline into Snowflake/BigQuery,
  orchestrated with Airflow + dbt. *(Cloud + Data Engineering)*
- **mlops-pipeline** — train → track in MLflow → serve via FastAPI + Docker, consuming the
  lakehouse project's features. *(Data-to-ML bridge)*
- **rag-service** — retrieval-augmented Q&A with a working API and evals. *(Applied AI)*
- **experiment-analysis** — A/B test + causal-inference notebook ending in a written
  business recommendation. *(Data Science)*

---

## Education & Certifications

- **M.S., Computer Information Systems** — Colorado State University
- **B.Tech** — Vignan Foundation for Science, Technology and Research
- **AWS Certified Solutions Architect – Associate**
- **Microsoft Certified: Azure Data Engineer Associate**

---

## Open to

Cloud Data Engineering · Data Platform Engineering · AI/ML Engineering · Data Science —
roles that use more than one link in the chain above. Based in the US.

<div align="center">

**Building data-to-AI platforms people can serve themselves from.**

</div>
