MulDoc

Introducing the MultiPDF Chat AI App! 🚀 Seamlessly engage in conversations with multiple PDFs using Langchain, Google Gemini Pro, and FAISS Vector DB. Effortlessly deploy with Streamlit for an enhanced PDF experience. Get instant and accurate responses powered by the incredible Google Gemini OpenSource language model. 📚💬 Revolutionize your PDF interactions now! 🔥✨

📝 Overview

The MulDoc is a cutting-edge Streamlit-based web application designed for interactive conversations with a chatbot. Upload multiple PDF documents, extract text information, and train the chatbot using this content. Engage in real-time conversations with the chatbot and transform your PDF experience.

📢 Run on Streamlit Cloud

Launch App On Streamlit

💻 Demo:

Demo 1: Chatbot Output

🎯 How It Works:

MultiPDF Chat App Diagram

The application follows these steps to provide responses to your questions:

PDF Loading : Reads multiple PDF documents, extracting their text content.
Text Chunking : Divides the extracted text into smaller, manageable chunks.
Language Model : Utilizes a language model to generate vector representations (embeddings) of text chunks.
Similarity Matching : Compares your question with text chunks, identifying the most semantically similar ones.
Response Generation : Selected chunks are passed to the language model, generating a response based on relevant PDF content.
Demo 2: Chatbot Output

🎯 Key Features

Adaptive Chunking: Utilizes Sliding Window Chunking, dynamically adjusting window size and position for RAG, balancing fine-grained and coarse-grained data access based on data complexity and context.
Multi-Document Conversational QA: Supports both simple and multi-hop queries across multiple documents, breaking the single-document limitation.
File Compatibility: Handles both PDF and TXT file formats.
LLM Model Compatibility: Supports Google Gemini Pro, OpenAI GPT 3, Anthropic Claude, Llama2, and other open-source LLMs.
Demo 3: Chatbot Output

🌟 Requirements

Streamlit: A Python library for building web applications with interactive elements.
google-generativeai: Provides generative AI capabilities for chatbots and virtual agents. Used for content generation, dialogue agents, summarization, and classification systems.
python-dotenv: Loads environment variables from a .env file, storing configuration settings and sensitive information.
langchain: Custom library for natural language processing tasks, including conversational retrieval, text splitting, embeddings, vector stores, chat models, and memory.
PyPDF2: Library for reading and manipulating PDF files in Python. Useful for handling PDF manipulation in a multipdf chatbot.
faiss-cpu: FAISS (Facebook AI Similarity Search) library for efficient similarity search, machine learning embeddings, information retrieval, content-based filtering, and clustering of dense vectors.
langchain_google_genai: Integration between LangChain and Google’s generative-ai SDK, extracting textual data from PDFs and generating accurate responses.
Demo 4: Chatbot Output
