# ChromaDb-QnA-on-Private-Documents-RAG-
A Retrieval-Augmented Generation (RAG) system built with LangChain and ChromaDB for document-based question answering with conversational memory.
Overview
This pipeline processes PDF documents, creates vector embeddings, and enables conversational Q&A with context retention. It's specifically designed for financial psychology content but can be adapted for any domain.

Architecture
Document → Chunking → Embeddings → ChromaDB → Retrieval → LLM → Response
                                        ↑
                                   Conversation Memory
Features

Document Processing: PDF loading and intelligent chunking
Vector Storage: ChromaDB for efficient similarity search
Conversational Memory: Maintains chat history across questions
Custom Prompts: Specialized prompts for domain expertise
Flexible Retrieval: Configurable similarity search parameters
