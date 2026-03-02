🎓 Student Management System

A web-based Student Management System built using Flask (Python) and SQLite.
This application allows users to register, log in, and manage student records efficiently.

🚀 Features

🔐 User Authentication (Register / Login / Logout)

➕ Add New Students

📋 View Student List

✏️ Edit Student Information

❌ Delete Students

💾 SQLite Database Integration

📁 Organized Project Structure (Templates & Static Files)

🛠️ Tech Stack

Backend: Python, Flask

Frontend: HTML, CSS

Database: SQLite

Version Control: Git & GitHub

📂 Project Structure
student-management/
│
├── env/                      
├── static/                   
├── templates/                
│   ├── edit.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   └── view.html
│
├── app.py                    
├── requirement.txt           
├── students.db               
├── .gitignore                
└── README.md   

1️⃣ Clone the Repository
git clone https://github.com/your-username/student-management.git
cd student-management

2️⃣ Create Virtual Environment (Recommended)
python -m venv env

Activate environment:

Windows

env\Scripts\activate

Mac/Linux

source env/bin/activate
3️⃣ Install Dependencies
pip install -r requirement.txt
4️⃣ Run the Application
python app.py

Open your browser and visit:

http://127.0.0.1:5000/
🗄️ Database

Database file: students.db

Uses SQLite (lightweight & file-based)

Automatically created if not available

📌 .gitignore Recommendation

Make sure your .gitignore file contains:

env/
__pycache__/
*.pyc
students.db
🌟 Future Improvements

Search functionality

Pagination

Role-based authentication (Admin/User)

REST API integration

Deployment on Render / Railway / Heroku

📄 License

This project is for educational purposes.

👨‍💻 Author

Your Name
GitHub: https://github.com/your-username
