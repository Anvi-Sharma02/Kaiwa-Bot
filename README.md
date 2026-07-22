# 🤖 Kaiwa-Bot

**An AI-powered Japanese Voice Conversation Practice Assistant**

Kaiwa-Bot is an AI-powered web application that helps Japanese language learners improve their speaking skills through natural voice conversations. Users can interact with an AI conversation partner, receive contextual responses, practice casual or business Japanese, and build confidence without needing a human language partner.

---

## 📖 About the Project

Many Japanese learners spend most of their time studying grammar and vocabulary but struggle to find opportunities to practice speaking. Kaiwa-Bot bridges this gap by providing realistic AI-powered voice conversations, allowing learners to practice anytime and anywhere.

Whether you're preparing for the JLPT, planning to work in Japan, or simply looking to improve your conversational fluency, Kaiwa-Bot offers an immersive learning experience focused on real communication.

---

## ✨ Features

* 🎙️ Real-time voice conversations in Japanese
* 🤖 AI-powered contextual responses using Groq Llama 3.3
* 💬 Casual Conversation Mode
* 💼 Business Japanese (Keigo) Mode
* 🧠 Natural grammar and vocabulary corrections
* 🔊 AI speech synthesis for spoken responses
* 🎤 Speech recognition using the Web Speech API
* 🔐 Secure Google Sign-In with Firebase Authentication
* 📱 Responsive and modern user interface

---

## 🎯 Target Users

* JLPT N5–N2 learners
* Self-study Japanese learners
* College students
* Professionals preparing to work in Japan
* Anyone looking to improve Japanese speaking confidence

---

## 🛠️ Tech Stack

### Frontend

* React
* Vite
* JavaScript (ES6)
* HTML5
* CSS3
* Tailwind CSS
* Framer Motion

### AI Integration

* Groq API
* Llama 3.3 70B Versatile

### Voice Technologies

* Web Speech API
* Speech Recognition API
* Speech Synthesis API

### Authentication

* Firebase Authentication
* Google Sign-In

### Version Control

* Git
* GitHub

---

## 🚀 How It Works

1. User signs in using a Google account.
2. Selects either Casual or Keigo mode.
3. Speaks naturally in Japanese.
4. Speech Recognition converts speech into text.
5. The text is sent to the Groq AI model.
6. Kaiwa-Bot generates a contextual Japanese response.
7. The response is displayed and spoken aloud.
8. The conversation automatically continues for natural speaking practice.

---

## 📂 Project Structure

```text
Kaiwa-Bot/
├── src/
│   ├── services/
│   │   ├── ai.js
│   │   └── auth.js
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   └── assets/
│
├── public/
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Anvi-Sharma02/Kaiwa-Bot.git
```

### Navigate to the project

```bash
cd Kaiwa-Bot
```

### Install dependencies

```bash
npm install
```

### Configure environment variables

Create a `.env` file:

```env
VITE_GROQ_API_KEY=your_groq_api_key

VITE_FIREBASE_API_KEY=your_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### Run the application

```bash
npm run dev
```

---

## 🎯 Challenges Faced

One of the biggest challenges was creating a natural voice conversation experience using browser-based speech recognition and speech synthesis. Managing continuous conversations, handling speech interruptions, maintaining conversational flow, and reducing recognition errors required careful coordination between browser speech APIs and the AI response pipeline.

---

## 🔮 Future Improvements

* 📝 Personal vocabulary notebook
* 📚 Grammar notes and mistake tracking
* 🎯 JLPT-specific practice modes
* 📈 Learning progress dashboard
* 💾 Conversation history
* 🗣️ Multiple Japanese voice options
* 🌐 Real-time streaming conversations
* ☁️ Cloud database integration
* 🎭 Scenario-based roleplay practice

---

## 👩‍💻 Author

**Anvi Sharma**

* Computer Science Engineering Student
* DevOps Specialization
* Japanese Language Learner (JLPT/NAT N3)
* Passionate about AI, Full-Stack Development, DevOps, and building technology for language learning.

GitHub: https://github.com/Anvi-Sharma02

---

## 📄 License

This project is licensed under the MIT License.
