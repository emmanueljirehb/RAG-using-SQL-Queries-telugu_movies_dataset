
![ChatGPT Image Jul 4, 2025, 10_29_09 AM](https://github.com/user-attachments/assets/bff5a264-e4d8-4933-b6b9-c129e9fec439)
# 🎬 RAG using SQL Queries - Telugu Movies Dataset

This project demonstrates **Retrieval-Augmented Generation (RAG)** using a custom **Telugu Movies dataset**. It combines **LLMs** with SQL-based data retrieval to generate contextual and accurate responses based on real-world movie data.

---

## 📌 Key Features

- 🔎 Implements **RAG pipeline**: retrieves data via SQL and augments generation using a language model.
- 📂 Uses a **Telugu movies dataset** with structured metadata (title, director, year, rating, etc.).
- 🧠 Integrates **LangChain** components to handle:
  - Query interpretation
  - Document retrieval
  - Prompt construction
  - Final answer generation
- 🧪 Example Queries: 
  - "List all movies directed by SS Rajamouli after 2010"
  - "Which Telugu movies have a rating above 8?"

---

## 📊 Dataset Info

The dataset includes information such as:
- 🎥 Movie Title
- 👨‍💼 Director
- 📅 Release Year
- ⭐ IMDb Rating
- 📋 Genre

---

## 🛠️ Tech Stack

- 🧠 **LangChain**
- 🤖 **OpenAI / GPT model**
- 🗄️ **SQLite / Pandas SQL**
- 🌐 **XAMPP Server (Apache + MySQL)** – used to host and manage the SQL database for query execution.

  ![XAMPP Interface Screenshot](https://www.apachefriends.org/images/xampp-logo-ac950edf.svg)

- 🧪 **Streamlit** (optional for UI)
- 🐍 **Python**

---

## 🚀 How to Run

1. **Clone the repo**

   ```bash
   git clone https://github.com/emmanueljirehb/RAG-using-SQL-Queries-telugu_movies_dataset.git
   cd RAG-using-SQL-Queries-telugu_movies_dataset
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Start XAMPP Server**

   - Launch the **XAMPP Control Panel**
   - Start **Apache** and **MySQL**
   - Import the movie dataset into **phpMyAdmin** or use SQL CLI

4. **Run the main script / Streamlit app**

   ```bash
   python app.py
   # or
   streamlit run app.py
   ```

---

## 📌 Use Cases

- Querying domain-specific datasets using natural language
- Building intelligent assistants for data exploration
- RAG applications in entertainment analytics or regional language domains

---

## 🧠 RAG Flow Explained

1. **User inputs natural language query**
2. **LangChain parses query into SQL**
3. **SQL runs against the movie database**
4. **Retrieved results + original query are sent to LLM**
5. **LLM generates a coherent and informative response**

---

## 📷 Sample Output

> **Query**: _"What are the top 3 rated movies directed by Trivikram?"_  
> **Response**: _"The top 3 rated Telugu movies directed by Trivikram are Athadu, Ala Vaikunthapurramuloo, and Julayi, with ratings above 8."_  
![image](https://github.com/user-attachments/assets/0a883407-18de-4666-9420-8e852fd18f3b)

![Gemini_Generated_Image_jwy9aajwy9aajwy9](https://github.com/user-attachments/assets/4c8409ca-67ab-495f-a684-d4a841107bb8)

---

## ✨ Credits

Project by [@emmanueljirehb](linkedin http://www.linkedin.com/in/emmanueljirehb)  
Inspired by real-world use of RAG in structured databases.

---
