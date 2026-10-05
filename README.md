# Chatbot Application 🤖

A simple AI-powered chatbot built with **Flask** (backend) and **HTML/CSS/JavaScript** (frontend).  
This project demonstrates how to connect a web interface with a Python backend to handle user queries.

---

## 🚀 Features
- Interactive chat interface (frontend in HTML/CSS/JS)
- Flask backend API for handling responses
- Easy to extend with ML/NLP models
- Ready for deployment with Docker

---

## 📂 Project Structure
LLM_application_chatbot/
│── app.py              # Flask backend
│── static/             # CSS, JS files
│── templates/          # HTML frontend
│── requirements.txt    # Python dependencies
│── Dockerfile          # Containerization setup

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone git@github.com:swethakv18-code/chatbot.git
cd chatbot
2. Install dependencies
bash
pip install -r requirements.txt
3. Run the Flask app
bash
python app.py
4. Open in browser
Navigate to:

Code
http://127.0.0.1:5000
🐳 Docker Deployment
Build and run the container:

bash
docker build -t chatbot-app .
docker run -p 5000:5000 chatbot-app
📸 Screenshots
<img width="1008" height="570" alt="image" src="https://github.com/user-attachments/assets/0bf9b454-2133-475a-a4f0-a18b99fdda3c" />

📜 License
This project is open-source under the MIT License.
