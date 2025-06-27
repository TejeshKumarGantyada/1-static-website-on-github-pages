# 🚀 Static Website on GitHub Pages

This is a beginner-friendly DevOps project that demonstrates how to build, version control, and deploy a static portfolio website using **Git**, **GitHub**, **GitHub Pages**, and **GitHub Actions**.

---

## 🌟 Project Goals

* ✅ Learn Git basics: `init`, `add`, `commit`, `push`
* ✅ Host a static website for free using GitHub Pages
* ✅ Set up CI/CD with GitHub Actions for auto-deployment

---

## 🌐 Live Project

👉 [Click here to visit the live portfolio](https://tejeshkumargantyada.github.io/1-static-website-on-github-pages/)

---

## 🛠️ Technologies Used

* HTML5 & CSS3
* Git & GitHub
* GitHub Pages
* GitHub Actions

---

## 🧰 Folder Structure

```
1-static-website-on-github-pages/
├── index.html
├── style.css
├── README.md
├── assets/
│   └── screenshot.png  # Optional screenshot
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions for auto-deploy
```

---

## 📸 Website Preview

![Portfolio Screenshot](assets/screenshot.png)

---

## ⚙️ Step-by-Step Setup Instructions

### ✅ Step 1: Clone the Repository

```bash
git clone https://github.com/TejeshKumarGantyada/1-static-website-on-github-pages.git
cd 1-static-website-on-github-pages
```

---

### ✅ Step 2: Create/Edit Your Portfolio

Edit the `index.html` and `style.css` files as you like.

```bash
# After making changes, run these:
git add .
git commit -m "Update portfolio content"
```

---

### ✅ Step 3: Push Your Changes

```bash
git push origin main
```

GitHub Actions will automatically deploy your changes to GitHub Pages.

---

### ✅ Step 4: GitHub Actions Auto-Deploy

The `.github/workflows/deploy.yml` file contains the automation logic. It:

* Triggers on every push to the `main` branch
* Publishes the latest version of your site to GitHub Pages

---

### ✅ Step 5: View Your Live Website

Go to:

```
https://<your-username>.github.io/<repo-name>/
```

Example:

```
https://tejeshkumargantyada.github.io/1-static-website-on-github-pages/
```

---

## 💬 Feedback & Suggestions

Feel free to open an issue or reach out via [GitHub profile](https://github.com/TejeshKumarGantyada)!

---
