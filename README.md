# Personal Portfolio — Sai Madhavi

A responsive, single-page portfolio website (HTML/CSS/JS, no framework) with a
light/dark theme, built to showcase machine-learning & computer-vision work.

## ✏️ Before you publish — fill in the placeholders

Search `index.html` for **`EDIT ME`** and update:

- Your name, headline, and bio
- **LinkedIn URL** (replace `YOUR-LINKEDIN`)
- A **public email** you're comfortable sharing (replace `your.email@example.com`)
- Education / current role / location in the "About" facts list
- Any additional projects (duplicate a project card, or delete the placeholders)

## 👀 Preview locally

Just open `index.html` in a browser, or serve it:

```bash
python -m http.server 5500
# then visit http://localhost:5500
```

## 🚀 Deploy free on GitHub Pages

The simplest setup is a **user site**, served at `https://<username>.github.io`:

1. Create a new GitHub repo named exactly **`Madhavi-30.github.io`**
   (empty — no README/license).
2. From this folder:

   ```bash
   git init -b main
   git add .
   git commit -m "Add personal portfolio site"
   git remote add origin https://github.com/Madhavi-30/Madhavi-30.github.io.git
   git push -u origin main
   ```

3. In the repo: **Settings → Pages → Source = "Deploy from a branch" →
   Branch = `main` / `root`**, then Save.
4. Wait ~1 minute, then open **https://madhavi-30.github.io** 🎉

To publish it inside an existing project repo instead, put these files in a
`/docs` folder and set Pages → Source to the `docs/` folder.

## Structure

```
portfolio/
├── index.html   # content (edit the EDIT ME markers)
├── style.css    # theme, layout, responsive rules
├── script.js    # theme toggle + scroll reveal
└── assets/      # drop images / screenshots here
```
