# AI Resume Builder

A full‑stack AI-powered resume builder that allows users to create, enhance, preview, download, and share professional resumes online.

## 🚀 Features
- User authentication (Signup/Login)
- Create multiple resumes
- Live resume preview
- AI-enhanced:
  - Professional Summary
  - Experience Description
  - Auto-extracted resume from uploaded PDF
- Multiple resume templates
- Theme color customization
- Profile image upload + background removal (ImageKit)
- Publish resume publicly with a shareable link
- Download as PDF

## 🌐 Live Demo Links

- **Frontend:** https://ai-resume-builder-rho-gold.vercel.app/
- **Backend:** https://ai-resume-builder-backend-wq1m.onrender.com/


## 🛠️ Tech Stack

### Frontend
- React (Vite)
- TailwindCSS
- React Router
- Lucide Icons
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer (File Upload)
- ImageKit (Background Removal)
- Google Gemini API (AI Enhancements)

### Deployment
- Backend → Render
- Frontend → Vercel

## 📦 Project Structure
```
AI-Resume-Builder/
│── client/       # React Frontend
│── server/       # Node.js Backend
│── README.md
```

## 🔧 Environment Variables

### Frontend (.env)
```
VITE_BASE_URL=https://your-backend-url.onrender.com
```

### Backend (.env)
```
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret
IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
IMAGEKIT_URL_ENDPOINT=
GEMINI_API_KEY=
```

## ▶️ Running Locally

### Frontend
```bash
cd client
npm install
npm run dev
```

### Backend
```bash
cd server
npm install
npm start
```


## 📄 License
MIT License
