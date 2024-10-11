## RAG-Based-Document-Retrieval-and-Q-A-ChatBot

#Overview
RAG-Based Document Retrieval and Q&A ChatBot is a conversational AI system designed to efficiently retrieve information from documents and generate concise, context-aware responses to user queries. This project leverages Retrieval-Augmented Generation (RAG) to combine the best of two approaches: retrieving relevant documents from a corpus and using a powerful language model for generating answers.

By utilizing LangChain, Groq LLM, and Chroma for document storage, this chatbot can handle dynamic Q&A tasks with a high level of accuracy and relevance.

Project Features
Retrieval-Augmented Generation (RAG): Combines document retrieval with a language generation model to provide highly accurate answers.
Context-Aware Conversations: Retains chat history to maintain coherent multi-turn dialogues.
Efficient Document Indexing and Retrieval: Uses Chroma and HuggingFace embeddings for quick and accurate retrieval of relevant documents.
Customizable and Scalable: Easily adapt the chatbot to any knowledge domain by providing different document sources.
Technologies Used
LangChain: A library for building language model applications with features like document retrieval and conversational chains.
Groq LLM: A high-performance LLM (Large Language Model) used for natural language generation in this project.
HuggingFace Embeddings: Provides embeddings for document vectorization and similarity search.
Chroma: A fast, scalable vector database used for storing and retrieving document embeddings.
BeautifulSoup: Used for scraping content from web pages for document retrieval.
