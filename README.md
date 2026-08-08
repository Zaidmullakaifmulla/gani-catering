# Gani Catering — Website

A free, one-page website for Gani Catering (Belagavi). Built as plain HTML/CSS/JS —
no build tools, no paid hosting needed.

## What's inside
- `index.html` — the whole site
- `assets/gani-logo.png` — your logo, cropped from Instagram

## 1. Put it on GitHub Pages (free hosting)

1. Go to https://github.com/Zaidmullakaifmulla and click **New repository**.
2. Name it exactly: `gani-catering` → Create repository (keep it Public).
3. Click **Add file → Upload files**, drag in `index.html` and the `assets` folder
   (with `gani-logo.png` inside it), then **Commit changes**.
4. Go to the repo's **Settings → Pages**.
5. Under "Build and deployment", set **Source: Deploy from a branch**,
   **Branch: main / (root)** → **Save**.
6. Wait ~1–2 minutes. Your site will be live at:
   **https://zaidmullakaifmulla.github.io/gani-catering/**

That's it — completely free, no domain purchase needed. (If you want a nicer
free domain later, e.g. `ganicatering.great-site.net`, InfinityFree or Freenom
let you point a free domain at this GitHub Pages site — ask me if you want
that set up too.)

## 2. Turn on the enquiry form (free — Formspree)

Right now the "Send Enquiry" form on the site won't actually deliver anywhere
until you connect it — takes 2 minutes:

1. Go to https://formspree.io and sign up free (50 submissions/month free).
2. Create a new form, and copy the **form endpoint** it gives you —
   looks like `https://formspree.io/f/abcd1234`.
3. Open `index.html`, find this line (near the contact form):
   ```html
   <form id="enquiryForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
4. Replace `YOUR_FORM_ID` with the ID Formspree gave you, save, and re-upload
   `index.html` to GitHub (or edit it directly on GitHub — pencil icon on the file).
5. Formspree will send a confirmation email to `zaidmulla17000@gmail.com` the
   first time someone submits — click confirm once, then it's live.

Every enquiry submitted on the site will land straight in that inbox.

## 3. What already works with zero setup
- **Call button** → dials +91 93801 10090
- **WhatsApp button** (top bar + floating button) → opens WhatsApp with a
  pre-filled message
- **Google Maps link** → opens the shop address
- **Instagram link** → opens @gani_caterings

## 4. Editing content later
Everything (menu items, prices, address, phone) lives as plain text inside
`index.html`. Open it in any text editor (or GitHub's built-in editor —
click the pencil icon on the file in your repo) and edit directly; no
special software needed.

## Ideas for later (optional, still free)
- Add real event photos to a gallery section once you have them
- Add prices per plate/package next to menu items
- Add a WhatsApp Business catalog synced to the same menu
