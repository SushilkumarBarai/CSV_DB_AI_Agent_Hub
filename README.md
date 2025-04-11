
# 🧠 Agentic AI for SQL & CSV Querying

This project is a Python-based Agentic AI assistant that connects to **SQL databases** and **CSV files** to answer user queries using natural language. Powered by **LangChain**, **OpenAI**, and **Streamlit**, it offers an intuitive interface for querying structured data sources.

---

## 🚀 Features

- 🔗 Connects to **SQL databases** using `pyodbc` and `SQLAlchemy`
- 📁 Reads and queries **CSV files**
- 🤖 Uses **LangChain Agents** to interpret and run user queries
- 💡 Employs **OpenAI GPT** for natural language understanding
- 🖥️ Simple **Streamlit UI** for user interaction
- 🧠 Supports intelligent reasoning over structured data

---

## 🧰 Tech Stack

- **Python 3.10+**
- `langchain`, `openai`, `streamlit`
- `pyodbc`, `SQLAlchemy` for SQL connection
- `pandas` for CSV handling
- `.env` for API and DB credentials

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/SushilkumarBarai/database_csv_ai_agents.git
cd database_csv_ai_agents
```

2. **Create a virtual environment (optional)**

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the App

```bash
streamlit run sql_db_agent.py
```

Then open [http://localhost:8501](http://localhost:8501) in your browser.

---



## 📁 Sample `.env` Configuration

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_api_key
DATABASE_CONNECTION_STRING=DRIVER={ODBC Driver 17 for SQL Server};SERVER=your_server;DATABASE=your_db;UID=user;PWD=password
```

---

## 💬 Example Queries

- “What is the total number of customers in the database?”
- “Show me the average revenue per region from the CSV file.”
- “Get the top 5 products by sales from the last quarter.”

---

## ✅ Conclusion

This Agentic AI solution bridges the gap between natural language and structured data. By integrating powerful LLMs (like OpenAI's GPT) with SQL databases and CSV files, it empowers users to **query data using plain English** — without needing to write SQL or Python code.

With an intuitive UI built on Streamlit and intelligent reasoning powered by LangChain agents, this system is a perfect example of how LLMs can be used to build real-world, **low-code data analytics assistants**.

---

## 🧠 Use Cases

- 🔍 **Business Intelligence Assistant**: Let business users query databases without SQL — e.g., “Show me sales trends for the last quarter.”
- 📈 **Data Analyst Co-Pilot**: Speed up insights from CSVs and databases without switching tools or writing code.
- 🧾 **Customer Support Dashboards**: Answer real-time customer queries using backend CRM databases.
- 🡩‍🏫 **Education & Learning**: Help students interact with datasets using natural language to understand data structures and outputs.
- 🏢 **Enterprise Reporting**: Automatically generate reports from operational databases with plain English instructions.
- 🧪 **Prototyping & Demos**: Great for showing quick proofs-of-concept in data-driven AI applications.



---

## 🤛 Author

**Sushil Kumar Barai**  
🔗 [GitHub](https://github.com/SushilkumarBarai)


