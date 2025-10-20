# Adripple — Creative Digital Studio

Adripple is a modern web design and development studio helping brands make waves online. This repository contains the full static site for **adripple.vercel.app**, ready for deployment on GitHub Pages or Vercel.

---

## 🚀 Quick Start

### 1. Clone this repo
```
git clone https://github.com/calkoek-sudo/adripple.git
cd adripple
```

### 2. Deploy to Vercel
If you haven’t yet:
```
npm i -g vercel
vercel
```
Follow prompts and link your project.

Or, use GitHub Pages:
- Push your repository.
- In GitHub → Settings → Pages → Source: `main / root`.

---

## 🧱 Project Structure

```
adripple/
├── index.html          # Main static site file
├── README.md           # This documentation
└── .gitignore          # Standard Node/Vercel ignores
```

---

## 🧩 Features
- Responsive layout (mobile-first)
- Modern minimalist UI (Inter font, gradients, glassmorphism)
- SEO and AdSense meta tags
- About, Services, Portfolio, Insights, Contact, and Privacy pages
- Simple built-in mailto contact form
- Ready for Google AdSense review

---

## 💰 AdSense Readiness Checklist
Before requesting AdSense review:
1. Ensure all text is unique and high-quality.
2. Replace any placeholder links (LinkedIn, Behance, email).
3. Include a Privacy Policy (already included).
4. Add your `google-site-verification` meta tag in `<head>`.
5. Redeploy the site via Vercel.
6. Go to AdSense → Sites → `adripple.vercel.app` → **Request Review**.

---

## 🧠 SEO + Performance Tips
- Use descriptive page titles and meta descriptions.
- Optimize images before uploading.
- Add Open Graph images for social previews.
- Use internal links between sections.
- Add your sitemap.xml if you grow the site.

---

## 🛠️ Customization
- Update colors in the `:root` CSS variables at the top of `index.html`.
- Replace 💧 emoji logo with an SVG or PNG logo.
- To separate files: move `<style>` into `styles.css` and `<script>` into `app.js`.

---

## 👥 Credits
Designed and developed by **Adripple Team** — South Africa 🇿🇦  
Built with ❤️ and HTML5, CSS3, and vanilla JS.

---

## 📜 License
MIT License — Free to use, modify, and share.

---

## .gitignore
```
# Node / Vercel / Build ignores
node_modules/
.vercel/
.env
.env.local
.DS_Store
*.log
dist/
.cache/
.vscode/
```

---

**Next Step:**
- Commit and push:
```
git add .
git commit -m "Adripple initial site setup"
git push origin main
```
- Verify AdSense meta tag.
- Redeploy to Vercel.
- Request review after 24–48 hours.

Once approved, you can add your AdSense script snippet before the closing `</head>` tag.