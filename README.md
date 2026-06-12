# ShopMind AI

ShopMind AI is an AI-powered e-commerce assistant built using Retrieval-Augmented Generation (RAG). The system combines large language models with vector search to provide accurate and context-aware responses to shopping-related queries.

## Overview

The application enables users to ask natural language questions about products and receive intelligent responses based on retrieved information. By integrating a language model with a vector database, the assistant can understand user intent and generate relevant recommendations.

## Features

* Semantic product search
* Retrieval-Augmented Generation (RAG)
* Context-aware question answering
* Vector similarity search using ChromaDB
* LangChain-powered orchestration
* Llama 3.1 integration through Groq
* Hugging Face embeddings

## Technology Stack

* Python
* LangChain
* Llama 3.1
* Groq API
* ChromaDB
* Hugging Face Embeddings
* Google Colab

## Project Workflow

1. Load product data and documents.
2. Generate embeddings using Hugging Face models.
3. Store embeddings in ChromaDB.
4. Retrieve relevant information based on user queries.
5. Generate responses using Llama 3.1.
6. Return context-aware answers to the user.

## Installation

Clone the repository:

git clone https://github.com/Sriram624/ShopMind-AI-Assistant.git

Move into the project directory:

cd ShopMind-AI-Assistant

Install dependencies:

pip install -r requirements.txt

## Configuration

Create a `.env` file and add your Groq API key:

GROQ_API_KEY=your_api_key_here

## Usage

Open the notebook in Google Colab or Jupyter Notebook and run all cells in sequence.

The system will:

* Load the knowledge base
* Create embeddings
* Build the vector database
* Initialize the language model
* Start answering user queries

## Example Queries

* Recommend a laptop under ₹60,000
* Suggest a smartphone with a good camera
* Compare two products
* Recommend running shoes for beginners
* Find the best product for daily use

## Learning Outcomes

This project demonstrates practical implementation of:

* Retrieval-Augmented Generation
* Vector Databases
* Embedding Models
* Large Language Models
* Conversational AI
* Prompt Engineering

## Future Enhancements

* Real-time product catalog integration
* Personalized recommendations
* Review summarization
* Voice-based interaction
* Multi-modal search capabilities

## Author

Sriram B

Software Developer with interests in Artificial Intelligence, Machine Learning, and Full-Stack Development.
