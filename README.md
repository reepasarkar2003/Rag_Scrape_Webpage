# Rag_Scrape_Webpage


# RAG Pipeline for Course Information Bot

A Retrieval-Augmented Generation (RAG) implementation that creates an AI assistant capable of answering questions about course information by scraping website data and using vector database retrieval.

## Overview

This project demonstrates how to build a RAG pipeline that:
- Scrapes course information from a website
- Processes and chunks the data
- Stores embeddings in a vector database (ChromaDB)
- Retrieves relevant context for user queries
- Generates accurate answers using OpenAI's LLM

## Architecture
User Query → Vector DB Retrieval → Context Augmentation → LLM Generation → Response


## Key Features

- **Web Scraping**: Automatically extracts course information from websites
- **Intelligent Chunking**: Splits content with overlap to preserve context
- **RAG Pipeline**: Enhances LLM responses with retrieved context
  
