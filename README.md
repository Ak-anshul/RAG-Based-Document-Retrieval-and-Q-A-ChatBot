# RAG-Based-Document-Retrieval-and-Q-A-ChatBot

# Overview
RAG-Based Document Retrieval and Q&A ChatBot is a conversational AI system designed to efficiently retrieve information from documents and generate concise, context-aware responses to user queries. This project leverages Retrieval-Augmented Generation (RAG) to combine the best of two approaches: retrieving relevant documents from a corpus and using a powerful language model for generating answers.

By utilizing LangChain, Groq LLM, and Chroma for document storage, this chatbot can handle dynamic Q&A tasks with a high level of accuracy and relevance.

# Project Features
Retrieval-Augmented Generation (RAG): Combines document retrieval with a language generation model to provide highly accurate answers.
Context-Aware Conversations: Retains chat history to maintain coherent multi-turn dialogues.
Efficient Document Indexing and Retrieval: Uses Chroma and HuggingFace embeddings for quick and accurate retrieval of relevant documents.
Customizable and Scalable: Easily adapt the chatbot to any knowledge domain by providing different document sources.

# Technologies Used
LangChain: A library for building language model applications with features like document retrieval and conversational chains.
Groq LLM: A high-performance LLM (Large Language Model) used for natural language generation in this project.
HuggingFace Embeddings: Provides embeddings for document vectorization and similarity search.
Chroma: A fast, scalable vector database used for storing and retrieving document embeddings.
BeautifulSoup: Used for scraping content from web pages for document retrieval.

# How It Works

1. Document Retrieval
The project uses Chroma to store documents as vector embeddings. When a user asks a question, the system retrieves the most relevant document chunks based on similarity:

2. Question Answering with RAG
Once documents are retrieved, they are passed into the Groq LLM, which uses the retrieved content to generate an accurate response to the user's query:

3. History-Aware Conversations
The chatbot maintains a chat history, allowing users to ask follow-up questions that refer to previous ones. This ensures coherent conversations even when questions are fragmented.

# License
This project is licensed under the MIT License. 


