# 🔧 FlowPro Plumbing Website

A modern, mobile-first, high-converting website for a local plumbing business.  
Built with pure HTML, CSS, and vanilla JavaScript — zero dependencies, instant load.

---

## 📁 Project Structure

```
flowpro-plumbing/
├── index.html        ← Main website (all 8 pages)
├── vercel.json       ← Vercel deployment config
├── .gitignore        ← Git ignore file
└── README.md         ← This file
```

---

## ✅ Before You Deploy — Customize Your Details

Open `index.html` and **find & replace** these placeholders:

| Placeholder         | Replace With                        |
|---------------------|-------------------------------------|
| `[PHONE_NUMBER]`    | e.g. `(555) 123-4567`               |
| `[WHATSAPP_NUMBER]` | e.g. `15551234567` (no spaces/dashes)|
| `[EMAIL]`           | e.g. `info@flowproplumbing.com`     |
| `[ADDRESS]`         | e.g. `123 Main Street`              |
| `[CITY]`            | e.g. `Austin`                       |
| `[STATE]`           | e.g. `TX`                           |
| `[ZIP]`             | e.g. `78701`                        |
| `[WORKING_HOURS]`   | e.g. `Mon–Fri 7am–7pm`             |

> **Tip:** Use your code editor's Find & Replace All (Ctrl+H / Cmd+H) to replace all at once.

Also replace the Google Maps embed placeholder with your real embed code from [Google Maps Embed API](https://developers.google.com/maps/documentation/embed).

---

## 🚀 Deploy to Vercel (Step-by-Step)

### Method 1: GitHub + Vercel (Recommended)

#### Step 1 — Push to GitHub

1. Go to [github.com](https://github.com) → Click **"New repository"**
2. Name it `flowpro-plumbing` → Set to **Public** → Click **Create repository**
3. Open your terminal and run:

```bash
# Navigate to this folder
cd flowpro-plumbing

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: FlowPro Plumbing website"

# Connect to your GitHub repo (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/flowpro-plumbing.git

# Push
git branch -M main
git push -u origin main
```

#### Step 2 — Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) → Sign up / Log in with GitHub
2. Click **"Add New Project"**
3. Find and select your `flowpro-plumbing` repository → Click **Import**
4. Leave all settings as default (Vercel auto-detects static sites)
5. Click **"Deploy"**
6. ✅ Your site is live! You'll get a URL like `flowpro-plumbing.vercel.app`

---

### Method 2: Vercel CLI (Fastest)

```bash
# Install Vercel CLI
npm install -g vercel

# Navigate to project folder
cd flowpro-plumbing

# Deploy
vercel

# Follow the prompts — done!
```

---

### Method 3: Drag & Drop (No terminal needed)

1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag the entire `flowpro-plumbing` folder onto the page
3. Click **Deploy** — that's it!

---

## 🌐 Custom Domain (Optional)

1. In Vercel dashboard → Your project → **Settings → Domains**
2. Add your domain e.g. `flowproplumbing.com`
3. Update your domain's DNS records as instructed by Vercel
4. SSL certificate is automatic and free

---

## 🔄 Update Your Website

After making changes to `index.html`, just push to GitHub:

```bash
git add .
git commit -m "Update contact info"
git push
```

Vercel will **auto-redeploy** within seconds. 🎉

---

## 📞 Pages Included

| Page     | Description                                    |
|----------|------------------------------------------------|
| Home     | Hero, services overview, reviews, map, CTAs    |
| About    | Story, team, certifications, commitments       |
| Services | Detailed service pages with booking links      |
| Booking  | Online booking form with time slots            |
| Pricing  | 3-tier pricing cards (Basic/Standard/Emergency)|
| Gallery  | 9-item project grid with lightbox              |
| Blog     | 3 full SEO blog posts with FAQ accordions      |
| Contact  | Contact form, info, hours, WhatsApp, map       |

---

## ⚡ Performance & SEO

- ✅ Local Business Schema (JSON-LD)
- ✅ Review Schema markup
- ✅ FAQ Schema on blog posts
- ✅ Open Graph meta tags
- ✅ Semantic HTML5 (H1, H2, proper headings)
- ✅ Mobile-first responsive layout
- ✅ Click-to-call & WhatsApp integration
- ✅ Zero external JS dependencies
- ✅ Vercel CDN = global fast loading

---

## 🛠 Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, Grid, Flexbox, animations
- **Vanilla JS** — SPA routing, form handling, gallery
- **Google Fonts** — Syne + DM Sans
- **Vercel** — Hosting & CDN

---

*Built for local plumbing businesses. Customize the brand name, colors, and content to match your business.*
