# Multimodal RAG

Multimodal Retrieval-Augmented Generation (RAG) implementation for querying PDF documents containing text, tables, and images using semantic search and LLMs.

## Tech Stack
- Python
- LangChain
- Pinecone (vector store)
- Hugging Face (embeddings)
- Groq (LLM inference)


## Pipeline

```text
PDF → Extraction → Processing → Embeddings → Pinecone
                                                |
User Query → Retriever → Relevant Context → LLM → Response
```
