# Deploying to GitHub Pages

1. On GitHub, create a **public** repository named exactly `<your-github-username>.github.io`.
2. Upload everything in this folder (index.html, assets/, .nojekyll) to the repo root, or:

   ```
   cd this-folder
   git init && git add . && git commit -m "Personal website"
   git branch -M main
   git remote add origin https://github.com/<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```
3. Repo Settings -> Pages -> Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Your site goes live at `https://<your-github-username>.github.io` within a minute or two.
