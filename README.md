# Multimodal RAG

Multimodal Retrieval-Augmented Generation (RAG) implementation for querying PDF documents containing text, tables, and images using semantic search and LLMs.

## Tech Stack
- Python
- LangChain
- Pinecone (vector store)
- Hugging Face (embeddings)
- Groq (LLM inference)

## Architecture

```text
PDF Documents
      |
      v
Text, Tables & Image Extraction
      |
      v
Content Processing & Summarization
      |
      v
Embedding Generation
      |
      v
Pinecone Vector Database
      |
      v
Semantic Search & Retrieval
      |
      v
LLM Response Generation
```
