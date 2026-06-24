# QuickAI🚀

An AI-powered SaaS platform that provides multiple productivity and content-generation tools in one place. Users can generate articles, create blog titles, review resumes, generate AI images, remove image backgrounds, and remove unwanted objects from images.

🌐 Live Demo: https://quick-ai-clone.vercel.app/

---

## Features

### ✍️ AI Article Generator
Generate high-quality articles on any topic using Google's Gemini AI.

### 📝 AI Blog Title Generator
Create SEO-friendly and engaging blog titles instantly.

### 📄 AI Resume Review
Upload a PDF resume and receive detailed AI-powered feedback, strengths, weaknesses, and improvement suggestions.

### 🎨 AI Image Generator
Generate images from text prompts using ClipDrop AI.

### 🖼️ Background Remover
Remove image backgrounds with a single click.

### 🪄 Object Remover
Remove unwanted objects from images using Cloudinary's Generative AI.

### 👤 Authentication & Authorization
Secure user authentication and subscription management powered by Clerk.

### 💳 Premium Plan Support
Free and Premium user plans with usage restrictions for free users.

### 📚 History Management
All generated content is stored and can be accessed later.

---

## Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- Axios
- React Markdown
- Lucide React
- React Hot Toast
- Clerk React

### Backend

- Node.js
- Express.js
- PostgreSQL (Neon)
- Clerk Express
- OpenAI SDK (Gemini API Compatibility Layer)
- Cloudinary
- ClipDrop API
- PDF Parse

### Database

- Neon PostgreSQL

### Authentication

- Clerk

### AI Services

- Google Gemini 2.5 Flash
- ClipDrop API
- Cloudinary AI Transformations

### Deployment

- Frontend: Vercel
- Backend: Render
- Database: Neon

---

## Project Structure


QuickAI-Clone/
│
├── client/                 # Frontend (React + Vite)
│
├── server/                 # Backend (Node + Express)
│
├── README.md
│
└── .gitignore

---

## Installation

### Clone Repository

```bash
git clone https://github.com/girishdhakar/QuickAI-Clone
```

### Move into Project Directory

```bash
cd QuickAI-Clone
```

---

## Frontend Setup

```bash
cd client

npm install

npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

## Backend Setup

```bash
cd server

npm install

npm run dev
```

Backend runs on:

```text
http://localhost:3000
```

---

## Deployment

### Frontend

Deploy the `client` folder to:

- Vercel

### Backend

Deploy the `server` folder to:

- Render

Required Environment Variables must be configured in both services.

---

## Author

### Girish Dhakar

- GitHub: https://github.com/girishdhakar
- LinkedIn: https://www.linkedin.com/in/girish-dhakar-64b59b277/

---

## License

This project is created for educational and portfolio purposes.
