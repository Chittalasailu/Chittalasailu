<div align="center">

# CHITTALA SAILU

Software Engineer · Python · Backend · AI/ML

Software engineer building APIs, data pipelines, and AI-integrated applications.

[Projects](#featured-projects) · [Skills](#technical-skills) · [LinkedIn](https://www.linkedin.com/in/chittalasailu/) · [Email](mailto:chittalasailu02@gmail.com)

</div>

---

## About

I'm a software engineer focused on backend systems, building REST APIs, data pipelines, and AI-integrated applications. I primarily work with Python and FastAPI, with experience across relational and graph databases and React-based frontends.

My projects range from AI and data analytics platforms to backend services and developer tools. I enjoy building practical systems where APIs, data, and AI work together to solve real problems.

## Featured Projects

### [ai-intelligence-ingestion-pipeline](https://github.com/Chittalasailu/ai-intelligence-ingestion-pipeline)

Async data pipeline that collects AI-industry information — startups, products, research papers, news, and jobs — from public sources and turns it into structured, deduplicated records. Built around a multi-provider LLM client that falls back across providers on rate limits or payload errors, and an entity-resolution layer that merges duplicate records using fuzzy matching with a tuned similarity threshold. Every record is validated against a domain-specific schema before being persisted.

**Tech:** Python · asyncio · Pydantic · SQLAlchemy · PostgreSQL · pytest

**Highlights:** Async processing · Schema validation · Entity resolution · LLM fallback

[View Repository →](https://github.com/Chittalasailu/ai-intelligence-ingestion-pipeline)

### [AI-Powered-Data-Analytics-Platform](https://github.com/Chittalasailu/AI-Powered-Data-Analytics-Platform)

End-to-end data platform covering ingestion, cleansing, transformation, and model training on top of PySpark and Delta Lake. Raw data is ingested against an explicit schema, cleaned through deduplication, outlier handling, and null imputation, then aggregated into Delta tables before feeding a scikit-learn clustering and classification stage. Results are served through a Streamlit dashboard, and the pipeline can be run stage-by-stage from the command line.

**Tech:** Python · PySpark · Delta Lake · scikit-learn · Streamlit · pytest

**Highlights:** ETL pipeline · Feature engineering · Machine learning · Data visualization

[View Repository →](https://github.com/Chittalasailu/AI-Powered-Data-Analytics-Platform)

### [SmartExpenseTracker](https://github.com/Chittalasailu/SmartExpenseTracker)

Full-stack personal expense tracker with a FastAPI backend and a React frontend. The API handles expense creation, filtering, and persistence through SQLAlchemy against PostgreSQL, while the frontend visualizes spending with category and monthly-trend charts and supports exporting the current view as a PDF report. Backend and frontend are deployed separately on Render and Vercel.

**Tech:** Python · FastAPI · PostgreSQL · SQLAlchemy · React · Chart.js

**Highlights:** REST API · Data visualization · PDF export · Deployment

[View Repository →](https://github.com/Chittalasailu/SmartExpenseTracker)

### [scalable-url-shortener](https://github.com/Chittalasailu/scalable-url-shortener)

Backend URL-shortening service built around reliable short-code generation, persistent storage, and request protection. Short codes are generated with Python's `secrets` module and retried against a database uniqueness constraint on collision, while a Redis-backed rate limiter enforces request limits through an atomic Lua script. The backend is organized in layers — API routes, services, repositories, and models — with Alembic managing schema migrations.

**Tech:** Python · FastAPI · PostgreSQL · Redis · SQLAlchemy · Alembic · pytest

**Highlights:** REST API design · Rate limiting · Caching · Database migrations · Testing

[View Repository →](https://github.com/Chittalasailu/scalable-url-shortener)

### [AI-Resume-Analyzer](https://github.com/Chittalasailu/AI-Resume-Analyzer)

Full-stack resume analysis tool with JWT-based authentication and a FastAPI backend that parses uploaded PDF/DOCX resumes and analyzes them using the Gemini API. User accounts and analysis history are persisted through SQLAlchemy, with endpoints covering signup, login, upload, and history retrieval. The React frontend presents results as an interactive dashboard with exportable reports.

**Tech:** Python · FastAPI · PostgreSQL · SQLAlchemy · React · Gemini API · pytest

**Highlights:** Authentication · LLM integration · File parsing · Testing

[View Repository →](https://github.com/Chittalasailu/AI-Resume-Analyzer)

### [blast-radius](https://github.com/Chittalasailu/blast-radius)

Dependency-risk explorer built on a graph database, designed to analyze how vulnerabilities propagate through transitive dependencies and identify affected applications. It uses Cypher-based dependency analysis with a Fastify backend and a React frontend for exploring dependency relationships and vulnerability impact.

**Tech:** JavaScript · Fastify · Neo4j · Cypher · React

**Highlights:** Graph database · Cypher queries · Dependency analysis · Data visualization

[View Repository →](https://github.com/Chittalasailu/blast-radius)

## Technical Skills

**Languages:** Python, JavaScript, SQL

**Backend & APIs:** FastAPI, Express, Fastify, REST APIs, Pydantic, JWT, asyncio, Rate Limiting

**Frontend:** React, Vite, Chart.js, Axios

**Databases & ORM:** PostgreSQL, Redis, Neo4j, Cypher, SQLAlchemy, Alembic

**AI / ML / Data:** Gemini API, PySpark, Delta Lake, scikit-learn, ETL, Entity Resolution, Schema Validation

**DevOps & Deployment:** Docker, GitHub Actions, Vercel, Render

**Testing:** pytest

---

<div align="center">

## Connect

[LinkedIn](https://www.linkedin.com/in/chittalasailu/) · [Email](mailto:chittalasailu02@gmail.com) · [GitHub](https://github.com/Chittalasailu)

</div>
