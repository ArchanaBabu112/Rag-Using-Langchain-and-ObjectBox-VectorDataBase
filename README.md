Retrieval-Augmented Generation (RAG) enhances response accuracy by combining retrieval-based models and generation-based models. 

This project leverages:
ObjectBox Vector Database: A high-performance vector database for storing and retrieving document embeddings quickly and accurately.

LangChain: A powerful language processing library for loading, processing, and querying text data, used here to process PDF documents and generate responses. Features PDF Document Loading:
Load and preprocess text from multiple PDF documents in a specified directory.

Text Splitting and Embedding:
Split text into chunks using RecursiveCharacterTextSplitter. Generate vector embeddings for each chunk with pre-trained language models.

Vector Storage and Retrieval:
Store embeddings in ObjectBox Vector Database. Retrieve relevant document chunks based on user queries efficiently.

Question Answering:
Process user queries and generate accurate answers using the RAG model. Combine retrieved document chunks with language generation models for contextually relevant responses. 
