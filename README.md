# L'Artisan - Neapolitan Pizza Artistry

A premium, modern, and responsive landing page for an artisan Neapolitan pizza restaurant. 

## Features
- **Responsive Design**: Mobile, tablet, and desktop friendly.
- **Modern UI**: Dark luxury aesthetic with elegant typography and gold accents.
- **Smooth Animations**: Intersection Observer based scroll-reveal animations.
- **Zero Dependencies**: Built with raw HTML5, CSS3, and Vanilla JavaScript. No external libraries or frameworks (except Google Fonts).

## Deployment Instructions (No Errors Guaranteed)

This project is a static website. There is no build step required (`npm run build`, etc.). This avoids common deployment issues related to Node versions or missing dependencies.

### GitHub Pages
1. Push this repository to GitHub.
2. Go to your repository **Settings** > **Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**.
4. Select `main` (or `master`) branch and the `/ (root)` folder.
5. Click Save. Your site will be live in a few minutes.

### Vercel
1. Log into Vercel and click **Add New Project**.
2. Import your GitHub repository.
3. Framework Preset: **Other**
4. Build Command: `(leave blank)`
5. Output Directory: `(leave blank)`
6. Click **Deploy**.

### Netlify
1. Log into Netlify and click **Add new site** > **Import an existing project**.
2. Select GitHub and choose your repository.
3. Base directory: `(leave blank)`
4. Build command: `(leave blank)`
5. Publish directory: `/` or `(leave blank)`
6. Click **Deploy site**.

## Common Deployment Gotchas Avoided:
- **Case Sensitivity**: All image filenames and paths are lowercase (e.g., `assets/images/hero-bg.png`). This prevents 404 errors on Linux servers.
- **Absolute Paths**: All asset paths use relative linking, avoiding missing asset errors when hosted on subpaths (like GitHub Pages).
- **Missing Dependencies**: Pure HTML/CSS/JS means no `node_modules` or `package.json` errors.

## Structure
- `index.html`: Main HTML file.
- `styles.css`: Complete styling system.
- `assets/images/`: Optimized image assets.
