# Moroccan Vibes

A small, modern landing page that links to selected TikTok videos.

## Files

- `index.html` — main page
- `styles.css` — site styles
- `.github/workflows/deploy.yml` — optional GitHub Actions workflow to publish to `gh-pages` on push to `main`

## Deploy to GitHub Pages (quick)

1. Create a new GitHub repository and push these files to the `main` branch.

```powershell
git init
git add .
git commit -m "Initial site"
git branch -M main
gh repo create <repo-name> --public --source=. --remote=origin --push
```

2. Option A — Use the included workflow: the action will deploy to `gh-pages` after pushes to `main`.

3. Option B — In GitHub Settings > Pages choose `main` branch and `/ (root)` as source to serve from `main`.
