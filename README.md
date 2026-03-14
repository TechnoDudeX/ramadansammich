# 🥪 Ramadan Sammich

**Feeding the GTA, One Sammich at a Time**

A community-driven initiative that assembles and distributes meals to local shelters across the Greater Toronto Area every Ramadan. Since 2012.

🌐 **Live site:** [ramadansammich.ca](https://ramadansammich.ca)

---

## 🚀 Deploy to Netlify via GitHub

### Step 1: Create a GitHub Repo

1. Go to [github.com/new](https://github.com/new)
2. Name it `ramadan-sammich` (or whatever you like)
3. Set it to **Public** or **Private**
4. Click **Create repository**

### Step 2: Push This Code

```bash
cd ramadan-sammich
git init
git add .
git commit -m "Initial commit - Ramadan Sammich website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ramadan-sammich.git
git push -u origin main
```

### Step 3: Connect to Netlify

1. Go to [app.netlify.com](https://app.netlify.com)
2. Click **"Add new site"** → **"Import an existing project"**
3. Choose **GitHub** and authorize Netlify
4. Select your `ramadan-sammich` repo
5. Build settings (should auto-detect, but verify):
   - **Build command:** _(leave blank — it's static HTML)_
   - **Publish directory:** `.`
6. Click **Deploy site**

### Step 4: Custom Domain (ramadansammich.ca)

1. In Netlify, go to **Site settings** → **Domain management**
2. Click **Add custom domain** → enter `ramadansammich.ca`
3. Update your DNS records at your domain registrar:
   - **Option A (recommended):** Point `ramadansammich.ca` as a CNAME to your Netlify subdomain (e.g., `your-site-name.netlify.app`)
   - **Option B:** Use Netlify DNS — transfer nameservers to Netlify
4. Netlify will auto-provision an SSL certificate (HTTPS)

---

## 📁 Project Structure

```
ramadan-sammich/
├── index.html      ← The entire website (single file)
├── netlify.toml    ← Netlify configuration
└── README.md       ← You're reading this
```

## ✏️ Making Changes

Since this is a single `index.html` file, just edit it directly and push:

```bash
git add .
git commit -m "Update content"
git push
```

Netlify will auto-deploy within seconds.

---

## 🌙 Built with love for the community.
