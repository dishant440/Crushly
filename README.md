# Crushly
A full-featured, real-time chat application with AI-powered message suggestions — including flirty, witty, supportive, or professional replies. This app is perfect for casual, romantic, or friendly interactions, with optional smart AI support.

---

## 🚀 Features

### 🔧 Core Chat Features
- 🔐 User Authentication (Email/Password or OAuth)
- 👥 User Profiles (Name, Gender, Interests, Photo)
- 💬 One-on-One Real-Time Chat (Socket.IO)
- 📦 Chat History & Storage (MongoDB)
- 📷 Image/GIF Upload (Optional)
- ✅ Read receipts, Typing indicators

---

### 🤖 AI Assistant Features
- ✨ **Message Suggestions Based on Context**  
  Flirty, funny, or empathetic messages depending on the ongoing chat and gender profile.
  
- 💡 **Tone Selector**  
  Choose AI suggestion tone: `Flirty`, `Funny`, `Casual`, `Witty`, `Formal`, etc.

- ⚡ **Smart Autocomplete**  
  Predict the next part of your sentence like Gmail Smart Compose.

- 📣 **Quick Replies**  
  1-tap response suggestions from recent messages.

- 🎭 **Rephrase with Emotion**  
  Let AI rephrase your message to sound more polite, romantic, funny, or sarcastic.

- 🌐 **AI-Powered Translation**  
  Translate messages in real-time between languages.

- 😍 **Mood Detection & Reactions**  
  Based on the message tone, show emojis or badges (e.g., 😊 Happy, 😏 Flirty).

---

## 🛠️ Tech Stack

| Layer        | Technology                        |
|--------------|-----------------------------------|
| Frontend     | React.js, Tailwind CSS, Socket.IO |
| Backend      | Node.js, Express.js, Socket.IO    |
| Database     | MongoDB with Mongoose             |
| Authentication | JWT, bcrypt                     |
| AI Assistant | OpenAI GPT / Gemini / Local LLM   |
| Deployment   | Render / Vercel / Railway         |

---

## 📁 Project Structure

#Crushly/
├── client/ # React Frontend
│ └── components/
│ └── pages/
│ └── hooks/
├── server/ # Node.js Backend
│ └── routes/
│ └── controllers/
│ └── models/
│ └── socket/
├── shared/ # Shared Types or Utils
├── .env
├── README.md
└── package.json

## 📦 Getting Started

🔧 Install Backend
```bash
cd server
npm install
npm run dev
```
🔧 Install Frontend
```bash
Copy
Edit
cd client
npm install
npm start
```

