🧠 QuesThink: AI-Powered MCQ Generator
From PDFs to Practice: Generate High-Quality Multiple Choice Questions with the Power of AI.

QuesThink is a web application designed to help students, educators, and professionals instantly create comprehensive quizzes from PDF documents. By leveraging the Google Gemini API, it transforms dense material into engaging study aids in seconds.

(Suggestion: Replace this placeholder with a real screenshot or GIF of your application to showcase your great UI!)

🎯 The Problem
Manually creating quizzes and study materials from textbooks, lecture notes, or research papers is a tedious and time-consuming process. This manual effort can be a significant bottleneck for effective learning and teaching, especially under tight deadlines like a hackathon!

✨ The Solution
QuesThink automates the entire process. Simply upload a PDF, and our application intelligently analyzes the content and generates relevant, high-quality Multiple Choice Questions (MCQs), complete with correct answers and explanations.

Key Features
📄 PDF Upload: Upload any PDF document (up to 16MB) to serve as the source material.

🤖 AI-Powered Generation: Utilizes the Google Gemini 1.5 Flash model for fast and contextually-aware question generation.

⚙️ Customizable Quizzes: Tailor your quiz by specifying the desired number of questions (from 5 to 50) and difficulty level (Easy, Medium, Hard, or a Mix).

🖥️ Interactive UI: A clean, modern, and responsive user interface for a seamless experience.

✅ Instant Feedback: View the generated questions immediately, with correct answers and detailed explanations clearly displayed.

⬇️ Multiple Export Options:

Download a PDF Report: Get a professionally formatted, printable PDF of your quiz.

Export as JSON: Download the quiz data in JSON format for easy integration with other platforms or applications.

🛠️ Tech Stack
This project was built using a combination of modern technologies:

Frontend:

HTML5

CSS3 (with responsive design)

Vanilla JavaScript (ES6+)

Backend:

Python 3

Flask: A lightweight WSGI web application framework.

Flask-CORS: For handling Cross-Origin Resource Sharing.

AI & Data Processing:

Google Gemini API: The core AI engine for content analysis and MCQ generation.

PyPDF2: For extracting text content from uploaded PDF files.

fpdf2: For generating the downloadable PDF reports.

⚙️ Getting Started
To run this project locally, follow these simple steps.

Prerequisites
Python 3.8 or newer

A Google Gemini API Key. You can get one from Google AI Studio.

Installation & Setup
Clone the repository:

git clone https://github.com/your-username/questthink.git
cd questhink

Create and activate a virtual environment:

Windows:

python -m venv venv
.\venv\Scripts\activate

macOS / Linux:

python3 -m venv venv
source venv/bin/activate

Install the required dependencies from the requirements.txt file:

pip install -r requirements.txt

Set up your environment variables:

Create a new file named .env in the root of the project directory.

Add your Gemini API key to this file:

# Gemini API Configuration
GEMINI_API_KEY="YOUR_GEMINI_API_KEY_HERE"

# Flask Configuration
FLASK_ENV=development
FLASK_DEBUG=True

Replace "YOUR_GEMINI_API_KEY_HERE" with your actual Google Gemini API key.

Run the application:

python app.py

You will see a confirmation message in your terminal:

🧠 QuesThink MCQ Generator Backend Starting...
📚 Ready to generate intelligent MCQs from your PDFs!
🌐 Access the API at: http://localhost:5000

Access the application:
Open your web browser and navigate to:
http://localhost:5000/ui

🚀 Future Enhancements
We have many ideas for expanding the capabilities of QuesThink:

📚 User Accounts & History: Allow users to sign up, save their generated quizzes, and view their history.

🔗 Support for More Formats: Add support for .docx, .txt, and direct URL inputs.

⚡ Caching: Implement Redis to cache results for frequently used documents, speeding up generation.

🎮 Interactive Quiz Mode: Allow users to take the quiz directly within the web interface and see their score.

🗂️ Batch Processing: Enable users to upload multiple documents to create a combined quiz.

## 🏆 Our Team

- Shivam Shinde
- Shraddha Adhav
- Arushi Shesh
- Hrutuja

