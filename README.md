# tahreemm.github.io

Personal academic website for [Tahreem Yasir](https://github.com/tahreemm).

## Deploy to GitHub Pages

1. Create a new repository on GitHub named **`tahreemm.github.io`** (must match your username exactly).
2. Push this folder to the repository:

```bash
cd tahreemm.github.io
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin git@github.com:tahreemm/tahreemm.github.io.git
git push -u origin main
```

3. In the repo on GitHub, go to **Settings → Pages** and confirm the source is **Deploy from branch: main / (root)**.
4. Your site will be live at **https://tahreemm.github.io** within a few minutes.

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080.

## Structure

```
tahreemm.github.io/
├── index.html
├── assets/
│   ├── css/style.css
│   └── js/main.js
└── README.md
```
