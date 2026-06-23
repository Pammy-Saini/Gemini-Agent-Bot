# Gemini Agent Bot

An intelligent AI agent built using **Streamlit**, **LangChain**, and **Google Gemini** that can answer user queries using both LLM reasoning and custom tools.

The application combines Gemini’s natural language understanding with tool-calling capabilities to perform tasks such as mathematical calculations and word counting in real time.

---

## Overview

Gemini Agent Bot is a lightweight AI assistant designed to:

- Answer general knowledge questions  
- Perform mathematical calculations  
- Count words in user input  
- Demonstrate tool integration using LangChain agents  

This project showcases how Large Language Models (LLMs) can interact with external tools to improve accuracy and extend functionality.

---

## Features

- **AI-Powered Question Answering** using Google Gemini  
- **Tool Calling Agent** with LangChain  
- **Calculator Tool** for mathematical operations  
- **Word Counter Tool** for text analysis  
- **Interactive UI** built with Streamlit  
- **Secure API Key Management** using environment variables  

---

## Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **Google Gemini API**
- **python-dotenv**

---

## Project Architecture

```bash
Gemini-Agent-Bot/
│
├── app.py               # Main Streamlit application
├── tools.py             # Custom tool definitions
├── requirements.txt     # Python dependencies
├── .env                 # API key configuration (excluded from Git)
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd Gemini-Agent-Bot
```

---

### 2. Create Virtual Environment

**Windows**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux / macOS**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Setup

Create a `.env` file in the root directory and add your Gemini API key:

```env
GOOGLE_API_KEY=your_api_key_here
```

Generate your API key from

Makersuite API Keys



---

## Running the Application

Start the Streamlit server:

```bash
streamlit run app.py
```

If Streamlit is not recognized:

```bash
python -m streamlit run app.py
```

---

## Sample Queries

Examples you can test:

```text
What is Python?
```

```text
3*4+5
```

```text
word count: I am learning AI
```

---

## Tool Descriptions

### Calculator Tool
Executes arithmetic expressions.

**Input**
```text
12*5+10
```

**Output**
```text
70
```

---

### Word Counter Tool
Calculates total number of words in a given sentence.

**Input**
```text
word count: AI is transforming technology
```

**Output**
```text
Total words: 4
```

---



## Future Enhancements

Planned improvements include:

- Chat history support  
- Voice interaction  
- Additional AI tools  
- File processing capabilities  
- Improved UI/UX  

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Building AI-powered applications  
- Using LangChain agents and tools  
- Integrating Google Gemini API  
- Developing interactive web apps with Streamlit  
- Managing environment variables securely  

---

## Author

**Pammy Saini**  
Aspiring AI / ML Developer

