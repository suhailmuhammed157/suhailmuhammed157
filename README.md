# Hi, I'm Suhail 👋

Senior Backend Engineer (5+ years) building distributed systems and cloud-native backends in **Go**, **Rust**, **Python** and **TypeScript**. Lately I'm going deep on AI infrastructure.

## Expertise
- Distributed systems and event-driven architectures (Kafka, RabbitMQ, gRPC)
- Microservices on Kubernetes (AKS): migrations, GitOps CI/CD, observability
- Document-processing pipelines: OCR, IDP, email ingestion, background workers
- Backend performance: profiling, concurrency, database tuning
- AI infrastructure: RAG, vector search, MCP servers, LLM internals

## Production work
- **Document processing backend (Python/FastAPI, AKS):** ~15k IDP requests, ~10k OCR requests (Mistral) and 4-5k emails per day across 9 Zoho mailboxes. Background workers, PDF split/merge, external IDP calls. Replaced legacy MuleSoft flows. Closed source.
- **Warehouse label printing (Go):** concurrent service integrating Salesforce with Zebra printers, rendering custom ZPL templates for multi-location label printing.
- **ANPR truck tracking (containerized):** integrates ANPR cameras for automated truck identification and tracking.
- **Data archival pipeline (Go):** extracts TBs of historical data across 800+ Salesforce entities via SOQL, with PGP encryption end to end and idempotent PostgreSQL batch inserts. Closed source.
- **Node.js → Go/gRPC migration (AKS):** core services moved for lower latency and better isolation. Closed source.
- **CI/CD and security automation:** multi-stage Azure DevOps pipelines deploying to AKS via GitOps, with automated security scanning and dependency patching.

## Open-source projects
- **[Event Processing Platform]([link](https://github.com/suhailmuhammed157/event-platform))**: Go + Kafka, bounded worker pools, DLQs, idempotent batch writes, Prometheus/Grafana.
- **[MCP PostgreSQL Server]([link](https://github.com/suhailmuhammed157/mcp-postgres-server-rust))**: Rust MCP server with a read-only PostgreSQL interface for AI agents.
- **[Transformer from Scratch]([link](https://github.com/suhailmuhammed157/transformer-from-scratch))**: [language/framework] implementation covering attention, training and inference.
- **[RAG experiments]**: Qdrant + Ollama retrieval pipelines.

## Stack
**Languages:** Go · Rust · Python · TypeScript · SQL
**Backend:** gRPC · Kafka · RabbitMQ · Redis · WebSockets · FastAPI · NestJS
**Infra:** Docker · Kubernetes (AKS) · Azure DevOps · GitOps
**Data:** PostgreSQL · Redis · Qdrant · PgBouncer
**Observability:** Prometheus · Grafana · OpenTelemetry
**AI:** RAG · Ollama · MCP · LLMs

## Interests
Rust async internals · performance engineering · database internals · LLM internals · agent tooling
