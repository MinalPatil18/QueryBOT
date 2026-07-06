# 🤖 QueryBOT – AI-Powered Natural Language to SQL Generator

QueryBOT is an AI-powered application that converts natural language questions into SQL queries using Google's Gemini Large Language Model (LLM). The generated SQL query is executed on a SQLite database, and the results are displayed through an interactive Streamlit interface.

The project demonstrates how Generative AI and Large Language Models can simplify database interactions by allowing users to retrieve information using plain English instead of writing SQL queries manually.

---

## 🚀 Features

- Convert natural language into SQL queries using Google Gemini AI
- Execute AI-generated SQL queries on a SQLite database
- Display query results in a clean tabular format using Pandas
- Interactive and user-friendly web interface built with Streamlit
- Secure API key management using environment variables
- Fast and lightweight application for database querying

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Framework:** Streamlit
- **Large Language Model:** Google Gemini API
- **Database:** SQLite
- **Data Processing:** Pandas
- **Environment Variables:** python-dotenv

---

## 📌 How It Works

1. The user enters a question in plain English.
2. Google Gemini converts the question into an SQL query.
3. The generated SQL query is executed on the SQLite database.
4. The application retrieves the relevant records.
5. Results are displayed in an interactive table.

---

## 📂 Project Structure

```
QueryBOT/
│── app.py
│── student.db
│── requirements.txt
│── .env
│── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/MinalPatil18/QueryBOT.git
cd QueryBOT
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file in the project root and add your Gemini API key.

```env
GOOGLE_API_KEY=your_api_key
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 💬 Example Questions

- How many students are in the MBA class?
- Show students from Section A.
- Display students scoring more than 80 marks.
- List all students sorted by marks.
- Show students with attendance above 90%.

---

## 🎯 Skills Demonstrated

- Large Language Models (LLMs)
- Generative AI
- Prompt Engineering
- AI Application Development
- Google Gemini API Integration
- Natural Language to SQL Conversion
- SQLite Database Operations
- Python Programming
- Streamlit Development
- Data Processing with Pandas

---

## 💡 Future Enhancements

- Support MySQL and PostgreSQL
- Conversational chatbot interface
- Query history
- Export results to CSV and Excel
- User authentication
- Database schema visualization

---

## 👩‍💻 Author

**Minal Patil**
