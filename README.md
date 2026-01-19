# RAG Workshop Demo Notebooks

## College Department RAG

This notebook demonstrates a basic Retrieval-Augmented Generation (RAG) system for answering questions about a fictional undergraduate department (DISE). It showcases the complete pipeline including document embedding using SentenceTransformers' `all-MiniLM-L6-v2` model, vector indexing with FAISS for fast similarity search, retrieval of relevant documents based on cosine similarity, and answer generation using Llama 3.1-8B through the HuggingFace Inference API. The implementation uses open-source technologies and provides free access without requiring local model downloads, making it ideal for educational purposes and understanding RAG fundamentals.

## Scholarships RAG

This notebook builds a practical RAG chatbot application for retrieving information about scholarships provided by the Government of India. It covers the end-to-end implementation including loading the scholarship dataset, chunking and splitting data for optimal retrieval, creating a vector database, generating embeddings for semantic search, encoding user queries with similarity scoring, and generating responses through an LLM to provide accurate scholarship information. The notebook serves as a hands-on example of applying RAG techniques to real-world government data, enabling users to query and discover relevant scholarship opportunities through natural language interactions.
