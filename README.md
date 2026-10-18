# LangChain Conversational Chatbot

## 📌 Overview
This project is a simple conversational chatbot built using Python, LangChain, and OpenAI's language model. It accepts user input, generates AI-powered responses, and maintains conversation history during the session.

## ✨ Features
- Interactive conversation through the terminal.
- AI-generated responses using the OpenAI API.
- Chat history management to preserve conversation context.
- Secure API key configuration using environment variables.

## 🛠️ Tech Stack
- Programming Language: Python
- LLM Framework: LangChain
- AI Model Integration: OpenAI API
- Environment Variables: python-dotenv


## ⚙️ Installation and Setup

### 1. Clone the repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_NAME
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
```

On Windows PowerShell:
```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install dependencies
```bash
pip install langchain-openai python-dotenv
```

### 4. Configure your API key
Create a `.env` file in the project directory and add:

```env
OPENAI_API_KEY=your_api_key_here
```

### 5. Run the chatbot
```bash
python chatbot.py
```

## 💬 Usage
1. Run the Python script.
2. Enter a message in the terminal.
3. The chatbot generates a response.
4. Continue the conversation to test chat history.
5. Type `exit` to end the session.

## 🚀 Future Improvements
- Add a web interface using Streamlit.
- Implement persistent conversation storage.
- Add error handling for API and network failures.
- Support multiple conversations.

## 👩‍💻 Author
Sakshi Kasera
