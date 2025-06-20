# 🚀 Node.js CI/CD Pipeline with GitHub Actions

This project sets up a CI/CD pipeline using GitHub Actions to automate testing and deployment for a Node.js web app. The application is structured for Heroku deployment with a configured Procfile, and the pipeline installs dependencies, runs tests, and prepares for deployment upon every push to the main branch. This project demonstrates a complete CI/CD pipeline setup for a Node.js web application using **GitHub Actions**. Every code push triggers automated testing and prepares the application for deployment.

---

## 📦 Tech Stack

- **Backend**: Node.js (Express)
- **CI/CD**: GitHub Actions
- **Version Control**: Git & GitHub
- **Deployment-Ready**: Heroku-compatible (Procfile setup)

---

## ⚙️ CI/CD Pipeline Features

- ✅ Automatic workflow triggered on push to `main` branch
- 🛠️ Installs dependencies with `npm install`
- 🧪 Runs tests via `npm test` (currently mocked to always pass)
- 🚀 Includes deployment-ready structure for Heroku
- 📂 `.github/workflows/ci-cd.yml` defines the entire pipeline

---

## 📁 Project Structure

---MyNodeApp/
├── .github/
│ └── workflows/
│ └── ci-cd.yml # GitHub Actions pipeline
├── Procfile # Tells Heroku how to start the app
├── index.js # Main application file
├── package.json # Project metadata & scripts
└── README.md


---

## 🧪 Test Script (Temporary)

The `test` script is currently a placeholder to ensure the pipeline passes:

```json
"scripts": {
  "start": "node index.js",
  "test": "echo \"No tests yet – passing.\" && exit 0"
}
```

## 🚀 Deployment (Optional)

The app is fully prepared for deployment to platforms like **Heroku**, **Render**, or **Railway**.

### ▶️ Deploy to Heroku Manually

```bash
heroku login
heroku create your-app-name
git push heroku main
```

 Note: Heroku now requires payment info to create apps.
 For free options, consider Render or Railway.


