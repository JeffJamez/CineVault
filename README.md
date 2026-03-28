# 🎬 CineVault
> A modern, full-stack movie discovery application built with JavaScript, Node.js, and RESTful APIs.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-f7df1e?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-14+-339933?logo=node.js)](https://nodejs.org/)

---

## ✨ Overview

**CineVault** is a responsive web application that allows users to browse, search, and explore movies with real-time data from [The Movie Database (TMDB) API](https://www.themoviedb.org/documentation/api). Built with a clean separation of concerns between frontend and backend, this project demonstrates modern full-stack development practices.

---

## 🚀 Key Features

✅ **Dynamic Movie Search** – Real-time search with debounced API calls  
✅ **Trending & Popular Movies** – Curated lists fetched from TMDB  
✅ **Responsive UI** – Mobile-first design with CSS Grid/Flexbox  
✅ **Modular Architecture** – Clean separation: `/frontend` + `/backend`  
✅ **Environment Configuration** – Secure API key management via `.env`  
✅ **Error Handling & Loading States** – Polished UX with feedback  
✅ **RESTful Backend** – Node.js/Express proxy layer for API requests  

*(Customize based on what your app actually does)*

---

## 🛠 Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript (ES6+), Fetch API |
| **Backend** | Node.js, Express.js, Axios |
| **API** | TMDB API (v3) |
| **Tooling** | npm, ESLint, Git, dotenv |
| **Deployment** | [Netlify/Vercel/Heroku – pick yours] |

---

## 📦 Installation & Setup

### Prerequisites
- Node.js v14+ 
- npm or yarn
- TMDB API key ([get one free](https://www.themoviedb.org/settings/api))

### Steps
```bash
# 1. Clone the repository
git clone https://github.com/JeffJamez/Movie-App.git
cd Movie-App

# 2. Install dependencies
npm install

# 3. Configure environment variables
# Create a .env file in /backend with:
TMDB_API_KEY=your_api_key_here
PORT=3000

# 4. Start the development server
npm run dev
# or start frontend/backend separately:
cd frontend && npm start
cd ../backend && npm start
