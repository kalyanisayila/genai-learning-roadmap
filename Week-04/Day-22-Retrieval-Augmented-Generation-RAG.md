# Day 22 – Retrieval-Augmented Generation (RAG)

## What is RAG?

Retrieval-Augmented Generation (RAG) is a technique that combines information retrieval with a Large Language Model (LLM). Before generating an answer, it retrieves relevant information from external documents or databases.


## Why RAG?

- Reduces hallucinations
- Provides up-to-date information
- Uses private or company-specific data
- Improves answer accuracy


## How RAG Works

1. User asks a question.
2. The question is converted into an embedding.
3. A vector database searches for similar documents.
4. Relevant documents are retrieved.
5. The documents are sent to the LLM.
6. The LLM generates the final answer.

## Components

- Embedding Model
- Vector Database
- Retriever
- Large Language Model (LLM)

## Popular Vector Databases

- FAISS
- ChromaDB
- Pinecone
- Weaviate

## Example

**Question:** What is our company's leave policy?

Without RAG:
The model may not know the answer.

With RAG:
The chatbot retrieves the HR policy document and generates an accurate response.


## Advantages

- Accurate responses
- Less hallucination
- Supports private knowledge
- Easy to update information

## Interview Questions

### 1. What is RAG?

RAG combines document retrieval with an LLM to generate accurate answers.

### 2. Why is RAG important?

It improves accuracy and enables the model to use external knowledge.

### 3. Name two vector databases.

FAISS and ChromaDB.


## Key Takeaways

- RAG = Retrieval + Generation
- Uses external knowledge before answering
- Reduces hallucinations
- Improves AI chatbot performance
