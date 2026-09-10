# Ravishek Kumar — Personal Website

Source code for my personal website, live at **[ravishek.github.io](https://ravishek-projects.github.io/ravishek.github.io/)**.

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
