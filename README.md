# Hi, I'm Tôn Thất Gia Huy

Data Engineering and Backend candidate in Ho Chi Minh City. I build data pipelines and APIs around traceable lineage, explicit ownership, recoverable lifecycle workflows, and testable failure handling.

> **Let's build a data path that survives the unhappy path.**

[Portfolio](https://tonthatgiahuy16.github.io/) · [LinkedIn](https://www.linkedin.com/in/ton-that-gia-huy/) · [Email](mailto:tonthatgiahuy160505@gmail.com)

## Featured projects

### [CloudMentor AI](https://github.com/tonthatgiahuy16/CloudMentor-AI)

A recoverable document-data platform for subject-scoped RAG, built with FastAPI, React, PostgreSQL, Chroma, and MinIO.

- **Data foundation:** PostgreSQL owns document metadata and lifecycle state; canonical PDF, TXT, and DOCX sources are retained through local or MinIO storage; Chroma is a rebuildable derived index.
- **Reliability:** checksum validation, retry and recovery workflows, database-enforced concurrent duplicate protection, and dry-run-first PostgreSQL–Chroma reconciliation with bounded repair.
- **Verification:** GitHub Actions cover backend tests, frontend lint/build, container-backed MinIO recovery, and PostgreSQL concurrent ingestion.

### [OpsBrain](https://github.com/tonthatgiahuy16/OpsBrain)

An evidence-first knowledge infrastructure prototype for investigating IT incidents, developed through small, tested vertical slices.

- **Implemented baseline:** FastAPI, PostgreSQL with pgvector, versioned Markdown ingestion, frontmatter validation, canonical hashing, immutable version history, and ingestion-job constraints.
- **Data design:** PostgreSQL is the system of record; future chunks, embeddings, search indexes, and relationships are treated as rebuildable derived data.
- **Current boundary:** retrieval, ACL enforcement, Ollama generation, citations, and Obsidian integration remain target architecture until matching implementation and runtime evidence exist.

### [Social Media Sentiment Pipeline](https://github.com/tonthatgiahuy16/social-media-sentiment-bigdata-pipeline)

A coursework batch pipeline processing approximately 1.6 million Sentiment140 records with HDFS, PySpark, partitioned Parquet, Spark ML, and FastAPI with MongoDB. It also includes a separate Kafka streaming demonstration with synthetic messages and an Airflow scheduling prototype.

## Engineering focus

- Make the system of record and derived data boundary explicit.
- Preserve identifiers and source metadata across ingestion and retrieval.
- Design retries, reconciliation, and recovery before calling a pipeline reliable.
- Separate implemented behavior, recorded evidence, and target architecture.

## Core stack

Python · SQL · PostgreSQL · FastAPI · PySpark · Docker · MinIO · Git

Open to Data Engineering, Data Platform, and data-intensive Backend internship or entry-level opportunities in Ho Chi Minh City.
