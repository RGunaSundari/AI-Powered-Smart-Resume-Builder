# 🧠 AI Resume Builder

A modern, AI-powered resume builder that helps users create professional resumes with the help of **Google's Gemini AI**. This application makes resume creation easier by offering smart suggestions and automatic formatting.

## 🚀 Features

- ✨ **AI-Powered Resume Generation**  
  Uses Gemini AI to improve and enhance resume content.
  
- 🖥️ **Modern UI/UX**  
  Clean and responsive interface using Shadcn UI components.

- 🔄 **Real-time Preview**  
  Instantly see changes to your resume as you type.

- 🎨 **Multiple Templates**  
  Choose from different professional resume layouts.

- 📥 **Export Options**  
  Download your resume in PDF and other formats.

- 🔐 **User Authentication**  
  Login and manage your profile securely.

- ☁️ **Cloud Storage**  
  Save your resumes for later access and editing.

## 🛠️ Tech Stack

### Frontend
- React
- Tailwind CSS
- Shadcn UI
- React Toastify

### Backend
- Node.js
- Strapi (Headless CMS)
- Neon PostgreSQL

### AI Integration
- Google Gemini AI

### Deployment
- Vercel (Frontend)
- Render/Railway (Backend)

## 📦 Installation
### Step 1: Clone the Repository
git clone https://github.com/yourusername/ai-resume-builder.git
cd ai-resume-builder

### Step 2: Set Up Environment Variables
Create a .env file in both client/ and server/ directories and add:

#### .env (client)
VITE_GEMINI_API_KEY=your_gemini_api_key
#### .env (server)
DATABASE_URL=your_neon_postgres_url

## ▶️ Start Development Servers
### 🖥️ Frontend
cd client
npm install
npm run dev
### 🔧 Backend
cd server
npm install
npm run develop

## 🔧 Configuration
Frontend: http://localhost:5137

Backend (Strapi): http://localhost:3000

Gemini AI: Make sure your API key is active

## 🚧 Project Status
✅ Core functionality: 90% complete

🔧 Footer implementation: In progress

🔍 Testing and optimization: Ongoing

## 🤝 Contributing
Contributions are welcome!
Please fork the repository, make your changes, and submit a Pull Request.

## 🙏 Acknowledgments
Google Gemini AI

Shadcn UI

The open-source community ❤️
