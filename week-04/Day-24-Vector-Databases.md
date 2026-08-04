# Day 24 – Vector Databases

## What is a Vector Database?

A Vector Database is a specialized database that stores vector embeddings and helps AI quickly find similar information using similarity search.

Instead of searching for exact words, it searches for similar meanings.


## Why Do We Need Vector Databases?

Large Language Models (LLMs) use embeddings to represent text as vectors.

A vector database stores these vectors and retrieves the most relevant information efficiently.

This is essential for applications like RAG, semantic search, and AI chatbots.


## How a Vector Database Works

1. Convert text into embeddings.
2. Store the embeddings in a vector database.
3. When a user asks a question, convert the question into an embedding.
4. Compare the question embedding with stored embeddings.
5. Retrieve the most similar documents.
6. Send them to the LLM to generate an answer.


## Popular Vector Databases

- FAISS
- ChromaDB
- Pinecone
- Weaviate
- Milvus
- Qdrant


## Applications

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- AI Chatbots
- Recommendation Systems
- Document Search
- Image Search


## Advantages

- Fast similarity search
- Handles millions of vectors
- Improves AI accuracy
- Supports real-time retrieval
- Easy integration with LLMs


## Limitations

- Requires embedding models
- More complex than traditional databases
- Performance depends on embedding quality


## Example

Suppose a company stores HR documents in a vector database.

Question:
> What is the leave policy?

The system:

1. Converts the question into an embedding.
2. Searches similar vectors.
3. Retrieves the HR policy document.
4. Sends it to the LLM.
5. Generates an accurate answer.


## Difference Between SQL Database and Vector Database

| SQL Database | Vector Database |
|--------------|-----------------|
| Stores rows and columns | Stores embeddings (vectors) |
| Searches exact values | Searches similar meanings |
| Used for structured data | Used for AI and semantic search |


## Interview Questions

### 1. What is a Vector Database?

A Vector Database stores embeddings and performs similarity search.

### 2. Why is it important in AI?

It helps retrieve relevant information quickly for LLMs.

### 3. Name four vector databases.

- FAISS
- ChromaDB
- Pinecone
- Weaviate

### 4. Where are vector databases used?

RAG, semantic search, chatbots, recommendation systems, and document retrieval.


## Key Takeaways

- Vector databases store embeddings.
- They perform similarity search instead of keyword search.
- They are a core component of RAG.
- Popular options include FAISS, ChromaDB, Pinecone, Weaviate, Milvus, and Qdrant.
