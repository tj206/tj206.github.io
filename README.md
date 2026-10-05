# tjjoseph-site

Personal portfolio for TJ Joseph. Plain HTML, no build step, hosted on GitHub Pages.

## Put it online (about 20 minutes)

1. **Create the repo.** On GitHub, make a new public repository. Name it `<your-username>.github.io` if you want the site at that address, or any name (e.g. `portfolio`) if you'll use a custom domain.
2. **Upload these files** to the repo root: `index.html`, `.nojekyll`, `README.md` and the `clips/` folder. Either drag them into GitHub's "Add file → Upload files" page, or from a terminal:
   ```
   git init
   git add .
   git commit -m "Launch portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. **Turn on Pages.** Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save. The site is live in a minute or two.
4. **Custom domain (optional, recommended).** Buy the domain (Porkbun, Namecheap, Cloudflare — roughly $10–15/yr for a .com). In Settings → Pages → Custom domain, enter it and save; GitHub creates a `CNAME` file. At your registrar, add the DNS records GitHub's Pages docs list for an apex domain (four A records) plus a `www` CNAME pointing to `<your-username>.github.io`. Once DNS resolves, tick "Enforce HTTPS".

## Updating

Edit `index.html`, commit, push. Pages redeploys automatically.

## Files

- Videos: don't commit video files (GitHub rejects files over 100 MB and Pages is slow for media). Upload to YouTube as unlisted or to Vimeo and link out, or embed.
- Images: keep each under ~1 MB; export from Canva as JPG or WebP at 1600px on the long side.
