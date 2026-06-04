# Dynamic Knowledge Base Chatbot Project

## Overview

This project implements a chatbot capable of dynamically expanding its knowledge base from PDF documents. The chatbot uses LangChain, ChromaDB, Ollama Embeddings, and Streamlit to retrieve information from uploaded PDFs and answer user queries.

## Features

* Reads PDF documents from the data source.
* Splits documents into chunks for efficient retrieval.
* Generates embeddings using Ollama.
* Stores embeddings in ChromaDB vector database.
* Dynamically updates the knowledge base when new PDFs are added.
* Provides a Streamlit-based chatbot interface.

## Project Structure

dynamic-knowledge-base-chatbot-project1

├── app.py

├── chatbot.py

├── updater.py

├── requirements.txt

├── Practicum 1.pdf

└── README.md

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Update the vector database:
   python updater.py

3. Run the chatbot:
   streamlit run app.py

## Expected Outcome

The chatbot automatically incorporates new information from PDF sources into its vector database and uses the updated knowledge base to answer user queries.

