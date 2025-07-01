
# 💬 ChatFusion

ChatFusion is an AI-powered chat interface built with **Streamlit**, **LangChain**, and **OpenAI's GPT models**. It offers a clean and interactive frontend with advanced conversational capabilities and support for document-based question answering using **Chat with PDF**.

---

## 🚀 Features

- ⚡ Streamlit-based responsive UI  
- 📚 Chat with PDFs (using `LangChain` and `PyPDF`)  
- 🔗 Vector DB and embeddings support  
- 🧠 GPT-3.5/4 powered backend via OpenAI API  
- 🛠 Modular structure for ease of development  
- 🌐 Environment variable management with `.env`  
- ✅ Chat memory and conversation history  


## 📁 Project Structure

ChatFusion/
├── assets/
├── components/
│ └── chat_box.py
├── pages/
│ ├── Chat_with_PDF.py
│ └── Home.py
├── utils/
│ ├── pdf_utils.py
│ ├── vector_utils.py
│ └── llm_utils.py
├── .env.example
├── requirements.txt
├── README.md
└── app.py

