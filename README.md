CERBERUS

AI-Powered SOC Enrichment & Correlation Engine
Overview

Cerberus is an AI-driven SOC enrichment and correlation platform designed to improve alert triage accuracy and reduce analyst workload.

The system ingests security alerts, correlates related events using shared entities (IOCs, users, hosts, processes), and applies LLM-powered, playbook-driven analysis with Retrieval-Augmented Generation (RAG) to produce analyst-ready investigation summaries and response recommendations.

Core Capabilities

- Real-time ingestion and normalization of security alerts

- Entity-based alert correlation to identify recurring and multi-stage attack activity

- LLM-driven analysis aligned with SOC investigation playbooks

- RAG-based enrichment using internal playbooks and threat intelligence

- Analyst-ready outputs designed for SIEM/SOAR escalation and automation

Technology Stack (High Level)

- Backend: Python

- API Layer: FastAPI

- Data Validation: Pydantic

- Application Server: Uvicorn

- Persistence: SQL-based storage (via ORM)

- AI/LLM: OpenAI APIs

- Knowledge Retrieval: Retrieval-Augmented Generation (RAG)

This public repository contains architecture and design documentation only.
The full production codebase is private.

📧 For code access or further discussion, please reach out via email: raja.cyborg@gmail.com
