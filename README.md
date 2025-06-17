💰 Expense Management System

A simple and efficient way to track, analyze, and visualize your expenses — powered by FastAPI (backend) and Streamlit (frontend).Built to help you manage your financial data seamlessly!



🧭 Project Overview

This project is designed to offer a lightweight, full-stack expense tracking system.
It features:

🖥️ A Streamlit-powered UI for user interaction

⚙️ A FastAPI backend for robust API handling

🧪 Built-in tests to ensure functionality and reliability



🧭Project Structure

expense-management-system/
│
├── frontend/        # 💡 Streamlit app (UI)
├── backend/         # ⚙️ FastAPI server (API logic)
├── tests/           # 🧪 Unit & integration tests
├── requirements.txt # 📦 Dependencies
└── README.md        # 📘 Project documentation



⚙️ Getting Started

Follow these steps to get the project up and running locally:

1️⃣ Clone the Repository

   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```

2️⃣ Install the Dependencies   
   ```commandline
    pip install -r requirements.txt
   ```

3️⃣ Start the FastAPI Backend  
   ```commandline
    uvicorn server.server:app --reload
   ```
4️⃣ Launch the Streamlit Frontend 
   ```commandline
    streamlit run frontend/app.py
   ```




✅ Features

Add, update, and delete expenses
Filter and view expenses by date or category
Interactive data visualizations
Modular and testable code structure

📌 Notes

Make sure you have Python 3.8+ installed.
Backend runs on http://localhost:8000 by default.
Frontend Streamlit app runs on http://localhost:8501.


🙌 Contributing

Want to improve the project? Feel free to fork it and send a pull request.
Bug reports and feature suggestions are welcome!


