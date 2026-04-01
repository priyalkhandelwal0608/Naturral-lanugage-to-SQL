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
```


##  Example Usage

###  Input:

```
Show all employees
```

###  Database Output:

```
Name     Age     Salary
Alice    25      50000
Bob      30      60000
Charlie  35      70000
```

###  AI Output:

```
There are 3 employees: Alice, Bob, and Charlie.
Their ages range from 25 to 35 and salaries range from 50,000 to 70,000.
```

---

##  Workflow

1. User enters a question
2. Question is converted into SQL
3. SQL query runs on SQLite database
4. Result is stored in Pandas DataFrame
5. Data is converted into text
6. Prompt is sent to Ollama
7. AI generates a simple explanation
8. Output is shown to user

---

