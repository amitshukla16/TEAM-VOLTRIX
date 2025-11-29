Precise Summary – Personal Finance Tracker

A full-stack finance management web app with secure authentication, transaction tracking, category management, and analytics.

🌐 Live

Frontend (Vercel) – finance-tracker-smoky-seven.vercel.app

Backend (Render) – finance-tracker-oo3x.onrender.com

Health Check – /api/v1/health

🚀 Key Features

User Auth with JWT

Add/Edit/Delete Transactions

Custom Categories for income/expenses

Dashboard Analytics (charts + monthly summary)

PDF/CSV Export

Responsive UI using Tailwind + DaisyUI

State Management via Zustand

Secure Backend with Express + MongoDB

🛠️ Tech Stack
Frontend

React, Vite, Tailwind, DaisyUI, Chart.js, Zustand, Axios.

Backend

Node.js, Express.js, MongoDB (Mongoose), JWT, bcryptjs.

DevOps

Docker, ESLint, Nodemon.

⚙️ Setup Steps


Add .env for backend + optional frontend.

Start using Docker (docker-compose up --build)
OR
Manual Start (npm install → npm run dev for both frontend & backend)

🔍 Verification

Backend health: /api/v1/health

Frontend: localhost:5173

Create user → login → add transaction → check dashboard.

🐳 Useful Docker Commands

Start: docker-compose up

Rebuild: docker-compose up --build

Stop: docker-compose down

🎨 App Usage

Register/Login

Add/edit/delete transactions

Create categories

View analytics (pie chart, bar chart, summary)

Export PDF/CSV reports

🚀 Deployment

Frontend on Vercel with VITE_BACKEND_URL.

Backend on Render with MongoDB Atlas.

Proper CORS + secure cookies configured for cross-domain apps.

follow the given link to see deployment :  https://finance-tracker-smoky-seven.vercel.app/

🐛 Troubleshooting

Check MongoDB URL

Fix CORS issues

Clear cookies for auth problems

Rebuild Docker if ports conflict"# TEAM-VOLTRIX" 
