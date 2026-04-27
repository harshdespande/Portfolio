# Harsh Deshpande — Portfolio

Personal portfolio for **Harsh Deshpande** — Data Engineer, Analytics Developer & Software Developer.

🌐 **Live site:** `https://harshdespande.github.io/portfolio/`  
_(URL will be active after GitHub Pages is enabled — see setup below)_

---

## 🚀 Quick Setup (3 Steps)

### Step 1 — Create the GitHub Repository

1. Go to [github.com](https://github.com) and sign in as `harshdespande`
2. Click **New repository**
3. Name it: `portfolio` (or any name you prefer)
4. Set visibility to **Public**
5. Click **Create repository**

### Step 2 — Push This Code

```bash
# In the project folder
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/harshdespande/portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **GitHub Actions**
3. That's it! The workflow will run automatically on every push to `main`

Your portfolio will be live at:
```
https://harshdespande.github.io/portfolio/
```

---

## 📁 Project Structure

```
portfolio/
├── public/
│   ├── index.html        ← Main portfolio page
│   └── resume.pdf        ← Add your resume PDF here
├── .github/
│   └── workflows/
│       └── deploy.yml    ← GitHub Actions auto-deploy
└── README.md
```

---

## ✏️ How to Add Your Resume PDF

1. Save your resume as `resume.pdf`
2. Place it inside the `public/` folder
3. Commit and push — it will be linked automatically via the "Resume ↗" button in the navbar

---

## ✏️ Customisations

All content lives in `public/index.html`. Key things to update:

| What | Where in the file |
|------|------------------|
| Profile photo | Add an `<img>` tag in the hero section |
| Project GitHub links | Update `href` in `.proj-title a` |
| Add more projects | Copy a `.proj-item` block |
| LinkedIn URL | Update `href` in the socials section |

---

## 🤖 Auto-Deploy

Every time you push to `main`, GitHub Actions will automatically:
1. Pick up the `public/` folder
2. Deploy it to GitHub Pages
3. Your live site updates within ~30 seconds

---

Built with plain HTML, CSS & JavaScript — no frameworks, no build step needed.
