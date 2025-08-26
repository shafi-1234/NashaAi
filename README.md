# 🚀 Nasha AI

Nasha AI is an AI-powered chatbot application built with **Streamlit** and **LangChain**, featuring seamless integration with **DeepSeek Ollama** for intelligent and interactive conversations.  
It is designed for simplicity, performance, and **offline use** — running **only on localhost** with no external server requirements.

---

## ✨ Features
- 🧠 Chat with advanced LLMs like DeepSeek Ollama  
- 🖥️ **Runs only on localhost in offline mode**  
- 🎨 Modern Streamlit UI with custom styling  
- ⚡ Lightweight, fast, and secure  
- 🔌 Modular architecture for easy customization  

---
▶️ Run Locally (Offline with Ollama + DeepSeek)

Install Ollama on your system.
Pull your desired DeepSeek model (example: deepseek-llm):
*)Run in cmd prompt
ollama pull deepseek-llm

---

## 🛠️ Tech Stack
- **App Framework:** Streamlit  
- **AI Framework:** LangChain  
- **LLM Provider:** DeepSeek Ollama  
- **Programming Language:** Python 3.9+  

---

## 📂 Project Structure
nasha-ai/
├── app.py # Main application file
├── requirements.txt # Project dependencies
├── README.md # Documentation
└── assets/ # Images, icons, and assets

---

## ⚙️ Installation & Setup
```bash
git clone https://github.com/your-username/nasha-ai.git
cd nasha-ai
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
pip install -r requirements.txt

---

▶️ Run Locally (Offline Mode)
streamlit run app.py

---

Once started, open your browser and visit:
🔗 http://localhost:8501

📌 Nasha AI runs only on your local machine in offline mode.


