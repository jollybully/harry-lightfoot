# Harry Lightfoot portfolio

Single-page static site. No build step.

## Edit

Copy lives in `index.html`. Open it, change the text, save.

- Add a credit: copy an `<article>` in the work section. Set `data-youtube` and the YouTube URLs / thumbnail id to the video id (the `v=` value).
- Thumbnails load as stills. The embed is created on click, so the page does not load ten YouTube players at once.

## Deploy (Cloudflare)

Connect the GitHub repo in Workers & Pages. Leave the defaults:

- Build command: none
- Deploy command: `npx wrangler deploy`

`wrangler.toml` tells Wrangler this is a static site (no Worker script). Every push to `main` deploys automatically.

## Custom domain

In the Pages project settings, add your domain under Custom domains.
