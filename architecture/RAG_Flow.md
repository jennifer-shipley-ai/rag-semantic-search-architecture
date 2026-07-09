# RAG Retrieval Flow (PM-Level)

This document explains the end-to-end flow of Retrieval-Augmented Generation in a way that is accessible to program managers and business stakeholders.

---

## 1. User Query
A user asks a question or submits a prompt.

Example:
“Summarize our Q4 sales performance.”

---

## 2. Query Embedding
The system converts the query into a vector representation using an embedding model.

Purpose:
- Capture semantic meaning
- Enable similarity search

---

## 3. Vector Search
The embedding is compared against a vector index containing organizational documents.

The system retrieves:
- Most relevant chunks
- Based on semantic similarity
- From approved data sources

---

## 4. Context Assembly
The retrieved chunks are packaged into a context window.

PM considerations:
- Chunk size
- Relevance thresholds
- Governance filters

---

## 5. LLM Generation
The LLM generates an answer using:
- The user’s query
- The retrieved context

This reduces hallucinations and ensures grounded responses.

---

## 6. Output Delivery
The final answer is returned to the user through:
- Chat interface
- API
- Application UI

---

## 7. Monitoring & Governance
PMs ensure:
- Retrieval accuracy
- Data freshness
- Responsible AI compliance
- Drift detection

---

This flow provides a clear, repeatable structure for enterprise RAG implementations.
