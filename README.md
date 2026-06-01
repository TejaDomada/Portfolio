# Teja Domada — Personal Portfolio Website

A premium, fully animated, dark-themed personal portfolio built from resume data.

## ✨ Features

- **Animated particle background** with interactive mouse tracking
- **Typing animation** cycling through professional roles
- **Scroll-triggered reveal animations** on all sections
- **Animated skill progress bars** with percentage indicators
- **Interactive timeline** for experience
- **Project cards** with hover effects
- **GitHub language visualization**
- **Animated counters** for stats
- **Contact form** with submit feedback
- **Responsive** — desktop, tablet, and mobile
- **SEO optimized** meta tags

## 🚀 Deployment Options

### Option 1: Vercel (Recommended — Free)

1. Go to [vercel.com](https://vercel.com) and sign up with GitHub
2. Drag and drop this folder, OR push to GitHub first:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```
3. In Vercel → **New Project** → Import your GitHub repo
4. Click **Deploy** — that's it!

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag the `portfolio` folder onto the Netlify dashboard
3. Your site is live instantly!

### Option 3: GitHub Pages (Free)

1. Push this folder to a GitHub repo named `YOUR_USERNAME.github.io`
2. Go to **Settings → Pages → Deploy from branch → main**
3. Site goes live at `https://YOUR_USERNAME.github.io`

### Option 4: Local Preview

Simply open `index.html` in any modern browser.

---

## 🔧 Customization

### Update Links
In `index.html`, search for and replace:
- `https://github.com` → your actual GitHub URL
- `#` (portfolio link) → your actual portfolio URL

### Add Real GitHub URL
Replace all instances of `href="https://github.com"` with your actual profile.

### Custom Domain (Vercel)
1. In Vercel project → **Settings → Domains**
2. Add your domain (e.g. `tejadomada.dev`)
3. Update your DNS with the provided records

---

## 📁 Structure

```
portfolio/
├── index.html        # Complete single-file portfolio
└── README.md         # This file
```

All CSS, JavaScript, and HTML are in a single optimized file for zero-dependency deployment.

---

Built with: HTML5 · CSS3 · Vanilla JS · Google Fonts (Syne + DM Mono + Inter)
