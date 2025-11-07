🌟 AI Resume Analyzer – by Roshan SS
A simple tool that analyzes resumes using AI and gives useful suggestions to improve them.

🔍 What It Does
Reads and extracts key info from resumes (PDF format)

Shows skills, keywords, and basic details

Suggests improvements like:

Skills to add

Courses to take

Predicted job roles

Resume tips and score

Gives feedback and ratings

Admin can view all user data and download it as CSV

🛠 Tech Used
Frontend: Streamlit, HTML, CSS, JavaScript

Backend: Python, Streamlit

Database: MySQL

Libraries: pandas, pyresparser, pdfminer3, Plotly, NLTK

🚀 How to Run
Clone the project:

bash
git clone https://github.com/deepakpadhi986/AI-Resume-Analyzer.git
Create and activate a virtual environment:

bash
python -m venv venvapp
cd venvapp/Scripts
activate
Install required packages:

bash
cd ../../App
pip install -r requirements.txt
python -m spacy download en_core_web_sm
Create a MySQL database named cv and update credentials in App.py.

Replace the resume_parser.py file inside pyresparser folder with the custom one provided.

Run the app:

bash
streamlit run App.py
🧪 Try It Out
Upload a resume and see the analysis

Use admin login: Username: admin Password: admin@resume-analyzer

📬 Contact
Made with ❤️ by Roshan SS
