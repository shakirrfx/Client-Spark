# ClientSpark — Freelancer Client Discovery Tool
> Deploy for free on GitHub Pages in under 5 minutes.

## 🚀 Deploy to GitHub Pages (Free Hosting)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **+ New repository**
3. Name it `clientspark` (or any name you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the file
1. In your new repo, click **Add file → Upload files**
2. Drag and drop `index.html` into the upload area
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: `main`, folder: `/ (root)`
4. Click **Save**

### Step 4 — Your site is live! 🎉
Within 1–2 minutes, your tool will be live at:
```
https://YOUR-USERNAME.github.io/clientspark/
```

---

## 📁 File Structure
```
clientspark/
└── index.html      ← The entire app (single file, no dependencies)
```

## ✨ Features Included
- **Landing page** with hero section, feature cards, and pricing tiers
- **2-day free trial** with live countdown timer in the app
- **Client discovery feed** with 8 mock clients across categories
- **Category tabs**: Design, Video, eCommerce, Dev, Copywriting, SEO, Social, Photography
- **Contact details** (email, phone, LinkedIn) — hidden behind paywall after trial
- **Simulated map panel** with client location markers
- **Paywall modal** when trial expires or locked leads are clicked
- **Fully responsive** — works on mobile, tablet, and desktop
- **No external dependencies** — just one HTML file

## 🎨 Customization
All CSS variables are at the top of `index.html` under `:root { }`:
```css
--accent: #D97B4A;    /* Change brand color */
--teal: #3D7A73;      /* Secondary color */
--cream: #FAF8F4;     /* Background */
```

## 🔗 Integrating Real APIs (Production)
To make this production-ready, connect these APIs:
- **LinkedIn API** — LinkedIn Developer Portal (OAuth 2.0)
- **Indeed Publisher API** — indeed.com/publisher
- **Google Maps JavaScript API** — console.cloud.google.com
- **Stripe** — stripe.com for subscription billing
- **SendGrid** — for trial expiry email notifications

## 📧 Support
Questions? Open a GitHub Issue in your repository.
