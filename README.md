# Csv-based-Retrieval-Augmented-Generation-RAG-

CSV-Based Chatbot with RAG (Retrieval Augmented Generation)
This project is a chatbot that uses a CSV file as its knowledge base. It allows users to load CSV data, generate a Chroma vector store for similarity search, and retrieve relevant information from the CSV content using a Retrieval Augmented Generation (RAG) approach. The chatbot can then answer questions based on the CSV data by leveraging Mistral AI's large language model.




Features
CSV Data Loading: Load any CSV file and clean the text data for better querying.
Chroma Vector Store: Create a Chroma index of CSV data to facilitate efficient document retrieval.
RAG Approach: Retrieve relevant document chunks using similarity search and generate a response using a large language model (Mistral AI).
Interactive Q&A: Ask questions interactively in a chatbot-like manner, with responses based on the CSV content.



Follow the prompts:


Enter the path to your CSV file.

Specify any columns to remove if necessary.

Ask questions interactively, and the chatbot will respond with relevant information based on the CSV data.

Exit the chatbot by typing exit, quit, or q.
