# AWS Node.js Application with Elastic Beanstalk and CI/CD Pipeline

This repository contains a Node.js application deployed using AWS Elastic Beanstalk, integrated with AWS CodePipeline for continuous integration and deployment (CI/CD). It showcases separate **test** and **production** environments, automated deployment processes, and manual approval steps.

---

## 📌 Project Overview

* **Application Name:** `MyApp`
* **Platform:** Node.js 18
* **Deployment:** AWS Elastic Beanstalk
* **CI/CD Tool:** AWS CodePipeline
* **Source Control:** GitHub

---

## 📁 Repository Structure

```
AWS-Nodejs-Beanstalk-App
├── app
│   ├── index.html
│   └── package.json
└── Pictures
```

---

## 🚀 Features

* ✅ Automated CI/CD via AWS CodePipeline.
* ✅ Separate test and production environments.
* ✅ Manual approval required before deploying to production.

---

## ⚙️ AWS Components

### 🌿 Elastic Beanstalk

* **Test Environment:**

  * Node.js version: 18.x

* **Production Environment:**

  * Node.js version: 18.x

### 🔄 CodePipeline

* Pipeline name: `My-CICD`
* Linked to GitHub repository.
* Automatic deployment to test on each commit.
* Manual approval step for deploying to production.

---

## 🛠 Deployment Workflow

1. **Commit Changes:** Push code changes to GitHub

📸 Screenshots

Check screenshots in the repository illustrating:

Application setup

Environments

CI/CD Pipeline

Test Environment

Production Environment
