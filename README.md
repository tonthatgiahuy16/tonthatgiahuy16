# Hi, I'm Tôn Thất Gia Huy

Data Engineering-focused developer in Ho Chi Minh City. I build data pipelines and data-backed applications with an emphasis on lineage, data quality, recoverability, and evidence-backed claims.

> **Let's build a data path that survives the unhappy path.**

[Portfolio](https://tonthatgiahuy16.github.io/) · [LinkedIn](https://www.linkedin.com/in/ton-that-gia-huy/) · [Email](mailto:tonthatgiahuy160505@gmail.com)

## Featured projects

### [CloudMentor AI](https://github.com/tonthatgiahuy16/CloudMentor-AI)

A recoverable, subject-scoped document-data lifecycle for RAG.

- Ingests PDF, UTF-8 TXT, and DOCX with source metadata and location-aware citations.
- PostgreSQL owns document and lifecycle state; canonical sources use local storage or MinIO; Chroma is a rebuildable derived index.
- Includes duplicate-safe ingestion, retry and restore flows, reconciliation, and controlled local-to-MinIO migration.

### [RetailPulse](https://github.com/tonthatgiahuy16/RETAILPULSE)

A reproducible batch data engineering and analytics project using the UCI Online Retail II dataset.

- Tracks an immutable source snapshot through PostgreSQL raw, staging, warehouse, and mart layers.
- Adds lineage, reconciliation and data-quality gates, dbt contracts, and a read-only BI semantic layer.
- Includes a Power BI Project report. Its pages were verified locally in Power BI Desktop; no hosted report or scheduled refresh is claimed.

### [OpsBrain](https://github.com/tonthatgiahuy16/OpsBrain)

An evidence-first knowledge infrastructure prototype for investigating IT operations incidents.

- Current implementation includes validated Markdown ingestion, canonical hashing, immutable PostgreSQL document versions, audit-event storage, deterministic chunk builds, and approval-driven reindex jobs with retries and lease fencing.
- Retrieval, complete ACL enforcement, Ollama generation, citations, and Obsidian integration remain target architecture, not implemented capabilities.

## Engineering focus

- Keep the system of record and derived data boundary explicit.
- Preserve identifiers and source lineage across pipeline stages.
- Design duplicate handling, retry, reconciliation, and recovery.
- Separate implementation, recorded evidence, and target architecture.

## Core stack

Python · SQL · PostgreSQL · dbt · PySpark · FastAPI · Docker · MinIO · Power BI · Git

Open to Data Engineering, Data Platform, and data-intensive Backend internship or entry-level opportunities in Ho Chi Minh City.
