# Stephanie Potter — Portfolio

Static HTML/CSS/JS portfolio, ready for GitHub Pages.

## Files
- `index.html` — Home
- `about.html` — About
- `projects.html` — Projects
- `contact.html` — Contact
- `styles.css` — Shared styles
- `script.js` — Mobile nav + active link + footer year

## Deploy to GitHub Pages
1. Create a new repository on GitHub (for example: `portfolio`).
2. Copy every file in this folder into the **root** of the repo (so `index.html` sits at the repo root).
3. Commit and push to the `main` branch.
4. On GitHub, go to **Settings → Pages**.
5. Under **Build and deployment → Source**, pick **Deploy from a branch**.
6. Choose branch **`main`** and folder **`/ (root)`**, then click **Save**.
7. After a minute, your site is live at:
   `https://potterstep.github.io/<repo-name>/`

## Customize
- Update the email on `contact.html`.
- Add a real education entry on `about.html`.
- To embed a YouTube intro video, paste YouTube's `<iframe>` embed code into `about.html` (e.g. below the intro paragraphs).
- To make the contact form actually send, use a service like [Formspree](https://formspree.io) — set the form's `action` to your Formspree endpoint and remove the `onsubmit` handler.
