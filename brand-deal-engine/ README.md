# BRAND DEAL ENGINE — Deployment Guide
## Built by NANDYVISUALS

---

## FILE STRUCTURE

```
brand-deal-engine/
├── index.html      ← Sales landing page (public)
├── access.html     ← Password gate (public)
├── engine.html     ← The actual app (protected)
├── vercel.json     ← Routing config
└── README.md       ← This file
```

---

## DEPLOY TO VERCEL (Recommended — 5 minutes)

### Step 1: Go to your GitHub repo
Open: https://github.com/nandelevisuals-commits/visionaries

### Step 2: Upload the folder
- Click "Add file" → "Upload files"
- Drag the entire `brand-deal-engine` folder into the upload area
- Commit with message: "Add Brand Deal Engine"

### Step 3: Vercel auto-deploys
Your existing Vercel project is connected to this repo.
Once pushed, the engine will be live at:

- **Sales page:** https://visionaries-rouge.vercel.app/brand-deal-engine/
- **Access gate:** https://visionaries-rouge.vercel.app/brand-deal-engine/access.html
- **App (protected):** https://visionaries-rouge.vercel.app/brand-deal-engine/engine.html

---

## GUMROAD SETUP

1. Go to: https://app.gumroad.com
2. Create a new product: "Brand Deal Engine"
3. Price: $47
4. Product type: Digital — no file needed (access via URL)
5. In the "Thank you / confirmation" message, paste:

```
Your access code is: BRANDDEAL2025

Access the Brand Deal Engine here:
https://visionaries-rouge.vercel.app/brand-deal-engine/access.html
```

6. Update the buy button URLs in index.html if Gumroad gives you a different link:
   - Search for: wandiko.gumroad.com/l/branddealengine
   - Replace with your actual Gumroad product URL

---

## ADDING NEW ACCESS CODES

Open `access.html` and find this section:
```javascript
const CODES = [
  'BRANDDEAL2025',
  'NANDYBLOSSOM',
  'DEALENGINE37',
  'CREATOR2025',
];
```
Add any new codes inside the array. You can give each buyer a unique code
or use one universal code for all buyers. Push to GitHub and Vercel updates automatically.

---

## YOUR URLS TO SHARE

| Purpose | URL |
|---------|-----|
| Sales page (share this) | visionaries-rouge.vercel.app/brand-deal-engine/ |
| Direct app access | visionaries-rouge.vercel.app/brand-deal-engine/access.html |
| Link in bio | visionaries-rouge.vercel.app/brand-deal-engine/ |

---

## PRICING SUGGESTION

- Launch price: $47 (what's set now)
- After 20 sales: raise to $47
- Bundle with VISIONAIRE Studio ($67) for $97 complete bundle

---

Questions? This was built by Claude for NANDYVISUALS.
