# Sabavath Suresh — Personal Developer Portfolio

Modern, responsive, cyber-aesthetic developer portfolio engineered for **Sabavath Suresh**, Python Full-Stack Developer & Trainee based in Bengaluru, Karnataka, India.

Built strictly using **semantic HTML5 and modern CSS3** (zero runtime JavaScript or framework bloat) and configured with **GitHub Actions CI/CD** for automated deployment to **GitHub Pages**.

---

## 🌟 Key Features

- **Pure HTML5 & CSS3:** Ultra-fast load times, zero external JS dependencies, 100% accessible and responsive across mobile, tablet, and desktop screens.
- **Modern Cyber Aesthetic UI:** Ambient glow effects, rotating orbital rings, floating tech chips, and custom CSS-rendered browser mockups.
- **Professional Training & Background:** Highlights internship and training at **WebTech Software Solutions** (Bengaluru) and degree studies at **Rajadhani Degree College** (**Bengaluru North University**).
- **Comprehensive Technical Stack:** Detailed showcase of Python 3, Django, SQLite3, HTML5, CSS3, JavaScript, Git, GitHub, VS Code, Postman, and Terminal / Bash.
- **Featured Project:** Complete showcase of the **Google Project (`django_project_blueprint`)** (modular YouTube, Google Maps, and Google Photos layouts).
- **Automated CI/CD Pipeline:** Includes `.github/workflows/deploy.yml` with pre-deployment integrity tests and automated GitHub Pages artifact deployment.
- **Print & PDF Friendly:** Includes clean print styles for exporting directly as a developer resume.

---

## 📁 Repository Structure

```text
suresh-portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml          # Automated CI/CD GitHub Pages workflow
├── assets/
│   ├── suresh-profile.jpg      # Professional profile portrait
│   └── webtech-logo.jpg        # WebTech Software Solutions company logo
├── index.html                  # Semantic, structured HTML5 document
├── style.css                   # Custom responsive CSS3 design system
├── .gitignore                  # Git ignore rules for system/temp files
└── README.md                   # Project documentation & deployment guide
```

---

## 🚀 How to Run Locally

You can preview the portfolio locally using any browser:

### Option 1: Direct File Open
Double-click `index.html` or open it with Google Chrome, Safari, Firefox, or Microsoft Edge.

### Option 2: Local HTTP Server (Python)
From the portfolio directory, run:
```bash
python3 -m http.server 8000
```
Then visit: `http://localhost:8000`

---

## 🌐 Deploying to GitHub Pages with CI/CD

This repository is configured with a **GitHub Actions CI/CD workflow** (`.github/workflows/deploy.yml`). Follow these steps to publish your portfolio online for free:

### Step 1: Commit Changes
In your terminal, navigate to your portfolio folder and run:
```bash
git add .
git commit -m "feat: complete Sabavath Suresh portfolio with new portrait and CI/CD workflow"
```

### Step 2: Push to Your GitHub Repository
```bash
# Add your repository as origin (if not already set)
git remote add origin https://github.com/sabavath7456-stack/suresh-portfolio.git

# Push to main
git push -u origin main
```

### Step 3: Enable GitHub Pages with GitHub Actions
1. On GitHub, navigate to your repository's **Settings** tab.
2. In the left sidebar, click **Pages** (under the "Code and automation" section).
3. Under **Build and deployment** -> **Source**, select:
   👉 **GitHub Actions**
4. GitHub Actions will now automatically run `.github/workflows/deploy.yml` whenever you push changes to `main`.

Your live portfolio will be available at:
`https://sabavath7456-stack.github.io/suresh-portfolio/`

---

## 📬 Contact & Personal Info

- **Name:** Sabavath Suresh
- **Title:** Python Full-Stack Developer & Trainee
- **Location:** Bengaluru, Karnataka, India
- **Email:** [sabavath7456@gmail.com](mailto:sabavath7456@gmail.com)
- **Phone:** [+91 9550831468](tel:+919550831468)
- **GitHub:** [https://github.com/sabavath7456-stack](https://github.com/sabavath7456-stack)
- **Featured Repository:** [https://github.com/sabavath7456-stack/django_project_blueprint](https://github.com/sabavath7456-stack/django_project_blueprint)

---
© 2026 Sabavath Suresh. All Rights Reserved.
