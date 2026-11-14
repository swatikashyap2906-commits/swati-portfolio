# Swati Kashyap — Portfolio

A single-page interactive portfolio. No build step, no dependencies.

- `index.html`: all markup, styles and interactions (scenes 1–7 run top to bottom).
- `assets/`: images, videos and the Sanskriti photobook pages, referenced from `index.html`.

To swap a project in the work grid, edit the `projects` list in `index.html` (search for `EDIT HERE`) and drop the new cover into `assets/`.

## Deploy on Vercel (free)

1. Go to https://vercel.com/new and sign in with GitHub.
2. Import this repository (`swati-portfolio`).
3. Settings on the import screen:
   - **Framework Preset:** Other
   - **Build Command:** leave empty
   - **Output Directory:** leave empty (root)
4. Click **Deploy**. Every push to `main` redeploys automatically.

## Other free hosts

- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / `/ (root)`.
- **Netlify:** Drag the folder onto https://app.netlify.com/drop, or import the repo with no build command.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
