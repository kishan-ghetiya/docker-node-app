# 🚀 Docker Node.js App

A simple Node.js Express application packaged with Docker and integrated with GitHub Actions for CI/CD.  
This project demonstrates how to containerize a Node.js app and automate Docker image builds and pushes to DockerHub.

---

## 📦 Features

- ✅ Basic Express.js web server (`GET /`)
- 🐳 `Dockerfile` for containerization
- 🔥 `.dockerignore` to optimize image size
- ⚙️ GitHub Actions workflow for:
  - Auto Docker build on push
  - Auto DockerHub image push

---

## 📁 Tech Stack

- Node.js  
- Express.js  
- Docker  
- GitHub Actions (CI/CD)  
- DockerHub  

---

## 🛠 How to Run

### 📍 Build and Run Locally with Docker:

```bash
docker build -t docker-node-app .
docker run -p 3000:3000 docker-node-app
