# LexAI Chat 🤖💬

LexAI Chat is a modern, lightweight **AI chatbot web application** built using **HTML, CSS, and JavaScript**, powered by **Google Gemini (Generative Language API)**.  
It features a clean floating chat interface, emoji support, file uploads, and real-time AI responses — all running on the frontend.

---
<p align="center">
<img width="921" height="672" alt="Screenshot 2026-02-09 204405" src="https://github.com/user-attachments/assets/11212c1f-ad23-4c22-942e-c4967e57dbab" />
</p>

## ✨ Features

- 💬 Interactive AI chatbot
- ⚡ Powered by **Gemini 2.5 Flash**
- 😀 Emoji picker integration
- 📎 File upload support (images & documents)
- 🪟 Floating chat widget (open / close)
- 🎨 Responsive and modern UI
- 🚀 No backend required (frontend-only)

---

## 📁 Project Structure
```bash
LexAI-Chat/
│
├── index.html # Main HTML file
├── style.css # Styling for the chat UI
├── script.js # Chat logic and Gemini API integration
└── README.md # Project documentation
```

---

## 🚀 Getting Started

### 1️⃣ Download or Extract
Extract the `LexAI-Chat.zip` file to your local system.

---

### 2️⃣ Add Your Gemini API Key

Open **`script.js`** and replace the API key placeholder:

```js
const API_KEY = "YOUR_GEMINI_API_KEY";
```
You can generate an API key from Google AI Studio.
---

### 3️⃣ Run the Project

Simply open index.html in any modern web browser.

No server or build step required.
---

## 🧠 How It Works

1. User enters a message in the chat input

2. The message (and optional uploaded file) is sent to Gemini API

3. Gemini generates a response

4. The response is dynamically displayed in the chat UI
---
## 🔮 Future Enhancements

- Backend integration for API key security

- Conversation memory & chat history

- User authentication

- Chat with PDFs / documents (RAG)

- Dark / light theme toggle

---

## ⚠️ Security Note

API keys are exposed on the frontend.
For production, use a backend to secure keys and manage requests.
