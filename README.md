# 💬 ChatFusion

ChatFusion is a modern, real-time messaging web application that enables seamless communication between users. Designed with performance, scalability, and UX in mind, it supports private and group chats, user authentication, and real-time updates.

---

## 🚀 Features

- 🔐 Secure User Authentication (JWT/Session-based)
- 💬 Real-time Messaging with Socket.IO
- 👥 Private and Group Chats
- 📝 Message status (delivered, read)
- 🔎 User Search and Contact Management
- 🖼️ Profile Pictures & Media Support
- 🌓 Dark/Light Theme Toggle (optional)
- 📱 Responsive UI across devices

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS / Bootstrap
- Axios
- React Router

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose ODM)
- Socket.IO (real-time communication)
- JWT for authentication
- Multer/Cloudinary (optional for file uploads)

**Dev Tools & Deployment:**
- Git & GitHub
- Postman (API testing)
- Render / Vercel / Netlify / Railway (deployment options)

---
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
## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/chatfusion.git
cd chatfusion

# Frontend setup
cd client
npm install
npm start

# Backend setup
cd ../server
npm install
npm run dev




