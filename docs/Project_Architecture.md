# System Architecture

## Data Flow

```
Knowledge Base
        │
        ▼
Document Chunking
        │
        ▼
Sentence Transformer Embeddings
        │
        ▼
ChromaDB Vector Database
        │
        ▼
Semantic Search
        │
        ▼
Question Answering Model
        │
        ▼
Grounded Response
```

## Components

### Knowledge Base

Eight customer support documents containing information about Learnexity.

### Chunking

Documents are split into overlapping chunks to preserve context.

### Embeddings

Sentence Transformers convert each chunk into a numerical vector.

### Vector Database

ChromaDB stores vectors for efficient semantic retrieval.

### Retrieval

Top-k relevant chunks are retrieved based on cosine similarity.

### Generation

A Hugging Face Question Answering model extracts answers from retrieved context.

### Response

Responses include confidence scores and source attribution.
