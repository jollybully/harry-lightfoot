# Harry Lightfoot portfolio

Single-page static site. No build step.

## Edit

All copy lives in `index.html`. Open it, change the text, save.

- Add a role: copy an `<article>` block in the work section.
- Add a photo: drop an image in `assets/` and uncomment the figure block near the footer.

## Deploy (Cloudflare Pages)

1. Push this folder to a GitHub repo.
2. In Cloudflare Pages: connect the repo, build command **none**, output directory `/`.
3. Every push to `main` deploys automatically.

Or drag the folder into the Cloudflare Pages dashboard for a one-off upload.

## Custom domain

In the Pages project settings, add your domain under Custom domains.
