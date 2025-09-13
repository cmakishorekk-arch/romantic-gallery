[README.md](https://github.com/user-attachments/files/22309908/README.md)
# Romantic Gallery (GitHub Pages)

A single-page, mobile-friendly photo gallery. Click any image to open a full-screen lightbox. Use left/right arrow keys to navigate.

## How to publish on GitHub Pages

1. Create a new repository on GitHub (e.g., `romantic-gallery`).
2. Upload **all files** from this folder to the repo (`index.html` and the `images/` folder). You can drag & drop the whole folder in GitHub's web UI or use Git.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.  
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

> Tip: If you add new photos later, just upload them to the `images/` folder and commit. They will appear automatically.

## Local preview (optional)
Open `index.html` in your browser. For best results, serve locally with a simple HTTP server:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.
