# 📚 StudyBot — Mini ChatGPT-Style Chatbot for Students

A beginner-friendly AI chatbot web application built using **Python**, **FastAPI**, **HTML**, and **CSS**.

This chatbot helps students ask questions and receive AI-generated answers using:

* 🌐 Wikipedia Search
* 🤖 Hugging Face Transformers (BART Model)
* 💬 ChatGPT-style User Interface

---

# 🚀 Features

✅ Clean ChatGPT-style interface
✅ Student-friendly chatbot
✅ AI-generated summarized answers
✅ Wikipedia integration
✅ FastAPI backend
✅ Responsive UI design
✅ Simple beginner project structure
✅ Easy to run locally

---

# 🛠️ Technologies Used

| Technology                | Purpose               |
| ------------------------- | --------------------- |
| Python                    | Backend Programming   |
| FastAPI                   | API Framework         |
| HTML                      | Frontend Structure    |
| CSS                       | Styling               |
| Wikipedia API             | Information Retrieval |
| Hugging Face Transformers | AI Summarization      |
| Uvicorn                   | Server                |

---

# 📂 Project Structure

```bash
Student_Chatbot/
│
├── main.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   └── index.html
│
├── static/
│   └── css/
│       └── style.css
│
├── screenshots/
│   ├── chatbot_interface.png
│   └── chatbot_response.png
│
└── venv/
```

---

# ⚙️ Installation Guide

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/chussainbee2026-commits/Student_Chatbot_API.git
```

---

## 2️⃣ Navigate to the Project Folder

```bash
cd Student_Chatbot_API
```

---

## 3️⃣ Create Virtual Environment

```bash
python -m venv venv
```

---

## 4️⃣ Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

---

## 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 6️⃣ Run the Application

```bash
python main.py
```

OR

```bash
uvicorn main:app --reload
```

---

# 🌐 Open in Browser

After starting the server, open:

```bash
http://127.0.0.1:8000
```

---

# 📸 Project Screenshots

## 🖥️ Chatbot Interface

![Chatbot Interface](student_chatbot/screenshots/chatbot_interface.png)

---

## 💬 Chatbot Response Example

![Chatbot Response](student_chatbot/screenshots/chatbot_response.png)

---

# 🤖 How It Works

1. User enters a question.
2. The chatbot searches Wikipedia.
3. AI summarizes the information.
4. The response is displayed in the chatbot UI.

---

# 📦 requirements.txt

```txt
fastapi
uvicorn
jinja2
wikipedia
transformers
torch
```

---

# 💡 Future Improvements

* 🔐 User Authentication
* 🌙 Dark Mode
* 🧠 Better AI Models
* 📱 Mobile Responsive Design
* 💾 Chat History Storage
* 🌍 Multi-language Support

---

# 👨‍💻 Author

**Hussain Bee**

GitHub Repository:

[https://github.com/chussainbee2026-commits/Student_Chatbot_API](https://github.com/chussainbee2026-commits/Student_Chatbot_API)

---

# ⭐ Support

If you like this project:

⭐ Star the repository on GitHub
🍴 Fork the project
📢 Share with others

---

# 📜 License

This project is created for educational and learning purposes.
