#  AI Personal Assistant

A simple and interactive **AI Personal Assistant** built with **Flask**, powered by **DeepSeek AI models** through the **SambaNova API**. The application enables users to ask general questions and summarize lengthy emails using a clean and responsive web interface.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_Framework-black?style=for-the-badge&logo=flask)
![OpenAI SDK](https://img.shields.io/badge/OpenAI-SDK-412991?style=for-the-badge&logo=openai)
![DeepSeek](https://img.shields.io/badge/DeepSeek-AI-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

---

##  Features

-  **Ask Anything** – Get AI-generated responses to general questions.
-  **Email Summarization** – Convert long emails into concise 2–3 sentence summaries.
-  **Fast AI Responses** – Powered by DeepSeek models via the SambaNova API.
-  **Simple Web Interface** – Clean and responsive UI built with HTML, CSS, and JavaScript.
-  **Secure API Key Management** – Uses environment variables to keep API keys safe.

---

##  Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend Programming |
| Flask | Web Framework |
| HTML5 | Frontend Structure |
| CSS3 | Styling |
| JavaScript | Frontend Interactivity |
| OpenAI Python SDK | API Integration |
| SambaNova API | AI Inference |
| DeepSeek-V3.1 | Question Answering |
| DeepSeek-R1-0528 | Email Summarization |
| python-dotenv | Environment Variable Management |

---

##  Project Structure

```text
AI-Personal-Assistant/
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── main.py
├── Requirements.txt
├── .env.example
├── Architecture.png
└── README.md
```

---

##  Installation

### 1️ Clone the Repository

```bash
git clone https://github.com/your-username/AI-Personal-Assistant.git
cd AI-Personal-Assistant
```

### 2️ Create a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️ Install Dependencies

```bash
pip install -r requirements.txt
```

---

##  Environment Variables

Create a file named **`.env`** in the project root.

```env
OPENAI_API_KEY=YOUR_SAMBANOVA_API_KEY
```

> **Note:** Never commit your `.env` file or API keys to GitHub.

---

##  Running the Application

Start the Flask server:

```bash
python main.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

##  How It Works

###  Ask Anything

1. Enter any question.
2. Click **Ask**.
3. The Flask backend sends your query to the **DeepSeek-V3.1** model through the SambaNova API.
4. The AI-generated response is displayed on the webpage.

---

###  Email Summarization

1. Paste an email into the text area.
2. Click **Summarize**.
3. The backend sends the email to the **DeepSeek-R1-0528** model.
4. A concise summary is returned and displayed.

---

##  System Architecture

```text
                User
                  │
                  ▼
          HTML/CSS/JavaScript
                  │
                  ▼
             Flask Backend
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
  Ask AI Endpoint     Summarize Endpoint
        │                   │
        ▼                   ▼
 DeepSeek-V3.1      DeepSeek-R1-0528
        │                   │
        └─────────┬─────────┘
                  ▼
          SambaNova API
                  │
                  ▼
            AI Response
                  │
                  ▼
               Browser
```

---


##  Future Enhancements

-  Chat history
-  Dark mode
-  Speech-to-Text
-  Text-to-Speech
-  PDF and document summarization
-  File upload support
-  Streaming AI responses
-  Multiple AI model selection
-  ChatGPT-style conversation interface

---

##  Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---


##  Author

**Soumya Kanti Upadhyay**

-  B.Tech in Computer Science & Engineering

---
