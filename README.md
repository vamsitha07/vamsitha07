<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./light.svg">
  <img alt="Vamsitha Gude — Data Engineer" src="./dark.svg">
</picture>

<div align="center">

[![Email](https://img.shields.io/badge/Email-vamsitha7%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vamsitha7@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN-SLUG/)
[![GitHub](https://img.shields.io/badge/GitHub-vamsitha07-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vamsitha07)

![AWS Certified Solutions Architect Associate](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Microsoft Certified Azure Data Engineer Associate](https://img.shields.io/badge/Azure-Data_Engineer_Associate-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Location](https://img.shields.io/badge/Location-Malvern,_PA-7C3AED?style=flat-square&logo=googlemaps&logoColor=white)

</div>

---

## About

Data engineer with four years of experience building the pipelines other teams
quietly depend on. Most of my work has been taking something messy and manual —
financial transaction data, cloud infrastructure spread across dozens of accounts,
decades-old healthcare records — and turning it into something governed and
queryable that people can serve themselves from.

I like owning problems end to end, I care a lot about data quality being an
engineering practice rather than someone checking spreadsheets, and I tend to pick
up whatever is blocking the platform even when it sits outside my formal scope.

**Currently:** Cloud Data Engineer @ Vanguard — Chief Technology Office & Chief Data Analytics Office, Data Engineering
and Enterprise Data Storage.

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Data & Lakehouse**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD4?style=flat-square&logo=delta&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache_Iceberg-1B75BB?style=flat-square&logo=apache&logoColor=white)
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

**AWS**

![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Glue](https://img.shields.io/badge/Glue-8C4FFF?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Step Functions](https://img.shields.io/badge/Step_Functions-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Bedrock](https://img.shields.io/badge/Bedrock-01A88D?style=flat-square&logo=amazonaws&logoColor=white)

**Platform & DevOps**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Open Policy Agent](https://img.shields.io/badge/OPA-7D9199?style=flat-square&logo=openpolicyagent&logoColor=white)

---

## What I've Built

**Self-service data sharing platform** — replaced a manual, ticket-driven provisioning
process that took two to three business days with a code-driven pipeline that finishes
in under five minutes at better than 99% execution success, with a full audit trail and
roughly a 60–70% drop in total cost of ownership. Three orchestrated workflows
(producer, consumer, teardown) that branch on validation state and fan out in parallel,
cutting multi-consumer runs by three to five times. Governance runs as code through
Open Policy Agent. Rolled out 11+ microservices across engineering, staging, and
production.

**Continuous data consistency engine** — detects replication drift between clusters on
an hourly schedule and alerts the owning team within minutes. Metadata-driven,
bidirectional comparison over a rolling window with deliberate overlap, plus a
self-healing control loop: async query tracking, skip and failure counters, and a
circuit breaker that stops the engine from hammering a broken table pair and resets
on the next healthy run.

**CDC to lakehouse ingestion** — declarative Auto CDC flow upserting change events into
SCD Type 2 tables with full history. Replaced roughly 200 lines of fragile hand-written
merge logic with about six lines of declarative pipeline code that correctly handles
out-of-order events, deletes, and idempotent reprocessing — fixing a correctness bug
where deleted records were silently staying marked as current.

**Iceberg operational playbook** — proved managed table optimizers work across account
boundaries (compacted a table from 600 small files to one with row count unchanged),
then wrote the firm's operational standard covering compaction, snapshot expiry, time
travel, rollback, and both delete modes.

---

## Current Focus

```text
Building:
  - Governed, self-service data platforms on AWS
  - Streaming CDC into lakehouse table formats
  - Data quality as an engineering practice, not a checklist

Exploring:
  - Apache Iceberg internals and cross-account catalog design
  - Declarative pipelines and Databricks Asset Bundles
  - LLM agents for structured platform configuration

Open to:
  - Senior Data Engineering and Data Platform roles
  - Lakehouse and streaming architecture work
```

---

## GitHub Analytics

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=vamsitha07&show_icons=true&theme=tokyonight&border_radius=10&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vamsitha07&layout=compact&theme=tokyonight&border_radius=10&langs_count=8)

</div>

---

## Education & Certifications

- **M.S., Computer Information Systems, Colorado State University**
- **Bachelors**, Vignan Foundation for Science, Technology and Research
- **AWS Certified Solutions Architect – Associate**
- **Microsoft Certified: Azure Data Engineer Associate**

---

<div align="center">

*Building data platforms people can serve themselves from.*

</div>
