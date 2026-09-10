# Ravishek Kumar — Personal Website

Source code for my personal website, live at **[ravishek.github.io](https://ravishek.github.io)**.

---

## 📁 Repo Structure

```
ravishek.github.io/
├── index.html          # Main single-page website
├── cv.pdf              # CV (keep updated)
├── assets/
│   └── profile.jpg     # Profile photo
└── README.md           # This file
```

---

## ✏️ How to Customize

Open `index.html` and locate the `<!-- ✏️ -->` comment markers:

| Section | What to update |
|---|---|
| `<!-- ABOUT -->` | Bio, research interests, institution |
| `<!-- CV -->` | Path to `cv.pdf` |
| `<!-- PROJECTS -->` | Project title, summary, tech tags, GitHub link |
| `<!-- EDUCATION -->` | Degrees, GPA, coursework |
| `<!-- CONTACT -->` | Email, GitHub, LinkedIn, Google Scholar |

---

## 🚀 Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/Ravishek-Projects/ravishek.github.io.git
git push -u origin main
```

Then go to **Settings → Pages → Source: Deploy from branch → `main` / `root`**.  
The site goes live at `https://ravishek.github.io` within a couple of minutes.

---

## 🔄 Updating the Site

```bash
git add .
git commit -m "Update [section]"
git push
```

GitHub Pages rebuilds automatically on every push — no build step required.

---

## 🛠️ Built With

- Plain HTML
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Inter](https://fonts.google.com/specimen/Inter) — Google Fonts
- [GitHub Pages](https://pages.github.com/) (free hosting)
