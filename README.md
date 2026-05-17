# AI Systems Engineering

Learning AI systems by building production-grade projects from scratch.

This repository documents my journey from full-stack developer to AI systems engineer by building real-world AI infrastructure and RAG systems.

The goal is NOT to build toy chatbots.

The goal is to deeply understand:
- RAG architecture
- vector databases
- embeddings
- retrieval failures
- chunking strategies
- hallucination
- hybrid search
- reranking
- memory systems
- latency optimization
- AI observability
- evaluation pipelines
- agent workflows
- production deployment

---

# Current Main Project

## AI Incident Copilot

An AI-powered DevOps incident investigation system that analyzes:
- Kubernetes logs
- Docker logs
- CI/CD failures
- incident reports
- monitoring alerts
- internal documentation

Features:
- semantic search
- hybrid retrieval
- reranking
- citation grounding
- hallucination reduction
- streaming responses
- observability dashboards

---

# Tech Stack

## Frontend
- Next.js
- TypeScript
- Tailwind

## Backend
- Node.js
- NestJS
- FastAPI

## AI Stack
- OpenAI
- Sentence Transformers
- pgvector
- Qdrant
- LangChain
- LlamaIndex

## Infra
- Docker
- Kubernetes
- Redis
- Kafka

---

# Repository Structure

```bash
apps/
  frontend/
  api/
  ai-service/

packages/
  shared/

infra/
  docker/
  kubernetes/

experiments/
  chunking/
  embeddings/
  reranking/
  evaluation/

docs/
  architecture/
  learnings/
