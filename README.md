# GitHub Pages Deployment

This folder is ready to deploy as a static GitHub Pages site. The entry point is `index.html`, and all linked files live alongside it.

## One-time setup
1. Create a new GitHub repository (public or private).
2. From this folder, run:

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

## Enable GitHub Pages
1. Open the repository on GitHub.
2. Go to Settings -> Pages.
3. Under "Source", choose "Deploy from a branch".
4. Select `main` and `/ (root)`, then save.

## Update the site
```bash
git add .
git commit -m "Update site"
git push
```
