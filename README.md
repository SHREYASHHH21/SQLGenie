# Gemini App To Retrieve SQL Data

This project demonstrates a web-based application that allows users to input natural language queries and receive SQL-generated results directly. The app uses an AI model to convert text inputs into SQL queries, which are executed to fetch data from a database. It simplifies database interactions, enabling non-technical users to retrieve data effortlessly.

---

## Features

- **Natural Language to SQL**: Converts user input into SQL queries automatically.
- **Streamlit Interface**: Simple and interactive web interface built using Streamlit.
- **Database Querying**: Supports querying data dynamically from a connected database.
- **Efficient AI Integration**: Leverages AI to interpret user intent and generate accurate SQL statements.

---

## Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Database**: SQLite (or any relational database)
- **AI Model**: Google Gemini Pro

---

## Screenshots

### 1. Fetching Average Marks of All Students Class-Wise
![Average Marks](![Screenshot 2025-01-16 114120](https://github.com/user-attachments/assets/5de2df30-0afe-46ba-b2a2-c45e6f2bf56e))

### 2. Fetching Student Name with Second Highest Marks Class-Wise
![Second Highest Marks](![Screenshot 2025-01-16 113924](https://github.com/user-attachments/assets/bdf9aa1e-5d83-4687-aef9-f7c34241f415))

## How to Run the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/<repository>.git
   ```
2. Navigate to the project directory:
   ```bash
   cd <repository>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
5. Open the app in your browser at `http://localhost:8501`.

---

## Usage

1. Enter a query in natural language (e.g., "Provide average marks of all students class-wise").
2. Click **"Ask the question"**.
3. View the SQL result displayed on the screen.

---

## Example Queries

- "Provide the total number of students in each class."
- "Fetch the top 5 scorers in Mathematics."
- "List students who scored below 40 in Science."

---

## Future Enhancements

- **Multi-Database Support**: Add compatibility with MySQL, PostgreSQL, etc.
- **Custom Authentication**: Enable user authentication for secure access.
- **Enhanced NLP**: Improve model accuracy for complex queries.

---
   
