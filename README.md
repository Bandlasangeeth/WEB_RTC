# Meetify — Full Stack Video Conferencing App

Meetify is a full-stack web application for **real-time video conferencing** with multi-user support, live chat, and responsive UI. Built using **React, Node.js, Socket.io, and MongoDB**, it provides a scalable and modern solution for seamless online communication.

## 🚀 Tech Stack
- **Frontend:** React, Material UI, React Router, Socket.io Client  
- **Backend:** Node.js, Express, Socket.io, MongoDB (Mongoose)  
- **Deployment:** Render.com  

## 📁 Project Structure
├── backend/
│   ├── src/
│   │   ├── app.js              # Express + Socket.io server
│   │   ├── controllers/        # Socket & user controllers
│   │   ├── models/             # Mongoose models
│   │   └── routes/             # API routes
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── pages/              # Route-level components
│   │   ├── components/         # Reusable UI components
│   │   ├── contexts/           # React contexts (Auth)
│   │   ├── styles/             # CSS Modules
│   │   └── environment.js      # Backend URL config
│   └── package.json
├── render.yaml                 # Render Blueprint config
└── .gitignore


## 🏃 Running Locally
**Backend**
```bash
cd backend
npm install
npm run dev


Runs on: http://localhost:8000

Frontend

bash
cd frontend
npm install
npm start


Runs on: http://localhost:3000

☁️ Deploying to Render
Option A — Blueprint (Recommended)

Push repo to GitHub

Render Dashboard → New → Blueprint

Connect GitHub repo

Render auto-detects render.yaml

Set env vars manually:

Backend

MONGO_URI → MongoDB connection string

CLIENT_URL → Frontend Render URL



Runs on: http://localhost:3000

☁️ Deploying to Render
Option A — Blueprint (Recommended)

Push repo to GitHub

Render Dashboard → New → Blueprint

Connect GitHub repo

Render auto-detects render.yaml

Set env vars manually:

Backend

MONGO_URI → MongoDB connection string

CLIENT_URL → Frontend Render URL
Code
