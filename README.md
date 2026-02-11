<h1 align="center">📚 AI-Powered Learning Assistant App</h1>
<h3 align="center">Full-Stack MERN Application with Google Gemini AI</h3>

<p align="center">
An AI-powered learning assistant built using the <b>MERN Stack (MongoDB, Express, React, Node.js)</b> integrated with <b>Google Gemini AI</b> to help students upload study materials, interact with documents, generate summaries, flashcards, quizzes, and track their learning progress.
</p>

---

## 🚀 Features

### 🔐 User Authentication
- Secure user registration and login  
- JWT-based authentication  
- Password hashing using bcrypt  
- Protected routes with middleware  
- Persistent login sessions  

---

### 📂 PDF Upload & Management
- Upload study materials in PDF format  
- File size tracking  
- Store file metadata in MongoDB  
- Organized document management  
- Delete and manage uploaded documents  

---

### 📖 Embedded PDF Viewer
- View PDFs directly inside the application  
- No need to download files  
- Smooth and responsive document rendering  
- In-app reading experience  

---

### 🤖 AI-Powered Chat (Google Gemini)
- Context-aware Q&A based on uploaded document  
- Conversational AI experience  
- Intelligent response generation  
- Document-based contextual understanding  

---

### 📝 AI Document Summary
- Generate concise summaries of entire PDFs  
- One-click summary generation  
- Helpful for quick revision  
- Structured and readable output  

---

### 🧠 AI Concept Explainer
- Ask for detailed explanations of specific topics  
- Deep breakdown of difficult concepts  
- Easy-to-understand AI responses  

---

### 🗂️ Auto-Generated Flashcards
- Automatically extract important concepts  
- Generate flashcard sets from documents  
- Flip animation for interactive learning  
- Save and manage flashcards  
- Mark flashcards as favorites  

---

### ❓ AI Quiz Generator
- Generate multiple-choice quizzes  
- Custom question count selection  
- Context-aware question generation  
- Intelligent answer options  

---

### 📊 Quiz Results & Analytics
- Score tracking  
- Correct answer review  
- Explanation for each answer  
- Performance insights  

---

### 📈 Progress Tracking Dashboard
- Total documents uploaded  
- Total flashcards created  
- Total quizzes attempted  
- Recent activity feed  
- Learning analytics overview  

---

### ❤️ Favorites System
- Mark important flashcards  
- Quick-access review section  
- Personalized revision system  

---

### 📱 Responsive UI
- Modern UI built with Tailwind CSS  
- Fully responsive (mobile, tablet, desktop)  
- Clean and intuitive design  
- Smooth animations and transitions  

---

# 🏗️ Tech Stack

## 🎨 Frontend
- React.js  
- Tailwind CSS  
- Axios  
- React Router DOM  
- React PDF Viewer  

## ⚙️ Backend
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JWT Authentication  
- Multer (File Upload Handling)  

## 🤖 AI Integration
- Google Gemini API  
- Context-based prompt engineering  
- Dynamic content generation  

---

# 🧠 System Architecture

Client (React + Tailwind)
↓
Express Server (Node.js)
↓
MongoDB Database
↓
Google Gemini API


## 🔄 Application Flow

1. User uploads PDF  
2. Server extracts text  
3. Text stored in database  
4. User asks question / generates summary / quiz  
5. Backend sends context to Gemini API  
6. AI response returned to frontend  

---

# 🔐 Authentication Flow

1. User registers  
2. Password hashed with bcrypt  
3. JWT token generated  
4. Token stored in localStorage  
5. Protected routes validate token via middleware  

---
