# 🚀 Node.js CI/CD Demo Project

This is a simple Node.js application created to test and demonstrate a complete CI/CD pipeline using:

- GitHub Actions for Continuous Integration & Deployment
- Docker for containerization
- AWS EC2 (Ubuntu Linux Server) for deployment

The purpose of this project is to practice automating build, test, Docker image creation, and deployment workflows.

---

## 📌 Project Overview

This project includes:

- A basic Node.js server (Express app)
- Docker configuration
- GitHub Actions workflow for CI/CD
- Deployment to an AWS Ubuntu EC2 instance

---

## 🏗️ Tech Stack

- Node.js
- Express.js
- Docker
- GitHub Actions
- AWS EC2 (Ubuntu Linux)

---

## 📂 Project Structure

.
├── .github/workflows/
│ └── deploy.yml
├── Dockerfile
├── docker-compose.yaml
├── package.json
├── src/server.js
└── README.md


---

## ⚙️ Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Krunaljumde24/nodejs-application-deploy-github-actions.git
cd nodejs-application-deploy-github-actions

### 1. Install Dependencies
npm install

### 2. Run the Application Locally
npm start

### 3. Express server runs on: 
http://localhost:3000