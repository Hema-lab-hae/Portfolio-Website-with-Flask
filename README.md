# 🌐 Personal Portfolio Website (Flask)

A simple personal portfolio site built using **Python**, **Flask**, **HTML**, and **CSS**.

This project showcases your bio, skills, and contact form — a real-world mini web application built from scratch.
## 🚀 Features
- Home page with personal info and project list
- Contact page with working form (POST method)
- Flask routing and template rendering
- Clean HTML/CSS layout (easy to style and expand)

 ## 🛠️ Tech Stack
- **Backend**: Python, Flask
- **Frontend**: HTML5, CSS3
- **Tools**: VS Code, Virtual Environment
## 📁 Project Structure
portfolio/
├── main.py # Flask app
├── templates/
│ ├── index.html # Homepage
│ └── contact.html # Contact form
├── static/
│ └── style.css # CSS styling
└── README.md

## ⚙️ How to Run
### 1. Clone or Download

```bash
git clone <your-repo-url>
cd portfolio
2. Create Virtual Environment
bash
Copy
Edit

python -m venv .venv
source .venv/bin/activate      # macOS/Linux
.venv\Scripts\activate         # Windows

pip install Flask
3. Run the Flask App
bash
Copy
Edit
python main.py
Open your browser and visit:
http://127.0.0.1:5000

✍️ Example Content
🏠 Home Page (index.html)
Your name and title

Short about section

Project list

📬 Contact Page (contact.html)
Name, email, message input

Form handled via POST request

Prints message to console (for now)

📌 To-Do / Ideas
✅ Add Bootstrap for responsive design

❌ Send email from contact form (Flask-Mail)
❌ Add a blog or project gallery
❌ Deploy to Render, Heroku, or Vercel

