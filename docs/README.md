# Full-stack Quasar + Express App

This project demonstrates a full-stack application with:
- **Frontend**: Quasar Framework (Vue.js 3 + Vite)
- **Backend**: Express.js
- **Infrastructure**: Docker & Docker Compose

## Structure

- `frontend/`: Quasar SPA
- `backend/`: Express API
- `docker-compose.yml`: Orchestration

## Getting Started

1. **Run with Docker**:
   ```bash
   docker compose up --build
   ```
2. **Access**:
   - Frontend: [http://localhost:8080](http://localhost:8080)
   - Backend API: [http://localhost:3000/api/demo](http://localhost:3000/api/demo)

## Features

- **API Integration**: Frontend fetches data from Backend.
- **Environment Variables**: Configurable API URL.
- **Dockerized**: Multi-stage builds and healthchecks.
- **Logs**: Backend logs persisted in `backend/logs`.
