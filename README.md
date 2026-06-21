# personal-website

Static personal site for Harshal Rudra, deployed on Netlify.

- `index.html` — home page
- `post-*.html` — blog posts
- `support.js` — runtime (loads React/Babel/KaTeX from CDN at runtime)
- `*.png` / `*.jpg` / `*.gif` — blog images, served from the site root

No build step. Netlify publishes the repo root directly (see `netlify.toml`).
