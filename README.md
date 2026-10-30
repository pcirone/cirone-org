# Cirone.org — Ode to Holli

A timeless, editorial web tribute to Holli featuring Sonnet 65 by William Shakespeare, the original video melody by Paul Cirone, and cherished memories.

---

## 🚀 Running Locally

The local server is lightweight and has zero external npm dependencies. It runs on native Node.js:

```bash
# Start server
node server.js
```

Or:

```bash
npm start
```

Then open your browser to:
👉 **[http://localhost:3010](http://localhost:3010)**

---

## 📁 File Structure

* `index.html` — The complete modern web page (responsive, styled with editorial typography, lightbox gallery, custom video frame, and clean modular sections).
* `server.js` — High-speed, zero-dependency Node.js HTTP server.
* `assets/`
  * `photo-1.jpg` — Portrait memory I
  * `photo-2.jpg` — Portrait memory II
  * `favicon.jpg` — Site favicon
* `.gitignore` — Ignores temporary files and the `old_site/` archive.

---

## ✏️ Adding / Editing Content Later

* **To add more photos:** Simply drop your images into the `assets/` folder and copy an existing `.gallery-card` block in `index.html`.
* **To change text or verses:** Edit `index.html` directly. All sections (`#poem`, `#video`, `#gallery`) are clearly commented and cleanly structured.

---

## 🌐 Deploying to GitHub & Live Web (When Ready)

When you are ready to publish:
1. Initialize git and push to a new GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for cirone.org"
   git remote add origin https://github.com/<your-username>/cirone.org.git
   git push -u origin main
   ```
2. In GitHub repository **Settings $\rightarrow$ Pages**:
   * Set Source to **Deploy from a branch (`main` / root)**.
   * Under **Custom domain**, enter `cirone.org` (and check "Enforce HTTPS").
3. Update GoDaddy DNS to point `cirone.org` and `www.cirone.org` to GitHub Pages.
