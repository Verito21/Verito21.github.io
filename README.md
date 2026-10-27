# Srijan Singh – Portfolio

A single-page portfolio site. One file (`index.html`), no build step, no dependencies. Fonts load from Google Fonts and fall back to system fonts if blocked.

## Deploy on GitHub Pages

1. Create a public repo named `verito21.github.io` (your GitHub username + `.github.io`).
2. Put `index.html` in the repo root and push to `main`.
3. In the repo: Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
4. Wait a minute or two. The site is live at https://verito21.github.io.

## Other hosts

- Netlify Drop: drag this folder onto https://app.netlify.com/drop
- Cloudflare Pages or Vercel: connect the repo, no build command, output directory `/`.

## Editing

Open `index.html` and change the text directly. Colors and fonts are the variables at the top of the `<style>` block. The page follows the visitor's light or dark setting.
