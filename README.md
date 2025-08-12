# The Mindful Desi — Free Static Site (GitHub Pages)

This package is a *single‑page website* you can host **100% free** on GitHub Pages.

## What you need
- A GitHub account (free)
- This folder (upload as-is to a new GitHub repo)

## 1) Create the repo & upload
1. Go to https://github.com/new and create a repository named `mindfuldesi-site` (public is fine).
2. On the repo page, click **Add file → Upload files** and upload *all files/folders* from this package.
3. Commit the changes.

## 2) Turn on GitHub Pages
1. Go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** = `Deploy from a branch`.
3. Set **Branch** = `main` (or `master`), **/ (root)**. Click **Save**.
4. Wait ~1–2 minutes. Your site will appear at:
   `https://<your-username>.github.io/mindfuldesi-site/`

> Tip: If your repo uses the `master` branch, pick that instead of `main`.

## 3) Edit your details
Open `index.html` and update:
- **YouTube Embed**: Replace the video ID in the iframe URL (search for `dQw4w9WgXcQ`).
- **Newsletter form**: Replace `https://formspree.io/f/your-id` with your Formspree (free) or ConvertKit action URL.
- **Social links**: Replace YouTube/Instagram/TikTok profile links.
- **Favicon/Thumbnails**: Replace the PNGs inside `/assets` with your own (keep the same filenames or update the paths).

## 4) Optional: Custom domain
If you own a domain (e.g., `themindfuldesi.com`):
1. In the repo, click **Add file → Create new file**, name it `CNAME`, and put only your domain inside (no `https://`). Save.
2. In your domain DNS, add a **CNAME** record pointing your domain to `<your-username>.github.io`.
3. Back in **Settings → Pages**, set the **Custom domain** to your domain and enable **Enforce HTTPS**.

## 5) How to update later
- Edit files on GitHub (pencil icon) or commit via Git. GitHub Pages redeploys automatically.
- For images, upload to `/assets` and reference them with `assets/filename.png`.

---

### Where things live
- `index.html` → the whole site (simple, single file + CDN Tailwind)
- `assets/` → images (favicon + 3 placeholder thumbs)

### FAQ
- **Do I need to install anything?** No. This is plain HTML + Tailwind from a CDN, so GitHub Pages can serve it directly.
- **Can I rename the repo?** Yes. Your URL will change accordingly.
- **Can I use a different video per week?** Swap the embed ID and commit.
- **Will the form work without backend?** Yes, with Formspree free tier—create a new form and use its action URL.

Enjoy!
