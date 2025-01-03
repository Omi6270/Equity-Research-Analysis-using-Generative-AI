Equity Research Analysis Using Generative AI


Overview

This project leverages LangChain, FAISS, Generative AI, and LLMs to perform advanced financial analysis. It processes content from multiple URLs, organizes it into a vector database, and provides:

Detailed answers to user-specific questions.
Summarized insights from financial data.

Features

1. Multi-URL Input: Analyze data from up to 3 URLs simultaneously.
2. Automated Processing: Efficiently loads and processes data from the provided URLs.
3. Vector-Based Search: Utilizes FAISS for similarity search and efficient information retrieval.
4. Generative AI Answers: Employs LangChain and generative AI to answer user queries.
5. Financial Summarization: Extracts key financial insights from the input data.
   
Technology Stack

1. Backend: LangChain, FAISS Library
2. Frontend: Streamlit
3. Programming Language: Python
4. Database: Vector-based storage (FAISS)
   
Setup Instructions

1. Project Setup:
Open a folder in PyCharm or your preferred IDE.
Create a new .py file (e.g., main.py) and paste the project code.

2.Environment Setup:
Create a .env file in the project folder.
Add your OpenAI API key to the .env file in the following format:

OPENAI_API_KEY=your_api_key_here  

3. Run the Application:
Open the terminal in your project directory.
Run the following command:
" streamlit run main.py "
(Replace main.py with the name of your Python file if different.)

Usage:

1. Enter up to 3 URLs in the input fields.
2. Provide a query or prompt to receive detailed answers and insights.
