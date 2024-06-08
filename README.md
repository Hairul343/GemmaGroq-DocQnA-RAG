# End-to-End Document Q&A RAG App

This repository contains an end-to-end application for document-based Question & Answering (Q&A) using Retrieval-Augmented Generation (RAG) with Gemma and Groq APIs.
![image](https://github.com/Hairul343/GemmaGroq-DocQnA-RAG/assets/140678940/0044239a-b157-4b45-b654-b999d2cb6c4e)


## Overview

The application allows users to ask questions about specific documents. It retrieves relevant context from the documents using the Gemma API and generates answers using the Groq API. The architecture includes:

- **Document Retrieval**: Using Gemma API to search and retrieve relevant documents.
- **Context Extraction**: Extracting relevant context from the retrieved documents.
- **Answer Generation**: Using Groq API to generate answers based on the extracted context.

## Features

- **FastAPI**: A modern, fast (high-performance), web framework for building APIs with Python 3.7+.
- **Gemma API Integration**: Retrieve and search documents.
- **Groq API Integration**: Generate answers from the provided context.
- **Modular Code Structure**: Easy to extend and maintain.
- **Unit Tests**: Ensuring code reliability and correctness.

## Getting Started
