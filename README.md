# Multi-PDF Chatbot using AutoGPTQ and LangChain

This project implements a chatbot capable of answering questions based on multiple PDF documents using AutoGPTQ for text generation and LangChain for document retrieval and processing.<br>

The chatbot leverages several technologies and libraries:<br>
1. AutoGPTQ: Utilized for text generation based on prompts.<br>
2. LangChain: Used for document loading, embedding, retrieval, and text processing.<br>
3. PyPDF2: A library for reading PDF files.<br>
4. pdf2image: A tool for converting PDF pages to images.<br>
5. Chroma Vector Store: Provides fast approximate nearest neighbor search for document retrieval.<br>
6. Hugging Face Transformers: Provides pre-trained language models for text generation.<br>

## Features
i. Chat with the bot using natural language questions.<br>
ii. Retrieve answers from multiple PDF documents.<br>
iii. Supports various types of questions, including revenue, profit, and estimation queries.<br>
