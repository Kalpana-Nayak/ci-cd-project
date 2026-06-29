# CI/CD Pipeline with GitHub Actions & Docker

## 📌 Project Overview

This project demonstrates a complete CI/CD pipeline using GitHub Actions and Docker. Every time code is pushed to the main branch, GitHub Actions automatically builds the application, creates a Docker image, and pushes it to Docker Hub.

---

## 🚀 Features

- Automated CI/CD pipeline
- GitHub Actions workflow
- Docker containerization
- Automatic Docker image build
- Automatic Docker Hub image push
- Node.js application

---

## 🛠 Technologies Used

- Node.js
- Docker
- Docker Hub
- GitHub Actions
- Git
- GitHub

---

## 📂 Project Structure

```
.
├── .github/
│   └── workflows/
│       └── main.yml
├── Dockerfile
├── docker-compose.yml
├── app.js
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ How to Run

Clone the repository

```bash
git clone https://github.com/Kalpana-Nayak/ci-cd-project.git
```

Go to project directory

```bash
cd ci-cd-project
```

Install dependencies

```bash
npm install
```

Run the application

```bash
node app.js
```

---

## 🐳 Run using Docker

Build the image

```bash
docker build -t cicd-app .
```

Run the container

```bash
docker run -p 3000:3000 cicd-app
```

---

## 🔄 CI/CD Workflow

1. Push code to GitHub
2. GitHub Actions starts automatically
3. Install dependencies
4. Run application
5. Build Docker image
6. Login to Docker Hub
7. Push Docker image

---

## 🐋 Docker Hub Image

https://hub.docker.com/r/dockalpana/cicd-app

---

## 👩‍💻 Author

**Kalpana Nayak**
