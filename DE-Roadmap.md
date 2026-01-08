# Azure Data Engineer Roadmap (Working Professional – 2 hrs/day)

## Profile Context

- Background: MERN Stack Developer (3.4 yrs)
- Goal: Switch to **Azure Data Engineer**
- Constraint: 2 hours/day
- Focus: **Azure-only**, no analytics, no Spark dependency
- Market: India (AI-safe, enterprise-ready)

---

## Final Career Identity

**Backend Engineer specialized in Azure Data Platforms**

- AI-resilient
- High demand in India
- Strong long-term growth

---

## Core Technologies (What I Will Use)

### 1. Languages (Mandatory)

#### SQL

- Joins, CTEs, Window Functions
- Indexing & optimization
- Data modeling
- Warehousing queries (Azure SQL / Synapse)
- Used daily

#### Python

- ETL scripts
- API ingestion
- Data validation & transformation
- Logging, retries, error handling
- Memory-efficient processing
- Used daily

---

### 2. Orchestration

#### Apache Airflow

- Pipeline scheduling
- Dependency management
- Retry & failure handling
- Monitoring pipelines
- Controls **when & how** data flows

---

### 3. Azure Core Services (Mandatory)

#### Azure Data Lake Storage Gen2 (ADLS)

- Raw / processed / curated layers
- Scalable & low-cost storage
- Enterprise data lake architecture

#### Azure Blob Storage

- Landing zone for files
- CSV / JSON ingestion
- Initial raw data storage

#### Azure SQL Database

- Structured data storage
- Querying & transformations
- Downstream consumption

---

### 4. Data Movement

#### Azure Data Factory (ADF)

- Batch pipelines
- Copy activity
- Incremental loads
- Enterprise scheduling
- Error handling & retries
- Used by almost all Azure data teams

---

### 5. Data Warehousing (No Spark)

#### Azure Synapse (SQL Pools only)

- Large-scale querying
- Warehousing patterns
- Performance optimization
- Spark pools NOT required

---

### 6. Reliability & Production Skills

- Retry strategies
- Idempotent pipelines
- Logging
- Monitoring (basic Azure Monitor)
- Cost awareness
- Failure recovery mindset

---

## What I Will NOT Learn (Intentionally)

- Spark (optional later)
- Power BI
- Data Analytics / BI
- Machine Learning
- Data Science math
- Too many Azure services

Depth > Breadth

---

## Mental Architecture Model

Data Source (API / CSV / DB)
↓
Apache Airflow (orchestration)
↓
Azure Blob / ADLS (raw layer)
↓
Python ETL
↓
Azure SQL / Synapse
↓
Monitoring + Retry + Logs

---

## Learning Roadmap (6–8 Months)

### Phase 1 (Month 1–2): Foundations

- Advanced SQL
- Python for ETL
- Data modeling

### Phase 2 (Month 3): Azure Storage

- ADLS Gen2
- Blob Storage
- Azure SQL

### Phase 3 (Month 4): Azure Data Factory

- Pipelines
- Incremental loads
- Error handling

### Phase 4 (Month 5): Orchestration

- Apache Airflow
- Reliability & monitoring

### Phase 5 (Month 6): Warehousing

- Azure Synapse (SQL only)

### Phase 6 (Month 7–8): Production Readiness

- Monitoring
- Cost optimization
- Security basics
- Resume-grade projects

---

## Resume-Ready Projects

### Project 1: Batch Ingestion Pipeline

Public API
→ ADLS (raw)
→ Python ETL
→ Azure SQL
→ ADF scheduling

### Project 2: Incremental Enterprise Pipeline

CSV / API
→ ADLS (partitioned)
→ ADF incremental load
→ Synapse SQL
→ Monitoring + retry
