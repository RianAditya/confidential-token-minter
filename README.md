# Confidential Token Minter

A full-stack blockchain app for minting confidential tokens using zk-SNARKs.  
Built with React (frontend), Express (backend), MongoDB, JWT Auth, and Docker.

## 🚀 Features

- Scaffolded frontend using React
- Backend API using Express + MongoDB
- JWT-based user authentication system
- Dockerized development environment
- Ready for zero-knowledge proof (zk-SNARKs) integration

## 📦 Tech Stack

- **Frontend:** React
- **Backend:** Node.js, Express
- **Database:** MongoDB with Mongoose
- **Auth:** JWT
- **Infra:** Docker, Docker Compose

## 📁 Project Structure

```bash
confidential-token-minter/
├── backend/            # Express backend
├── frontend/           # React frontend
└── docker-compose.yml  # Full stack orchestration
```

## 📜 Scripts

### Docker

```bash
docker-compose up        # Start frontend + backend + MongoDB
docker build -t confidential-backend ./backend  # Build backend only
```

### Local

```bash
cd backend
node app.js              # Start backend
```

## ✅ Setup Steps

1. Clone the repository
2. Add `.env` file in `backend/`:
   ```env
   MONGO_URI=mongodb://localhost:27017/confidential-token-minter
   JWT_SECRET=yourSuperSecretKey
   ```
3. Run backend with Docker or locally

---

© 2025 Confidential Token Minter Project
