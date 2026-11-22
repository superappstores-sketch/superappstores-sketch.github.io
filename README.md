# TriNova Tech - TNT (Official Developer Website)

This repository contains the official developer website and AdMob `app-ads.txt` verification file for **TriNova Tech - TNT**.

## Included Files
- `index.html`: Responsive developer portfolio showcase with brand banner, apps showcase (*Selavu Book: Expense Tracker*), AdMob verification section, and contact info.
- `app-ads.txt`: Official AdMob publisher entry:
  ```
  google.com, pub-5664029289268267, DIRECT, f08c47fec0942fa0
  ```
- `robots.txt`: Search engine & crawler access rules allowing `Google-adstxt` and web crawlers.
- `.nojekyll`: Bypasses Jekyll build process so GitHub Pages serves raw files quickly.
- `privacy-policy.html`: Google Play-compliant privacy policy for apps.
- `terms.html`: Terms of service.

---

## Deployment to GitHub Pages

### Step 1: Create a Repository on GitHub
Create a new public repository named:
```
superappstores-sketch.github.io
```
*(Naming it `<username>.github.io` guarantees that it serves directly from the root domain `https://superappstores-sketch.github.io`, which is required by AdMob).*

### Step 2: Push this repository
From inside this directory:
```bash
git init
git add .
git commit -m "Initial commit: TriNova Tech site with app-ads.txt"
git branch -M main
git remote add origin https://github.com/superappstores-sketch/superappstores-sketch.github.io.git
git push -u origin main
```

### Step 3: Link in Google Play Console & AdMob
1. **Google Play Console**:
   - Go to **Developer Page** (or **Store Presence** &rarr; **Store Settings** &rarr; **Website**).
   - Set Website to: `https://superappstores-sketch.github.io`
   - Set App Privacy Policy to: `https://superappstores-sketch.github.io/privacy-policy.html`
2. **Google AdMob**:
   - Go to **Apps** &rarr; **app-ads.txt**.
   - Check verification status (AdMob crawls within 24 hours).
