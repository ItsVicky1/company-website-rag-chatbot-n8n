# company-website-rag-chatbot-n8n
AI-powered company website chatbot built with n8n using Google Drive, Pinecone vector database, and RAG to answer company and job-opening queries.


# Company Website RAG Chatbot with n8n

This project is a **Company Website RAG Chatbot** built with **n8n**.  
It is designed to help both **website visitors** and **job seekers** by answering questions from company knowledge stored in documents.

## Features

- Google Drive document ingestion
- PDF-based knowledge extraction
- Text chunking and embeddings generation
- Pinecone vector database integration
- RAG-based question answering
- Separate handling for:
  - company-related queries
  - job-opening and career-related queries
- Intent classification for website chat
- Professional fallback responses for unclear or unrelated questions

## Use Cases

This chatbot can answer questions about:

- company services
- technologies
- projects
- support
- general company information
- current job openings
- hiring details
- career opportunities

## Workflows Included

### 1. Vector Data Save Workflow
This workflow:
- checks Google Drive for files
- downloads documents
- adds metadata and categorizes them
- processes documents for embeddings
- stores vector data in Pinecone

### 2. Website Chatbot Workflow
This workflow:
- receives website visitor messages
- classifies intent
- routes the message properly
- retrieves relevant knowledge from Pinecone
- generates focused responses using RAG

## Tech Stack

- **n8n**
- **Google Drive**
- **Pinecone**
- **OpenAI Embeddings**
- **Groq Models**
- **RAG Architecture**

## Example Query Types

- What services does the company provide?
- What technologies do you use?
- Are there any current openings?
- Do you have internship opportunities?
- How can I apply?

## Future Improvements

- support for DOCX and TXT
- stronger metadata filtering
- better frontend chat widget integration
- deployment improvements for production use
- admin workflow for updating knowledge base

## Repository Purpose

This project demonstrates how to build a practical **AI-powered website chatbot** using workflow automation, vector search, and retrieval-augmented generation.

## Author

Built by Vikas Bhagwat
