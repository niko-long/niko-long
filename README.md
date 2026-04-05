  # Xiaolong Song

  **Data Engineer / Analytics Engineer** — based in the Netherlands

  Currently on the Digital Innovation Team at Zehnder Group, building data
  pipelines, internal AI tooling, and leading AI adoption training across
  departments.

  Dual Master's in Statistics & Data Science + Civil Engineering. Transitioned
  from infrastructure engineering to data infrastructure.

  ## What I work on

  **Data Engineering**
  - Designed and maintained automated ingestion pipelines
  data from 6+ European sources (REST APIs, file downloads), with
  transformation in Python, storage in Azure SQL, and a Streamlit
  front-end for stakeholder access.
  - Migrated SAP procurement data pipelines from
  QlikSense to PySpark on Microsoft Fabric, redesigning join logic and
  incremental load strategy, with CI/CD via Azure DevOps.
  - Built an event-driven Azure Function that monitors mailboxes via Microsoft
  Graph API, extracts and validates CSV attachments, and loads them into the
  data platform — replacing a manual upload workflow.

  **AI & Automation**
  - Exploring AI agent architectures for internal business process automation —
  prototyping tool-use patterns, prompt engineering strategies, and integration
  with existing data infrastructure.
  - Developed and delivered hands-on training sessions on AI-assisted workflows
  (Claude, ChatGPT, Microsoft Copilot) for non-technical colleagues, including
  custom instruction design and accuracy validation techniques.

  ## Selected Project

  **NL Transport Pulse**
  End-to-end Dutch transport reliability pipeline built as a portfolio data
  engineering project.

  - Designed a multimodal pipeline integrating NS rail disruption/departure
  data and NDW road traffic data.
  - Provisioned cloud infrastructure with Terraform on GCP, using GCS as the
  raw data lake and BigQuery as the warehouse.
  - Orchestrated ingestion workflows in Airflow and modeled downstream datasets
  with dbt.
  - Built the project to demonstrate practical data engineering concerns:
  idempotent loads, partitioned raw ingestion, schema management, data quality
  checks, and reproducible local setup with Docker.
  - Focus area: connecting rail disruptions with nearby road traffic signals to
  explore multimodal reliability patterns in the Netherlands.

  ## Tech stack

  ```text
  Languages:      Python, SQL, Java, R
  Data:           PySpark, Azure SQL, Microsoft Fabric, Delta Lake, BigQuery,
  dbt
  Cloud & Infra:  Azure Functions, Azure DevOps, Docker, Terraform, GCP
  Tools:          Streamlit, Airflow, Git, Microsoft Graph API
  Currently:      CS61B (Data Structures & Algorithms)

  ## Contact

  xiaolong.song93@gmail.com
