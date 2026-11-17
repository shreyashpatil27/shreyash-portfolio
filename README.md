# Shreyash Patil — Creative Portfolio

A placeholder-first React + Vite portfolio built from the supplied creative brief.

## Run locally

1. Install Node.js (18+ recommended).
2. In this folder run `npm install`.
3. Run `npm run dev` to preview.
4. Run `npm run build` to create the deployable `dist` folder.

## Deploy to Cloudflare Pages

1. Create a Cloudflare Pages project and choose **Direct Upload**.
2. Build this project locally with `npm install` then `npm run build`.
3. Upload the generated `dist` folder (not the source folder and not this ZIP).
4. Choose a project name such as `shreyashpatil`. Cloudflare will provide `shreyashpatil.pages.dev` if available.

For Git-based deployment, push this folder to GitHub and connect the repository in Cloudflare Pages. Use build command `npm run build` and build output directory `dist`.

## Replace placeholders

- Project data and categories: `src/main.jsx` (`projects` array).
- Replace each `<Placeholder />` block with an `<img>`, `<video>`, or PDF viewer when assets are ready.
- Update email, LinkedIn, resume and location links in `src/main.jsx`.
- Fonts and SEO title/description: `index.html`.

All project thumbnails are intentionally placeholders. No stock artwork, fake clients, testimonials, metrics or fictional portrait are included.
