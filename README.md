# iadriantan.com - Personal Blog Website

A clean, modern personal blog for Adrian Tan focused on Agentic AI, Fintech, and the Future of Banking.

**Live Site Ready** - Just upload to GitHub Pages, Netlify, or Vercel!

---

## 🚀 Quick Start

### 1. Preview Locally
1. Download this repository
2. Open `index.html` in your web browser
3. That's your website!

### 2. Deploy to GitHub Pages (Free Hosting)
1. Create a new GitHub repository
2. Upload all these files
3. Go to Settings → Pages → Enable GitHub Pages
4. Your site is live at `username.github.io/repo-name`

**Full deployment guide:** See `docs/hosting-guide.md`

---

## 📁 File Structure

```
iadriantan-website/
│
├── index.html              ← Homepage (shows latest posts)
├── archive.html            ← All posts organized by year
│
├── posts/
│   └── post-template.html  ← Copy this for each new blog post
│
├── images/                 ← Put your photos here
│   └── (your images)
│
└── docs/
    ├── how-to-update.md    ← Guide to adding posts
    ├── managing-posts.md   ← How to handle many posts
    └── hosting-guide.md    ← Deploy instructions
```

---

## ✍️ Adding a New Blog Post (5 Minutes)

### Step 1: Create Your Post
```bash
# Copy the template
posts/post-template.html → posts/my-new-post.html
```

### Step 2: Edit Your Post
Open `posts/my-new-post.html` and update:
- Title (in `<title>` and `<h1>`)
- Date
- Your content
- Tags

### Step 3: Add to Homepage
Open `index.html`, find the posts section, and add:
```html
<a href="posts/my-new-post.html" class="post-card">
    <div class="post-date">January 30, 2026</div>
    <h2>Your Post Title</h2>
    <p class="post-excerpt">Brief description...</p>
    <div class="post-tags">
        <span class="tag">Your Tag</span>
    </div>
</a>
```

### Step 4: Add to Archive
Open `archive.html` and add to the appropriate year section.

**Detailed guide:** See `docs/how-to-update.md`

---

## 🎨 Customization

### Change Colors
Edit the CSS variables in `index.html`:
```css
:root {
    --primary: #00ff88;    /* Change to your color */
    --accent: #ff006e;     /* Change to your color */
}
```

### Add Your Photo
1. Put your photo in `images/` folder
2. In `index.html`, find the about section
3. Replace `AT` with: `<img src="images/your-photo.jpg" alt="Adrian Tan">`

### Update Your Bio
Edit the text in the "About" section of `index.html`

### Update Social Links
Change the URLs in the header and footer of `index.html`

---

## 🌐 Hosting Options (All Free)

### Option 1: GitHub Pages
- Free hosting
- Custom domain support
- Auto-deploy from Git
- **Recommended for simplicity**

### Option 2: Netlify
- Free hosting
- Drag-and-drop deployment
- Form handling
- **Recommended for features**

### Option 3: Vercel
- Free hosting
- Great for developers
- Fast deployment

**Full instructions:** See `docs/hosting-guide.md`

---

## 📝 Content Management

### Homepage
- Shows your **10-15 latest posts**
- Keeps the page fast and focused
- Link to archive for older posts

### Archive
- Shows **ALL posts** organized by year
- No limit on number of posts
- Automatically organized

### When to Update
Every new post:
1. Add to homepage (if it's in latest 10-15)
2. Add to archive (always)
3. Remove oldest from homepage if needed

**Full strategy:** See `docs/managing-posts.md`

---

## 💰 Cost

- **Domain**: ~$12/year (Google Domains, Namecheap)
- **Hosting**: $0 (GitHub Pages/Netlify/Vercel)
- **Total**: **$1/month**

Compare to:
- Ghost: $108-300/year
- Beehiiv: $588/year
- Substack: Limited design control

---

## 📊 What's Included

### Design Features
✅ Modern dark theme with neon accents  
✅ Fully responsive (mobile-friendly)  
✅ Fast loading (no frameworks)  
✅ Clean, professional layout  
✅ Smooth hover animations  

### SEO Optimized
✅ Proper meta tags  
✅ Semantic HTML  
✅ Open Graph tags for social sharing  
✅ Clean URLs  
✅ Mobile-first design  

### Easy to Update
✅ No build process  
✅ No dependencies  
✅ Just HTML/CSS/JS  
✅ Edit in any text editor  
✅ Clear documentation  

---

## 🎯 Getting Started Checklist

### Before You Deploy
- [ ] Open `index.html` and preview in browser
- [ ] Update the about section with your bio
- [ ] Change social media links
- [ ] Add your photo (optional)
- [ ] Customize colors (optional)
- [ ] Write your first blog post

### Deploy
- [ ] Choose hosting platform
- [ ] Upload files
- [ ] Configure custom domain
- [ ] Verify site is live

### After Launch
- [ ] Submit to Google Search Console
- [ ] Share on social media
- [ ] Update LinkedIn/Twitter with link
- [ ] Start weekly publishing schedule

---

## 📚 Documentation

### Essential Guides
- **docs/how-to-update.md** - Step-by-step guide to adding posts
- **docs/managing-posts.md** - Handle unlimited posts without clutter
- **docs/hosting-guide.md** - Deploy your site in 30 minutes

### Advanced (Optional)
- **docs/content-automation.md** - Use AI to help write posts
- **docs/seo-strategy.md** - Rank higher in search

---

## ❓ Need Help?

### Common Questions

**Q: How do I preview my site locally?**  
A: Just double-click `index.html` - it opens in your browser!

**Q: How do I add images to posts?**  
A: Upload to `images/` folder, then use: `<img src="../images/photo.jpg">`

**Q: Can I change the design?**  
A: Yes! Edit the CSS in the `<style>` section of any HTML file.

**Q: What if I want to add 50+ posts?**  
A: Use the archive system! Homepage shows latest 10-15, archive shows all.

### Resources
- GitHub Pages: https://pages.github.com
- Netlify: https://netlify.com
- Markdown guide: https://www.markdownguide.org

---

## 🎉 You're Ready!

This is a complete, production-ready website. Everything you need to:
- ✅ Launch a professional blog
- ✅ Publish weekly without hassle
- ✅ Build your personal brand
- ✅ Save hundreds per year on hosting

**Next Step:** Open `index.html` in your browser to see your site!

---

## 📄 License

Feel free to use this template for your personal blog. The design is yours to customize!

---

## 🤝 Questions or Issues?

Check the documentation in the `docs/` folder. Everything is explained step-by-step.

**Let's build iadriantan.com! 🚀**
