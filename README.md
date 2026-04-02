# Publish This Site

This folder is ready for GitHub Pages.

Contents:
- `index.html`
- `foto1.jpeg`
- `foto2.jpeg`
- `foto3.jpg`
- `foto4.jpg`

Quick publish:

```bash
cd publish
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

Then on GitHub:

1. Open the repository
2. Go to `Settings > Pages`
3. Under `Build and deployment`, choose `Deploy from a branch`
4. Select `main` and `/root`
5. Save

Your site will be available after a minute or two at:

`https://YOUR-USERNAME.github.io/YOUR-REPO/`
