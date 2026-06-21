# Reel Dread

Reel Dread is a static horror movie picker web app. It runs from a single `index.html` file and includes a curated offline catalog, genre/sub-genre flow, five random picks, filters, a watchlist, and original in-app poster styling.

## Files in this GitHub package

```text
reeldread/
  index.html
  package.json
  README.md
  .gitignore
  assets/
    reeldread-logo.png
```

## Run locally without installing anything

Open `index.html` directly in your browser.

## Run locally with npm

This project also includes a small Vite setup so you can run a local development server.

```bash
npm install
npm run dev
```

Then open the local URL shown in the terminal.

## Build for production

```bash
npm run build
```

The production site will be created in:

```text
dist/
```

## Deploy on Cloudflare Pages

Recommended settings:

```text
Framework preset: Vite
Build command: npm run build
Build output directory: dist
Root directory: /
```

## Deploy on GitHub Pages without a build step

Because the app is static, you can also publish directly from the repository root.

1. Push this folder to a GitHub repository.
2. In GitHub, open the repository.
3. Go to Settings > Pages.
4. Choose Deploy from a branch.
5. Choose the `main` branch and `/ (root)`.
6. Save.

## Safety note

Do not commit API keys, passwords, `.env` files, proprietary company data, customer data, or confidential work data to GitHub.
