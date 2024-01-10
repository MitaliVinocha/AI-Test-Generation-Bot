AI Test Generation Bot
Introduction
________________________________________
The MultiPDF Chat App is a Python application that allows us to chat with multiple PDF documents. We can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs.

How It Works
________________________________________

 
The application follows these steps to provide responses to your questions:
1.	PDF Loading: The app reads multiple PDF documents and extracts their text content.
2.	Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.
3.	Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.
4.	Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.
5.	Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.

Dependencies and Installation
________________________________________
To install the MultiPDF Chat App, please follow these steps:
Install streamlit , pypdf2, langchain, python-dotenv, FAISS, huggingface_hub

Usage
________________________________________
To use the MultiPDF Chat App, follow these steps:
1.	Ensure that you have installed the required dependencies and added the OpenAI API key to the .env file.
2.	Run the main.py file using the Streamlit CLI. Execute the following command:
3.	streamlit run app.py
4.	The application will launch in your default web browser, displaying the user interface.
5.	Load multiple PDF documents into the app by following the provided instructions.
6.	Ask questions in natural language about the loaded PDFs using the chat interface.
