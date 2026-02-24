# 🚀 DEPLOY IN 5 MINUTES

## Step 1: Create GitHub Repo

1. Go to https://github.com
2. Click the "+" icon → "New repository"
3. Name: `golfalytics`
4. Click "Create repository"

## Step 2: Upload Your Files

Open Terminal (Mac) or Command Prompt (Windows) and run:

```bash
# Go to the golfalytics-final folder
cd path/to/golfalytics-final

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Launch Golfalytics site"

# Connect to GitHub (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/golfalytics.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**If it asks for password:** Use a Personal Access Token, not your GitHub password.

## Step 3: Deploy to Vercel

1. Go to https://vercel.com
2. Click "Sign Up" or "Log In" (use GitHub)
3. Click "Add New..." → "Project"
4. Find "golfalytics" in your repo list
5. Click "Import"
6. Click "Deploy" (don't change anything!)
7. Wait 1 minute ☕

## Step 4: Your Site is Live! 🎉

Vercel will give you a URL like:
`https://golfalytics.vercel.app`

Open it and see your site!

## Optional: Add Custom Domain

If you own `golfalytics.ca`:

1. In Vercel → Settings → Domains
2. Type: `golfalytics.ca`
3. Click "Add"
4. Follow the DNS instructions
5. Wait 10-30 minutes

---

## ✅ Checklist

- [ ] Created GitHub repository
- [ ] Pushed code to GitHub
- [ ] Connected to Vercel
- [ ] Site is live
- [ ] Tested on phone
- [ ] Tested contact form
- [ ] Added custom domain (optional)
- [ ] Shared on social media

---

## 🆘 Problems?

**"Permission denied" when pushing to GitHub?**
- Create a Personal Access Token on GitHub
- Use it as your password

**Can't find the folder in Terminal?**
- Use `cd` to navigate
- Or drag the folder into Terminal

**Vercel deployment failed?**
- Check the error log
- Make sure all files are in GitHub
- Try deploying again

---

## 📞 Need Help?

Check the full README.md for detailed instructions!

---

**That's it! Your Golfalytics site is now live! 🏌️⛳**
