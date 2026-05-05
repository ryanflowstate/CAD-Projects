# How to Upload This Repository to GitHub

## Option 1: Upload through GitHub website

1. Create a new repository on GitHub named `cad-portfolio`.
2. Click **Add file** → **Upload files**.
3. Drag this folder's contents into GitHub.
4. Commit the files.

## Option 2: Upload through Terminal

```bash
git init
git add .
git commit -m "Initial CAD portfolio"
git branch -M main
git remote add origin https://github.com/YOURUSERNAME/cad-portfolio.git
git push -u origin main
```

## What to Add Next

For each project, add:

- 1 screenshot or render in `images/`
- 1 drawing PDF in `drawings/`
- 1 CAD file or STEP export in `cad-files/`
- A short explanation in the project README
