# Racing game (web)

Browser game: responsive layout for **PC and iPad**, local multiplayer layouts, bots and levels — as we build them.

## Run offline

Open `index.html` in a browser, or use a local server:

```bash
npx --yes serve .
```

Visit the URL shown (often `http://localhost:3000`).

## Put it on GitHub and run online (GitHub Pages)

1. **Create a new repository** on GitHub (empty, no README if you will push this folder).
2. In this project folder, run (replace `YOUR_USER` and `YOUR_REPO`):

   ```bash
   git init
   git add .
   git commit -m "Initial commit: web racing game"
   git branch -M main
   git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch **main** and folder **`/` (root)**, then Save.
6. After a minute or two, the site URL will be:

   `https://YOUR_USER.github.io/YOUR_REPO/`

If you add a build step later (e.g. Vite outputs to `dist/`), change Pages to publish from the `dist` folder via Actions or the `gh-pages` branch — we can document that when the build exists.

## Notes

- **Repository must be public** for free GitHub Pages on a personal account (or use GitHub Team with private Pages).
- For a **custom domain**, add a `CNAME` file and configure DNS in the same Pages settings.
