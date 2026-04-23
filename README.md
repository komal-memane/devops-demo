# devops-demo

# 🚀 CI/CD Pipeline with GitHub Actions

<p align="center">
  <img src="https://img.shields.io/badge/CI-CD-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GitHub-Actions-black?style=for-the-badge&logo=githubactions" />
  <img src="https://img.shields.io/badge/HTML-Website-orange?style=for-the-badge&logo=html5" />
  <img src="https://img.shields.io/badge/Status-Live-success?style=for-the-badge" />
</p>

---

## 📌 Project Overview

This project demonstrates a **CI/CD (Continuous Integration & Continuous Deployment)** pipeline using GitHub Actions.
Whenever code is pushed to the repository, the workflow is automatically triggered and the website is deployed.

---

## 🎯 Features

✔️ Automated deployment on every push
✔️ CI/CD pipeline using GitHub Actions
✔️ Static website hosting
✔️ Simple and beginner-friendly DevOps project

---

## 🛠️ Tech Stack

* Git & GitHub
* GitHub Actions
* HTML, CSS
* GitHub Pages

---

## 📂 Project Structure

```bash
devops-demo/
│── index.html
│── .github/
│   └── workflows/
│       └── deploy.yml
```

---

## ⚙️ Workflow Explanation

The CI/CD pipeline is defined in a YAML file:

```yaml
name: Deploy Website

on:
  push:
    branches:
      - main

jobs:
  build-deploy:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout Code
        uses: actions/checkout@v4

      - name: Deploy Website
        run: echo "Website deployed successfully!"
```

---

## 🔄 How It Works

```mermaid
graph LR
A[Developer Push Code] --> B[GitHub Repository]
B --> C[GitHub Actions Triggered]
C --> D[Workflow Runs]
D --> E[Website Deployed]
E --> F[Live Website 🌐]
```

---

## 🌐 Live Demo

👉 https://<your-username>.github.io/devops-demo/

---

## 📸 Preview

<img src="https://via.placeholder.com/800x400.png?text=Project+Preview" alt="Project Preview" />

---

## 💡 Key Learnings

* CI/CD pipeline fundamentals
* Workflow automation using GitHub Actions
* YAML configuration
* Version control with Git
* Deployment using GitHub Pages

---

## 🎤 Interview Q&A

**Q: What is CI/CD?**
A: CI/CD automates integration and deployment of code changes.

**Q: What triggers this pipeline?**
A: A push to the main branch triggers the workflow.

**Q: What is GitHub Actions?**
A: A tool to automate build, test, and deployment workflows.

**Q: What is YAML?**
A: A configuration language used to define workflows.

---

## 🚀 Future Enhancements

* Add testing stage
* Integrate Docker
* Deploy to cloud (AWS)
* Add monitoring

---

