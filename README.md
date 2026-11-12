# Hi, I'm Tôn Thất Gia Huy

Data Engineering-focused developer in Ho Chi Minh City. I work on data pipelines and data-backed systems with an emphasis on lineage, data quality, recoverability, and evidence-backed claims.

> **Let's build a data path that survives the unhappy path.**

[Portfolio](https://tonthatgiahuy16.github.io/) · [LinkedIn](https://www.linkedin.com/in/ton-that-gia-huy/) · [Email](mailto:tonthatgiahuy160505@gmail.com)

## Featured projects

### [RetailPulse](https://github.com/tonthatgiahuy16/RETAILPULSE)

A data engineering and decision-analytics project using the UCI Online Retail II dataset.

- PostgreSQL pipeline with raw, staging, warehouse, and mart layers, plus a migration ledger, reconciliation gates, dbt contracts, and read-only BI semantic views.
- In-repository DAG runner for task dependencies, bounded retry/backoff, downstream skipping, JSON run history, and an optional failure webhook.
- Local Power BI Project (PBIP) source for semantic-model validation and temporal model backtesting, including a historical model-evaluation page.

### [CloudMentor AI](https://github.com/tonthatgiahuy16/CloudMentor-AI)

A personal document-data lifecycle project for evidence-grounded retrieval.

- **Multi-format ingestion pipeline** for PDF, UTF-8 TXT, and DOCX, preserving page-, line-, and paragraph-level source metadata.
- **PostgreSQL document registry and lifecycle**, with local or MinIO canonical-source storage and a rebuildable Chroma derived index.
- **Recovery and consistency controls** for duplicate protection, stale-ingestion recovery, bounded reconciliation repair, and controlled local-to-MinIO migration.

### [OpsBrain](https://github.com/tonthatgiahuy16/OpsBrain)

An evidence-first knowledge infrastructure prototype for IT operations knowledge.

- Verified baseline: Markdown frontmatter validation, canonical content hashing, immutable PostgreSQL document versions, lifecycle audit storage, and approval-driven reindex jobs.
- Chunk-only reindex worker with bounded delayed retry, persisted lease fencing, and expired-lease reclaim.
- Out of current scope: retrieval, complete ACL enforcement, citations, Obsidian integration, and deployment.

## Engineering focus

- Keep the system of record and derived data boundary explicit.
- Preserve identifiers and source lineage across pipeline stages.
- Design duplicate handling, retry, reconciliation, and recovery.
- Separate implementation, recorded evidence, and target architecture.

## Core stack

Python · SQL · PostgreSQL · dbt · FastAPI · Docker · MinIO · Power BI · Git

Open to Data Engineering, Data Platform, and data-intensive Backend internship or entry-level opportunities in Ho Chi Minh City.
