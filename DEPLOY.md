# AMI Concierge — Deployment Guide

## What's in this folder
- index.html       — The full app (all knowledge + chat UI)
- manifest.json    — Makes it installable as an app on phones
- service-worker.js — Enables offline support and fast loading
- DEPLOY.md        — This guide

---

## Step 1 — Create a GitHub account
1. Go to https://github.com
2. Click "Sign up" — just needs an email and password
3. Verify your email

---

## Step 2 — Create a new repository
1. Once logged in, click the green "New" button (top left)
2. Repository name: ami-concierge
3. Set to: Public
4. Leave everything else as default
5. Click "Create repository"

---

## Step 3 — Upload your files
1. In your new repository, click "Add file" → "Upload files"
2. Drag ALL FOUR files into the upload area:
   - index.html
   - manifest.json
   - service-worker.js
3. Scroll down, click "Commit changes"

---

## Step 4 — Turn on GitHub Pages
1. In your repository, click "Settings" (top menu)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and "/ (root)"
5. Click "Save"
6. Wait 2-3 minutes, then refresh the page
7. You'll see: "Your site is live at https://YOURUSERNAME.github.io/ami-concierge"

---

## Step 5 — Test it!
Visit your URL on your phone and desktop. On your phone:
- Chrome (Android): tap the three dots menu → "Add to Home Screen"
- Safari (iPhone): tap the Share button → "Add to Home Screen"
It will install like a real app with an icon on your home screen!

---

## Step 6 — Buy a custom domain (optional, ~$12/year)
1. Go to https://www.namecheap.com
2. Search for: amiconcierge.com or annamariaislandconcierge.com
3. Purchase your domain
4. In Namecheap, go to your domain's DNS settings
5. Add a CNAME record: www → YOURUSERNAME.github.io
6. In GitHub Pages settings, add your custom domain
7. Check "Enforce HTTPS"
8. Wait up to 24 hours for it to go live

---

## Need to update the app later?
1. Make changes to index.html (Claude can help with this!)
2. In your GitHub repository, click on index.html
3. Click the pencil (edit) icon
4. Paste in the new version
5. Click "Commit changes"
6. GitHub automatically republishes within ~2 minutes

---

## Icons (optional but recommended)
The app will work without custom icons, but to add your own:
- Create a 192x192 PNG and name it icon-192.png
- Create a 512x512 PNG and name it icon-512.png
- Upload them to your GitHub repository alongside the other files
- A simple palm tree or wave image works great
- Free tool to create icons: https://www.canva.com

---

Questions? Ask Claude for help at any step!
