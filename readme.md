
AI-Powered Career Guidance System

📌 Project Overview

The AI-Powered Career Guidance System is a web-based application that helps students and professionals choose suitable careers based on their interests, skills, and preferences. The system uses Flask (Python) for machine learning (KNN algorithm) and PHP for the web interface to provide career recommendations and eligibility quizzes.

🚀 Features

✅ User Authentication – Secure login and registration
✅ Profile Management – Users can fill in their details and interests
✅ Career Prediction – AI-based recommendations using the KNN algorithm
✅ Course Suggestions – Displays relevant courses for career paths
✅ Eligibility Quiz – Tests users' knowledge for different career fields
✅ Interactive UI – Built with PHP and HTML for a smooth experience

🛠️ Tech Stack

Backend: Flask (Python) for AI/ML processing

Frontend: PHP, HTML, CSS, JavaScript

Database: MySQL

Machine Learning Algorithm: K-Nearest Neighbors (KNN)


🔧 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/yourusername/career-guidance-system.git
cd career-guidance-system

2️⃣ Setup Python Environment

python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
pip install -r requirements.txt

3️⃣ Setup MySQL Database

1. Create a database career_guidance_db.


2. Import the provided career_guidance.sql file.


3. Update config.php with database credentials.



4️⃣ Start the Flask Server

python app.py

5️⃣ Start the PHP Server

php -S localhost:8000

6️⃣ Open in Browser

Visit http://localhost:8000 to access the application.

📂 Project Structure

career-guidance-system/
│-- ml_model/                # Machine learning model (Flask)
│   ├── model.pkl            # Trained KNN model
│   ├── app.py               # Flask API
│   ├── requirements.txt     # Dependencies
│-- web/                     # PHP Web Interface
│   ├── index.php            # Home page
│   ├── login.php            # User authentication
│   ├── dashboard.php        # User dashboard
│   ├── career.php           # Career recommendation page
│   ├── quiz.php             # Eligibility quiz page
│   ├── config.php           # Database connection
│-- database/                # SQL scripts
│   ├── career_guidance.sql  # Database schema
│-- README.md

🏆 Future Enhancements

🔹 Add deep learning models for better accuracy
🔹 Integrate chatbots for career counseling
🔹 Provide job and internship recommendations

🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

📜 License

This project is open-source under the MIT License.



