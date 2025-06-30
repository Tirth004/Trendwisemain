
# 📰 TrendWise - AI-Powered Trending Blog Platform

TrendWise is a full-stack SEO-optimized blog platform that:
- 🚀 Fetches trending topics (Google Trends)
- 🤖 Uses OpenAI (ChatGPT) to generate SEO articles
- 🌐 Displays them in a blog-style frontend (Next.js)
- 🔐 Supports Google login (NextAuth)
- 💬 Allows authenticated users to comment

---

## 🛠 Tech Stack

| Layer       | Technology                      |
|-------------|----------------------------------|
| Frontend    | Next.js 14+, TailwindCSS         |
| Auth        | NextAuth.js (Google login)       |
| Backend     | Express.js, OpenAI API, Puppeteer|
| Database    | MongoDB, Mongoose                |
| Deployment  | Vercel (Frontend), Render (Backend) |

---

## 🔧 Features

- ✅ Fetches Google Trends using Puppeteer
- ✅ Generates articles using OpenAI GPT-4
- ✅ Stores articles in MongoDB
- ✅ SEO-friendly meta tags and OG tags
- ✅ Dynamic sitemap & robots.txt (optional)
- ✅ Google Authentication with protected routes
- ✅ Comment system for logged-in users

---

## 🚀 Getting Started

### 📁 1. Clone the repo

```bash
git clone https://github.com/yourusername/trendwise.git
cd trendwise
```

### 🖥 2. Frontend Setup

```bash
cd frontend
npm install
cp .env.local.example .env.local  # Add your Google Auth credentials
npm run dev
```

### 🔌 3. Backend Setup

```bash
cd backend
npm install
cp .env.example .env  # Add your MongoDB and OpenAI API keys
node index.js
```

---

## 🌍 Live Demo

- Frontend: https://trendwise-frontend.vercel.app
- Backend: https://trendwise-backend.onrender.com

---

## 📄 Environment Variables

### `.env.local` (Frontend)

```
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
NEXTAUTH_SECRET=your_secret
```

### `.env` (Backend)

```
MONGO_URI=your_mongodb_uri
OPENAI_API_KEY=your_openai_api_key
```

---

## 🤝 Contribution

Want to contribute or suggest a feature? Fork the repo or raise an issue!

---

## 📬 Contact

Made by [Your Name](https://github.com/yourusername)  
Powered by OpenAI + Google Trends
