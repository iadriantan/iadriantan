# 🚀 Deploy Your Website in 30 Minutes

## Option 1: GitHub Pages (Recommended)

### Step 1: Create GitHub Account
1. Go to https://github.com
2. Sign up (free)
3. Verify your email

### Step 2: Create Repository
1. Click "+" in top right → "New repository"
2. Name it: `iadriantan.com` (or any name)
3. Keep it Public
4. Click "Create repository"

### Step 3: Upload Files
1. Click "uploading an existing file"
2. Drag and drop ALL files from this folder
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to repository Settings → Pages
2. Source: Deploy from branch `main`
3. Folder: `/ (root)`
4. Click Save

**Your site is now live!** It will be at:
```
https://YOUR-USERNAME.github.io/iadriantan.com
```

### Step 5: Add Custom Domain (Optional)
1. In Settings → Pages
2. Custom domain: Enter `iadriantan.com`
3. Click Save

**Then configure DNS at your domain registrar:**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A  
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153

Type: CNAME
Name: www
Value: YOUR-USERNAME.github.io
```

Wait 10-30 minutes for DNS to update.

---

## Option 2: Netlify (Easiest for Non-Developers)

### Step 1: Sign Up
1. Go to https://netlify.com
2. Sign up with email (free)

### Step 2: Drag and Drop
1. Look for "Sites" section
2. Drag your entire website folder onto the page
3. Wait 30 seconds

**Done!** Your site is live at a random URL like `random-name.netlify.app`

### Step 3: Custom Domain
1. Click "Domain settings"
2. Click "Add custom domain"
3. Enter: `iadriantan.com`
4. Follow DNS instructions

---

## Option 3: Vercel (For Developers)

### Step 1: Install Vercel CLI
```bash
npm install -g vercel
```

### Step 2: Deploy
```bash
cd iadriantan-website
vercel
```

Follow the prompts. Your site will be live in 60 seconds.

### Step 3: Add Custom Domain
```bash
vercel domains add iadriantan.com
```

---

## After Deployment

### 1. Verify Everything Works
- [ ] Homepage loads correctly
- [ ] Archive page works
- [ ] Sample posts open
- [ ] Links work (home ↔ archive)
- [ ] Looks good on mobile (resize browser)

### 2. Set Up Google Search Console
1. Go to https://search.google.com/search-console
2. Add property: Your domain
3. Verify ownership
4. Submit sitemap (if you create one)

### 3. Update and Test
1. Edit `index.html` with your real bio
2. Add your first real blog post
3. Push changes to see them go live

---

## Updating Your Live Site

### GitHub Pages
```bash
# Edit your files
git add .
git commit -m "Update website"
git push
# Wait 1-2 minutes, changes are live
```

### Netlify
1. Drag and drop updated files
2. Or connect to GitHub for auto-deploy

### Vercel
```bash
vercel --prod
```

---

## Troubleshooting

**Site not loading?**
- Wait 5-10 minutes for deployment
- Check repository is Public
- Verify GitHub Pages is enabled

**Custom domain not working?**
- DNS can take 4-24 hours
- Double-check DNS records
- Use https://dnschecker.org to verify

**Changes not showing?**
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Clear browser cache
- Try incognito/private window

---

## Cost Breakdown

- **Domain**: $12/year (Namecheap, Google Domains, Cloudflare)
- **Hosting**: $0 (GitHub/Netlify/Vercel free tier)
- **SSL Certificate**: $0 (included free)
- **Total**: **$1/month** 🎉

---

## Next Steps

1. ✅ Site is live!
2. 📝 Add your first real blog post
3. 🎨 Customize colors and content
4. 📱 Share on social media
5. 📊 Start publishing weekly

**You're live! Time to build your brand 🚀**
