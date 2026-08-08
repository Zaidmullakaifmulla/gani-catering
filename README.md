# Gani Catering — Website

A free, one-page website for Gani Catering (Belagavi). Plain HTML/CSS/JS —
no build tools, no paid hosting.

## What's inside (5 files, all go in the SAME folder — no subfolders)
- `index.html` — the whole site
- `gani-logo.png` — your logo
- `robots.txt` — lets search engines crawl the site
- `sitemap.xml` — helps Google index the site
- `README.md` — this file

## How to deploy — start completely fresh

To avoid mix-ups from earlier edits, the cleanest approach is to delete the
old repo and start over with these 5 files.

### 1. Delete the old repo (optional but recommended)
1. Go to `github.com/Zaidmullakaifmulla/gani-catering`
2. **Settings** → scroll to the bottom → **Delete this repository** → follow
   the confirmation steps

### 2. Create a fresh repo
1. Go to `github.com/Zaidmullakaifmulla` → **New repository**
2. Name it exactly: `gani-catering` → keep **Public** → **Create repository**

### 3. Upload all 5 files at once
1. On the empty repo page, click **uploading an existing file**
2. Drag in all 5 files together: `index.html`, `gani-logo.png`, `robots.txt`,
   `sitemap.xml`, `README.md`
3. Scroll down → **Commit changes**

### 4. Turn on GitHub Pages
1. Repo → **Settings → Pages**
2. Under "Build and deployment": **Source: Deploy from a branch**
3. **Branch: main**, folder: **/ (root)** → **Save**
4. Wait 1–2 minutes

Your site is now live at:
**https://zaidmullakaifmulla.github.io/gani-catering/**

## 5. Turn on the enquiry form (free — Formspree)

The "Send Enquiry" form needs a one-time connection:

1. Go to https://formspree.io → sign up free (50 submissions/month free)
2. Create a new form → copy the endpoint, looks like `https://formspree.io/f/abcd1234`
3. On GitHub, open `index.html` → click the pencil (edit) icon
4. Find this line near the contact form:
   ```html
   <form id="enquiryForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
5. Replace `YOUR_FORM_ID` with your real ID → **Commit changes**
6. Formspree emails `zaidmulla17000@gmail.com` to confirm the first time
   someone submits — click confirm once, then it's fully live

## What already works with zero setup
- **Call to Order** button → dials +91 93801 10090
- **WhatsApp buttons** (top bar + floating green icon) → opens WhatsApp with
  a pre-filled message
- **Google Maps link** → opens the shop address
- **Instagram link** → opens @gani_caterings

## Get found on Google (optional)
1. Go to https://search.google.com/search-console
2. Add property → paste your live URL
3. Verify → then go to **Sitemaps** → submit `sitemap.xml`
4. Indexing usually takes 1–3 weeks after that

## Editing content later
Everything (menu items, prices, address, phone) is plain text inside
`index.html`. Open it with the pencil (edit) icon on GitHub and edit
directly — no special software needed.
