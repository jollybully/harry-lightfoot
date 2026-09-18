# Harry Lightfoot portfolio

Single-page static site. No build step.

## Edit

All copy lives in `index.html`. Open it, change the text, save.

- Add a role: copy an `<article>` block in the work section.
- Add a photo: drop an image in `assets/` and uncomment the figure block near the footer.

## Deploy (Cloudflare)

Connect the GitHub repo in Workers & Pages. Leave the defaults:

- Build command: none
- Deploy command: `npx wrangler deploy`

`wrangler.toml` tells Wrangler this is a static site (no Worker script). Every push to `main` deploys automatically.

## Custom domain

In the Pages project settings, add your domain under Custom domains.
