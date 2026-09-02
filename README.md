<h1 align="center">Hi, I'm Tôn Thất Gia Huy</h1>

<p align="center">
  Final-year Data Science student focused on Backend and Data Engineering.
</p>

<p align="center">
  I build Python APIs and data pipelines, with an emphasis on traceable data flows, measurable results, and honest documentation.
</p>

<p align="center">
  <a href="https://tonthatgiahuy16.github.io">Portfolio</a> •
  <a href="https://www.linkedin.com/in/ton-that-gia-huy/">LinkedIn</a> •
  <a href="mailto:tonthatgiahuy160505@gmail.com">Email</a>
</p>

## Selected projects

### [CloudMentor AI](https://github.com/tonthatgiahuy16/CloudMentor-AI)

An in-progress FastAPI and RAG prototype that turns uploaded PDFs into traceable, source-grounded answers.

- Built an explicit **Extract → Transform → Chunk → Embed → Index** ingestion workflow.
- Preserved document, page, source, and chunk metadata through ingestion and retrieval.
- Used Chroma as a rebuildable vector index and created PostgreSQL/Alembic groundwork for document lifecycle records.
- Added isolated pytest coverage for ingestion, retrieval orchestration, schemas, and upload validation, with GitHub Actions running the suite on every push.

**Technologies:** Python, FastAPI, PostgreSQL, Alembic, Chroma, RAG

### [Social Media Sentiment Big Data Pipeline](https://github.com/tonthatgiahuy16/social-media-sentiment-bigdata-pipeline)

A coursework prototype for batch processing and simulated streaming in a local Docker Compose environment.

- Processed the Sentiment140 dataset of approximately **1.6 million tweets** with HDFS and PySpark.
- Created cleaning, feature-engineering, model-training, and Parquet storage stages.
- Recorded a storage reduction from **238 MB to 79 MB** and a local throughput benchmark from **222 to 1,176 records/second** in the coursework environment.
- Implemented a separate Kafka and Spark Structured Streaming demonstration using synthetic messages.

**Technologies:** Python, PySpark, HDFS, Kafka, MongoDB, FastAPI, Docker

## Technical focus

| Area | Technologies |
| --- | --- |
| Core | Python, SQL, Git |
| Backend and databases | FastAPI, REST APIs, PostgreSQL, Alembic |
| Data processing | PySpark, Parquet, Docker |
| Project exposure | Kafka, Airflow, HDFS, MongoDB, Chroma |

## Current focus

- Expanding CloudMentor integration tests across PostgreSQL, Chroma, embedding, and LLM boundaries.
- Completing PostgreSQL document-lifecycle integration.
- Improving backend reliability and reproducible local data workflows.

## Availability

Based in Ho Chi Minh City and open to **Backend and Data Engineering Intern/Fresher opportunities**.
