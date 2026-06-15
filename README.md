# Seungdong Yoa — Personal Site

Single-file static personal page (`index.html`). No build step, no dependencies.

## Preview locally
Just open the file:
```
open index.html
```
…or serve it (so relative links/SEO behave like production):
```
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy (any of these — all free)
- **GitHub Pages**: push this folder to a repo → Settings → Pages → deploy from branch.
- **Vercel / Netlify**: drag-and-drop the folder, or connect the repo. Auto-detects static.

## Before going live — checklist
- [ ] Replace the two **Google Scholar** placeholder links (`href="#"`) — Research section + Contact.
- [ ] Fill in real **venture descriptions** (Effectgen / Effectgen Homeliving / AgentMon). Add live URLs if any.
- [ ] Set your real domain in the `<link rel="canonical">` and Open Graph `og:url` tags (currently `seungdongyoa.com`).
- [ ] (Optional) Add a 1200×630 `og.png` share image and uncomment the `og:image` meta tag.
