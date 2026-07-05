# 🧠 StudyGenius AI – Intelligent AI Study Assistant

StudyGenius AI is a full-stack AI-powered learning platform that transforms static study materials into interactive learning experiences. It converts PDFs, DOCX, TXT, PPTX, and Images into quizzes, concise summaries, visual mind maps, and AI-generated study podcasts, making learning more engaging and effective.



# 🌐 Live Demo

**Website:** [https://StudyGenius-AI-Study-Assistant.netlify.app/](https://6a4a2f82ecb69e0f906fa42b--vermillion-lokum-69010c.netlify.app)

# 📂 GitHub Repository

**Repository:** [https://github.com/Bharadwaj1433/StudyGenius-AI-Study-Assistant_](https://github.com/Bharadwaj1433/StudyGenius-AI-Study-Assistant_)

---
# ✨ Features

## 📚 Multi-Document Contextual Learning
- Upload multiple documents simultaneously.
- Combines content from all uploaded files into a unified study module.
- Supports:
  - PDF
  - DOCX
  - TXT
  - PPTX
  - Images

---

## 🎯 Auto Topic & Chapter Detection

- Automatically detects chapters and important topics.
- Generate quizzes for specific chapters or the entire document.
- Smart topic segmentation for better learning.

---

## 📝 AI Summary Generator

- Generates concise and easy-to-understand summaries.
- Highlights important concepts.
- Saves study time while maintaining context.

---

## 🧠 Interactive Mind Maps

- Converts textual information into interactive visual mind maps.
- Built using D3.js.
- Helps understand relationships between concepts quickly.

---

## 🎙️ AI Study Podcasts

- Converts study notes into realistic AI-generated conversations.
- Multi-speaker podcast generation.
- Enables hands-free learning while traveling or multitasking.

---

## ❓ AI Quiz Generator

- Automatically creates quizzes from uploaded content.
- Multiple Choice Questions
- Topic-based quizzes
- Chapter-wise assessments

---

## 🔍 Content Integrity

- Sentence-level similarity checking.
- Helps verify summary accuracy.
- Reduces duplicate or repetitive content.

---

## 🔐 Authentication & Security

- Firebase Authentication
- Multi-Factor Authentication (MFA)
- SHA-256 Token Hashing
- Rate Limiting
- Automated Security Audit Suite

---

## ☁️ Hybrid Storage

- Firebase Firestore for authenticated users.
- LocalStorage support for Guest Mode.
- Seamless switching between guest and authenticated sessions.

---

# 🛠 Tech Stack

## Frontend

- React 19
- TypeScript
- Tailwind CSS
- Vite
- Lucide React Icons

---

## Backend

- Node.js
- Express.js
- Multer

---

## AI Services

- Google Gemini 2.0 Pro
- Google Gemini 2.5 Flash
- Google AI Studio SDK

---

## Database & Authentication

- Firebase Firestore
- Firebase Authentication

---

## Deployment

- Netlify
- Netlify CLI

---

# 📂 Project Structure

```
StudyGenius-AI/
│
├── components/
├── services/
├── views/
├── migrated_prompt_history/
├── App.tsx
├── firebase.ts
├── server.ts
├── package.json
├── vite.config.ts
└── README.md
```

---

# ⚙️ Local Setup

## Prerequisites

- Node.js (v18 or above)
- Google AI Studio API Key

---

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/studygenius-ai.git

cd studygenius-ai
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

## 3️⃣ Configure Environment Variables

Create a `.env` file in the project root.

```env
GEMINI_API_KEY=your_google_ai_api_key

PORT=3000

NODE_ENV=development
```

---

## 4️⃣ Start Development Server

```bash
npm run dev
```

Visit

```
http://localhost:5173
```

---

# 🚀 Production Deployment (Netlify)

## Install Netlify CLI

```bash
npm install -g netlify-cli
```

---

## Login

```bash
netlify login
```

---

## Build Project

```bash
npm run build
```

---

## Configure Environment Variable

```bash
netlify env:set GEMINI_API_KEY your_google_ai_api_key
```

---

## Deploy

```bash
netlify deploy --prod
```

When prompted:

```
Publish Directory:
dist
```

---

# 🔒 Security

- Multi-Factor Authentication (MFA)
- SHA-256 Secure Token Hashing
- Secure Session Management
- Browser Session Validation
- Rate Limiting
- OWASP Security Best Practices
- GDPR-Friendly Data Management
- User Data Export Support
- Permanent Account Deletion

---

# 📌 Future Enhancements

- AI Flashcards
- Study Progress Tracking
- Personalized Learning Paths
- AI Tutor Chat
- Collaborative Study Groups
- Mobile Application
- Offline Learning Support

---

# 👨‍💻 Developer

**Bharadwaj Rachakonda**

- Full Stack Developer
- AI & Machine Learning Enthusiast
- B.Tech CSE Student

GitHub:
https://github.com/Bharadwaj1433

---

# 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
