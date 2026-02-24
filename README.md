# Golfalytics

**Turn Golf Course Audiences Into Revenue Intelligence**

Privacy-compliant mobile foot traffic data for golf course marketing, sponsorship valuation, and digital activation.

---

## 🚀 Quick Deploy to Vercel

### Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com) and create a new repository
2. Name it: `golfalytics`
3. Make it Public or Private
4. **Don't** initialize with README

### Step 2: Upload Files

```bash
# Navigate to this folder in terminal
cd golfalytics-final

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial Golfalytics site"

# Add your GitHub repository
git remote add origin https://github.com/YOUR-USERNAME/golfalytics.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username.

### Step 3: Deploy to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click "Add New..." → "Project"
3. Find your `golfalytics` repository
4. Click "Import"
5. Click "Deploy" (no configuration needed!)
6. Wait 30-60 seconds

Your site will be live at: `https://golfalytics.vercel.app`

### Step 4: Add Custom Domain (Optional)

1. In Vercel project → Settings → Domains
2. Add `golfalytics.ca` (or your domain)
3. Follow DNS instructions from Vercel
4. Wait 5-30 minutes for DNS propagation

---

## 📦 What's Included

### Core Files
- `index.html` - Main landing page
- `styles.css` - Complete styling
- `script.js` - Interactions and animations
- `privacy.html` - Privacy policy page

### Branding
- `logo-horizontal.svg` - Logo for header/emails
- `logo-square.svg` - Logo for social media (512×512px)
- `favicon.svg` - Browser tab icon
- `apple-touch-icon.svg` - iOS home screen icon

### Configuration
- `vercel.json` - Vercel deployment config
- `package.json` - Project metadata
- `.gitignore` - Git ignore rules

---

## ✨ Features

### Professional Design
- ✅ Golf green color palette (#2d5016, #4a7c1f, #7ab800)
- ✅ High-quality background images
- ✅ 2×2 capability cards with shadows
- ✅ Smooth animations and hover effects
- ✅ Mobile responsive design

### Strategic Content
- ✅ Premium auto brand case study
- ✅ Privacy-compliant messaging throughout
- ✅ Digital activation capabilities highlighted
- ✅ Clear value propositions for 3 audiences

### Optimized for Conversion
- ✅ Contact form with validation
- ✅ Multiple CTAs throughout
- ✅ Social proof (stats bar)
- ✅ Professional logo and branding

---

## 🎨 Customization

### Update Statistics

Edit `index.html` around line 52:

```html
<div class="stat-number">700+</div>
<div class="stat-label">Golf Courses</div>
```

### Change Colors

Edit `styles.css` at the top:

```css
:root {
    --primary-color: #2d5016;
    --secondary-color: #4a7c1f;
    --accent-color: #7ab800;
}
```

### Replace Images

Current images are from Unsplash (free to use). To replace:

1. Find the image URL in `styles.css`
2. Replace with your own image URL
3. Or use local files in an `images/` folder

---

## 📧 Connect Contact Form

The form currently shows an alert. To make it functional:

### Option 1: Formspree (Easiest)

1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form
3. Get your endpoint
4. In `index.html`, add to the form tag:
   ```html
   <form action="https://formspree.io/f/YOUR_ID" method="POST" id="contactForm">
   ```

### Option 2: Netlify Forms

1. Add `data-netlify="true"` to your form tag
2. Deploy to Netlify instead of Vercel
3. Forms work automatically

---

## 📊 Add Analytics

### Google Analytics

Add to `<head>` in `index.html`:

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

### Vercel Analytics

1. In Vercel project → Analytics
2. Click "Enable"
3. Automatically added (no code needed)

---

## 🖼️ Logo Usage

### Horizontal Logo (`logo-horizontal.svg`)
- Use for: Website header, email signatures, documents
- Size: Scales to any size
- Background: Transparent

### Square Logo (`logo-square.svg`)
- Use for: LinkedIn, Twitter, Facebook, Instagram profiles
- Size: 512×512px (scales to any size)
- Background: Golf green

### Favicon (`favicon.svg`)
- Use for: Browser tabs
- Size: 32×32px
- Already implemented in the site

---

## 📱 Mobile Optimization

The site is fully responsive:
- ✅ Mobile-first design
- ✅ Touch-friendly buttons
- ✅ Readable text sizes
- ✅ Optimized images
- ✅ Smooth scrolling

Test on:
- iPhone (all sizes)
- Android devices
- Tablets
- Desktop (all resolutions)

---

## 🔧 Troubleshooting

### Site not deploying?
- Verify all files are committed to GitHub
- Check Vercel deployment logs for errors
- Make sure repository is accessible to Vercel

### Images not loading?
- Check that image URLs are correct in CSS
- Verify internet connection
- Try hard refresh (Ctrl+Shift+R)

### Form not working?
- Connect to Formspree or another backend
- Check browser console for errors
- Test with a simple alert first

---

## 🌟 Next Steps

After launching:

1. ✅ Test on multiple devices
2. ✅ Connect form backend
3. ✅ Add custom domain
4. ✅ Set up analytics
5. ✅ Share on social media
6. ✅ Use square logo for social profiles
7. ✅ Add to email signature

---

## 📞 Support

Built by Measured Reporting

- Website: [mearep.com](https://mearep.com)
- Email: info@mearep.com

---

## 📄 License

© 2026 Golfalytics / Measured Reporting. All rights reserved.

---

**You're ready to deploy!** 🏌️⛳📊

Follow the Quick Deploy steps above and your site will be live in minutes!
