# Yifan Zhang — yifanfilm.com

Personal portfolio site of Yifan Zhang 张轶凡 (film / AIGC / visual storytelling).

A single static page: `index.html` plus stills in `img/`. No build step.

- Edit works, loglines, awards and links in the `WORKS`, `LINKS` and `T` objects near the top of the `<script>` in `index.html`.
- Stills live in `img/` as `w<N>-<k>.jpg`; each work's `img` key and `hero` number pick its folder prefix and key still.
- Hosted on Cloudflare Workers (static assets, see `wrangler.jsonc`). Every push to `main` redeploys automatically.
- Files listed in `.assetsignore` are not published.
- DNS for yifanfilm.com is managed in Cloudflare; the domain itself is registered at Wix (renew before 2027-09-01).
