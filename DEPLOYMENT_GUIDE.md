# 🚀 CoreShift Landing Page — Vercel + Free .tk Domain

**Setup Time:** 15 minutes  
**Cost:** $0  
**Result:** `https://coreshift.tk`

---

## 📦 What You Need

All files are ready in your outputs folder:
- `coreshift-landing.html` — Your landing page
- `server.js` — Express server
- `package.json` — Dependencies
- `vercel.json` — Vercel config

---

## ⚡ Quick Deploy (5 steps)

### Step 1: Create GitHub Repo

1. Go to **github.com** → **New Repository**
2. Name it: `coreshift-landing`
3. Clone locally:
```bash
git clone https://github.com/YOUR-USERNAME/coreshift-landing.git
cd coreshift-landing
```

### Step 2: Add Files

Create folder structure:
```
coreshift-landing/
├── public/
│   └── index.html          (copy from coreshift-landing.html)
├── server.js               (copy from outputs)
├── package.json            (copy from outputs)
├── vercel.json             (copy from outputs)
└── .gitignore              (add below)
```

Create `.gitignore`:
```
node_modules/
.env
.DS_Store
```

### Step 3: Push to GitHub

```bash
git add .
git commit -m "Initial CoreShift landing page setup"
git branch -M main
git push -u origin main
```

### Step 4: Deploy to Vercel

1. Go to **vercel.com** → Sign in with GitHub
2. Click **"Add New Project"**
3. Select your `coreshift-landing` repo
4. Click **"Import"**
5. Leave all settings default
6. Click **"Deploy"** ✨
7. Wait 2-3 minutes
8. You'll get a URL like: `coreshift-landing.vercel.app`

### Step 5: Get Free .tk Domain

1. Go to **freenom.com**
2. Search: `coreshift`
3. Select `.tk` → **Continue**
4. Complete free registration (12 months)
5. Go to **My Domains**

### Step 6: Connect Domain to Vercel

**In Vercel:**
1. Go to your project → **Settings** → **Domains**
2. Add custom domain: `coreshift.tk`
3. Copy the nameservers Vercel shows:
   - `ns1.vercel-dns.com`
   - `ns2.vercel-dns.com`

**In Freenom:**
1. Click your domain → **Management Tools** → **Nameservers**
2. Select **"Use custom nameservers"**
3. Paste Vercel's nameservers
4. Save

⏳ **Wait 24-48 hours** for DNS to propagate

---

## ✅ You're Done!

Your landing page is now live at:
- **https://coreshift.tk** 🎉
- SSL certificate: Automatic ✅
- Updates: Just push to GitHub, Vercel auto-deploys

---

## 📝 Commands Cheat Sheet

**Update landing page:**
```bash
# Edit public/index.html
git add .
git commit -m "Update design"
git push
# Vercel redeploys automatically!
```

**Check deployment status:**
- Go to vercel.com → your project → Deployments

---

## 🎯 Next: Phase 5.2 - JavaScript SDK

Once landing page is live, we'll build:
```bash
npm install coreshift-js
```

With methods like:
```javascript
const cs = new CoreShift('api-key');
await cs.ai.chat([...]);
await cs.db.insert('users', {...});
```

---

## 💬 Troubleshooting

**Domain not working?**
- Wait 24-48 hours for DNS propagation
- Check Vercel nameservers in Freenom

**Landing page not showing?**
- Verify `public/index.html` exists
- Check Vercel deployment logs
- Redeploy manually in Vercel dashboard

**Want to edit landing page?**
- Edit `public/index.html`
- Commit and push to GitHub
- Vercel redeploys automatically

---

## 📊 Free Tier Limits

- **Vercel:** 100GB bandwidth/month, unlimited deployments
- **Freenom:** Free .tk domain (needs renewal every 12 months, but free)
- **GitHub:** Unlimited public repos

Perfect for launching CoreShift! 🚀
