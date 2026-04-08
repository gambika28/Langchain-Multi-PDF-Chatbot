# LangChain-Multi-PDF-Chatbot

This project is a conversational AI application that allows users to **upload multiple PDF files and ask questions** based on their content. It uses **LangChain, Google Gemini (Generative AI), and FAISS** to retrieve relevant information and generate accurate answers.

# Features

Upload multiple PDF documents
Extract and process text from PDFs
Split text into chunks for better retrieval
Store embeddings using FAISS vector database
Ask questions and get context-based answers
Uses Google Gemini for intelligent responses

# Tech Stack

Python
Streamlit
LangChain
Google Generative AI (Gemini)
FAISS (Vector Database)
PyPDF2

# Project Workflow

Upload PDF files
Extract text from PDFs
Split text into chunks
Convert text into embeddings
Store embeddings in FAISS
User asks a question
Retrieve relevant chunks using similarity search
Generate answer using Gemini model

# How It Works

The application processes uploaded PDFs and converts them into vector embeddings. When a user asks a question, the system retrieves the most relevant text chunks and passes them to the Gemini model to generate a response based on context.

# Installation

```bash id="code004"
git clone https://github.com/your-username/langchain-multi-pdf-chatbot.git
cd langchain-multi-pdf-chatbot
pip install -r requirements.txt
```

# Setup Environment Variables

Create a `.env` file and add your API key:

```bash id="code005"
GOOGLE_API_KEY=your_api_key_here
```

# Run the Application

```bash id="code006"
streamlit run app.py
```

# Usage

Upload one or more PDF files
Click on "Submit & Process"
Ask questions in the input box
Get answers based on PDF content

# Dependencies

streamlit
google-generativeai
python-dotenv
langchain
PyPDF2
faiss-cpu
langchain_google_genai

# Future Improvements

Add chat history memory
Improve UI/UX
Support more file formats (Word, TXT)
Deploy on cloud platforms

# Conclusion

This project demonstrates how Retrieval-Augmented Generation (RAG) can be used to build intelligent document-based chat systems using LangChain and Gemini.
