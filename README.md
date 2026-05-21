# Portfolio

A personal developer portfolio showcasing projects built with React, Gemini API, Babel, and more.

## 🚀 Deploy to GitHub Pages

### Option A — Simple (no build step needed)

1. Create a new GitHub repo named `your-username.github.io` (replace with your GitHub username)
2. Drop all three files into the repo root:
   - `index.html`
   - `style.css`
   - `main.js`
3. Go to **Settings → Pages → Source** and set it to `main` branch, `/ (root)`
4. Your site will be live at `https://your-username.github.io`

### Option B — Project sub-page

1. Create any public repo (e.g. `portfolio`)
2. Add the three files to the repo root
3. Enable GitHub Pages from **Settings → Pages**
4. Live at `https://your-username.github.io/portfolio`

## ✏️ Customization

- **Your name / email**: open `index.html` and update the hero `<h1>`, hero subtitle, and the `mailto:` link in the contact section
- **Add more projects**: copy an `<article class="project-card">` block and update the content + iframe `src`
- **Colors**: all colors are CSS variables at the top of `style.css` — change `--accent` and `--accent2` to restyle the whole site instantly

## 📁 File Structure

```
portfolio/
├── index.html   ← all markup
├── style.css    ← all styles
├── main.js      ← scroll animations & cursor glow
└── README.md    ← this file
```

No dependencies. No build step. Pure HTML/CSS/JS.
