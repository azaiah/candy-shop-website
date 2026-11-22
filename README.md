# The Candy Shop website

Static one-page site for The Candy Shop (Sugar Dollar, Sweet Money, Candy Cash, Muva Mula, Cha-Ching).
No build step: `index.html` plus the `assets/` folder.

## Deploy on Netlify
1. Push this folder to GitHub (`azaiah/candy-shop-website`).
2. In Netlify: Add new site > Import an existing project > pick the repo.
3. Build command: leave empty. Publish directory: `.` (already set in `netlify.toml`).

## Drop list signups
The email form is a Netlify Form named `drop-list`. Netlify detects it on the first deploy.
Signups show up under Site > Forms > drop-list. Turn on email notifications there if you want each signup emailed to you.

## Still to fill in
- Social links in the footer: search `[@HANDLE]` in `index.html`.
- Member flavors and blurbs live in the `M` list near the bottom of `index.html`.

## What's in assets/
- `sugar_dollar.webp`, `sweet_money.webp`, `candy_cash.webp`, `muva_mula.webp`, `cha_ching.webp`: member cutouts
- `logo_wrapper.webp` (main logo), `logo_cs.webp` (C$ icon), `logo_gumball.webp`, `favicon.png`
- `keep_a_business_name.mp4` + `kabn_poster.jpg`: the music video (web size, 576x1024)
