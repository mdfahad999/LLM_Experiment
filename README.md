# LLM_Experiment

# Corrective RAG Agent with Langgraph
A sophisticated Retrieval-Augmented Generation (RAG) system that implements a corrective multi-stage workflow using LangGraph. This system combines document retrieval, relevance grading, query transformation, and web search to provide comprehensive and accurate responses.


## Features

- **Smart Document Retrieval**: Uses Qdrant vector store for efficient document retrieval
- **Document Relevance Grading**: Employs llama-3.3-70b-versatile to assess document relevance
- **Query Transformation**: Improves search results by optimizing queries when needed
- **Web Search Fallback**: Uses Tavily API for web search when local documents aren't sufficient
- **Multi-Model Approach**: Combines all-MiniLM-L6-v2 embeddings and llama-3.3-70b-versatile for different tasks
- **Interactive UI**: Built with Streamlit for easy document upload and querying
