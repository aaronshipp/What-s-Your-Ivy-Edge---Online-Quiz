# What's Your Ivy Edge? — Student Assessment

A drag-and-drop personality assessment tool for The Ivy Edge clients.

## Files

- `index.html` — the complete single-page assessment (no build step needed)

## Publish on GitHub Pages

1. **Push the file to your repo:**
   ```bash
   git init
   git add index.html
   git commit -m "Add assessment"
   git branch -M main
   git remote add origin https://github.com/aaronshipp/What-s-Your-Ivy-Edge---Student-Assessment.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repo on GitHub
   - Click **Settings** → **Pages** (left sidebar)
   - Under "Source", select **Deploy from a branch**
   - Choose **main** branch, **/ (root)** folder
   - Click **Save**

3. **Your site will be live at:**
   ```
   https://aaronshipp.github.io/What-s-Your-Ivy-Edge---Student-Assessment/
   ```
   (GitHub usually takes 1–2 minutes to publish after the first push.)

## Making Changes

Edit `index.html` directly, then push again:
```bash
git add index.html
git commit -m "Update assessment"
git push
```
GitHub Pages will automatically redeploy.
