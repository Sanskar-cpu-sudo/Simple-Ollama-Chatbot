# Enhanced Q&A Chatbot with Ollama

A simple Streamlit-based chatbot that uses LangChain and Ollama to answer user questions using open-source LLMs such as Mistral and Gemma.

## Features

* Streamlit web interface
* Multiple Ollama models support
* Adjustable temperature parameter
* Adjustable max token length
* LangSmith tracing support
* Environment variable management using dotenv

## Project Structure

.
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
└── .env

## Installation

### 1. Clone the Repository

git clone https://github.com/your-username/ollama-chatbot.git

cd ollama-chatbot

### 2. Create Virtual Environment

Windows:

python -m venv venv

venv\Scripts\activate

Linux/Mac:

python3 -m venv venv

source venv/bin/activate

### 3. Install Dependencies

pip install -r requirements.txt

### 4. Install Ollama

Download and install Ollama from:

https://ollama.com

### 5. Pull Models

For Mistral:

ollama pull mistral

For Gemma:

ollama pull gemma:2b

### 6. Configure Environment Variables

Create a .env file:

LANGCHAIN_API_KEY=your_langsmith_api_key

### 7. Run Ollama

Start Ollama:

ollama serve

### 8. Run Streamlit App

streamlit run app.py

## Usage

1. Select an Ollama model from the sidebar.
2. Adjust temperature and max token settings.
3. Enter a question.
4. Receive a response from the selected model.

## Technologies Used

* Python
* Streamlit
* LangChain
* Ollama
* LangSmith
* Dotenv

## Example Models

* mistral
* gemma:2b
* llama3
* phi3

## Author

Developed as a simple LangChain + Ollama chatbot project.
