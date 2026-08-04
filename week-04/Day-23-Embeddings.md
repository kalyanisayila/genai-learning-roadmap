# Day 23 – Embeddings

## What are Embeddings?

Embeddings are numerical representations (vectors) of text, images, or other data. They help AI models understand the meaning and relationships between different pieces of information.

For example, the words **"car"** and **"automobile"** have similar meanings, so their embeddings are close to each other in vector space.


## Why are Embeddings Important?

- Capture the meaning of text
- Improve semantic search
- Help recommendation systems
- Support Retrieval-Augmented Generation (RAG)
- Used in chatbots and AI assistants

## How Embeddings Work

1. Input text is given to an embedding model.
2. The model converts the text into a vector (a list of numbers).
3. Similar texts produce similar vectors.
4. AI compares vectors to find related information.

## Example

Text:

"I love Python programming."

Embedding (Example):

[0.12, -0.45, 0.91, 0.33, ...]

The numbers themselves are not meaningful to humans, but AI uses them to compare similarity.


## Applications

- Semantic search
- Chatbots
- Recommendation systems
- Document search
- RAG applications
- Duplicate detection


## Popular Embedding Models

- OpenAI Embeddings
- Sentence Transformers
- BERT Embeddings
- Cohere Embeddings

## Advantages

- Understands meaning instead of exact words
- Improves search quality
- Fast similarity comparison
- Works well with vector databases


## Interview Questions

### 1. What is an embedding?

An embedding is a numerical vector representation of data that captures its meaning.

### 2. Why are embeddings used?

They help AI understand similarity between texts and improve search and retrieval.

### 3. Where are embeddings used?

Semantic search, recommendation systems, RAG, chatbots, and document retrieval.

### 4. What is a vector?

A vector is a list of numbers representing data in mathematical space.


## Key Takeaways

- Embeddings convert text into vectors.
- Similar meanings produce similar vectors.
- Embeddings power semantic search and RAG.
- Vector databases store embeddings for fast retrieval.
