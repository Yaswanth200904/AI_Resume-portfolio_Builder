AI Resume & Portfolio Builder

An AI-powered web application that allows users to create, manage, and download professional resumes and cover letters. Built using Flask, SQLAlchemy, and AI-based text generation services.

✨ Features

🔐 User Authentication (Register/Login)

📝 Resume Builder

🤖 AI Resume Analysis

📄 AI Cover Letter Generation

📥 PDF Resume Download

📁 Portfolio Page Creation

🗂 Resume History Management

📤 File Upload Support

🛠 Tech Stack

Backend: Flask (Python)

Database: SQLite (SQLAlchemy ORM)

Frontend: HTML, CSS, Jinja Templates

Authentication: Flask-Login

PDF Generation: Custom PDF Service

Deployment Ready: Gunicorn Compatible

📂 Project Structure
AI_Resume_Builder/
│── app.py
│── config.py
│── models.py
│── ai_service.py
│── pdf_service.py
│── resume_analyzer.py
│── requirements.txt
│── templates/
│── static/
│── instance/
⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/Yaswanth200904/AI-Resume-Portfolio-Builder.git
cd AI-Resume-Portfolio-Builder

2️⃣ Create virtual environment

python -m venv venv
venv\Scripts\activate  # Windows

3️⃣ Install dependencies

pip install -r requirements.txt

4️⃣ Run the application

python app.py

Future Improvements

Deploy to cloud (Render / Railway / etc.)

Add Resume Templates

Improve UI Design

Add Admin Dashboard

👩‍💻 Author

MV YASWANTH
CSE AI/ML 
Aspiring Full Stack Developer

App will run at:

http://127.0.0.1:5000
