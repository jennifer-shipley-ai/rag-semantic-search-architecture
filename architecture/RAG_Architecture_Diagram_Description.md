# RAG Architecture Diagram (Description)

Use this description to recreate a diagram in PowerPoint, draw.io, or Lucidchart.

---

## Diagram Components

### 1. User Layer
- Chat UI
- Application
- API client

### 2. Embedding Model
- Converts text → vector
- Used for semantic similarity

### 3. Vector Store / Index
- FAISS, Pinecone, Azure AI Search, etc.
- Stores embeddings
- Supports similarity search

### 4. Document Store
- PDFs
- Knowledge bases
- SharePoint
- Databases

### 5. Retrieval Layer
- Top‑K search
- Filters
- Governance rules

### 6. LLM Layer
- GPT model
- Uses retrieved context
- Generates grounded responses

### 7. Monitoring & Governance
- Logging
- Drift detection
- Access control
- Responsible AI checks

---

## Diagram Layout (Text Version)

