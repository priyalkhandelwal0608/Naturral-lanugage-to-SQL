#  AI-Powered Database Assistant using Ollama & SQLite

##  Overview

This project is an **AI-powered database assistant** that allows users to ask questions in **natural language** (like English), converts them into SQL queries, executes them on a database, and then uses an AI model to **explain the results in simple words**.

 In short:
**User Question → SQL Query → Database Result → AI Explanation**

---

##  Features

*  Ask questions in plain English
*  Automatic SQL query execution
*  Fetch results from SQLite database
*  AI-powered summarization using Ollama
*  Error handling for SQL and AI issues
*  Interactive command-line interface

---

##  Project Structure

```
project/
│── main.py              # Main application script
│── database.db         # SQLite database
│── requirements.txt    # Required libraries
│── README.md           # Project documentation
```

---

##  Technologies Used

*  Python
*  SQLite
*  Pandas
*  Ollama (LLM)
*  LangChain (optional integration)

---

##  Installation and run
pip install -r requirements.txt
Download and install Ollama from: https://ollama.com
ollama pull llama3
python main.py


---

