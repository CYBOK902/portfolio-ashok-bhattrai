# 🚀 GitHub Setup Instructions

Your portfolio is ready to be pushed to GitHub! Follow these steps:

## Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com)
2. Log in to your GitHub account (or create one if needed)
3. Click the **"+"** icon → **"New repository"**
4. Name it: `portfolio-ashok` (or any name you prefer)
5. Description: "Ashok Bhattarai's Graphic Design Portfolio"
6. Choose **Public** (so people can see it)
7. **Don't** initialize with README (we already have one)
8. Click **"Create repository"**

## Step 2: Add GitHub Remote & Push

After creating the repo, GitHub will show you commands. Run these in your terminal:

```bash
# Navigate to portfolio folder
cd "/Users/sudiprajmandal/Downloads/Downloads/Ashok/untitled folder"

# Add the remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/portfolio-ashok.git

# Rename branch to main (recommended)
git branch -m master main

# Push to GitHub
git push -u origin main
```

**Example with actual username:**
```bash
git remote add origin https://github.com/ashokbhattarai/portfolio-ashok.git
git branch -m master main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (gear icon) → **Pages**
3. Under "Build and deployment":
   - Source: Select **"Deploy from a branch"**
   - Branch: Select **"main"** folder **"/ (root)"**
4. Click **Save**
5. Wait 2-3 minutes for GitHub to build and deploy

## ✅ Your Portfolio is LIVE!

Your portfolio will be available at:
```
https://YOUR_USERNAME.github.io/portfolio-ashok
```

**Example:**
```
https://ashokbhattarai.github.io/portfolio-ashok
```

Share this link with anyone to show your portfolio! 🎉

## 📝 How to Update Later

After making changes locally:

```bash
cd "/Users/sudiprajmandal/Downloads/Downloads/Ashok/untitled folder"

# Make your changes to files...

# Then commit and push:
git add .
git commit -m "Update portfolio content"
git push
```

GitHub Pages will automatically update within seconds!

## 🎯 Using a Custom Domain (Optional)

If you have a custom domain:

1. Go to repository **Settings** → **Pages**
2. Under "Custom domain", enter your domain
3. Configure DNS with your domain provider
4. Add the GitHub nameservers

## 💡 Pro Tips

- **Change repo name:** Go to Settings → Rename repository
- **Add custom README:** Create `README.md` (already done!)
- **Private portfolio:** Change repo to Private instead of Public
- **CI/CD:** GitHub Pages automatically builds when you push

## 🆘 Troubleshooting

**"403 - Permission denied"**
- Check your GitHub token/authentication
- May need to use SSH instead: `git remote set-url origin git@github.com:USERNAME/repo.git`

**Portfolio not showing up**
- Wait 2-3 minutes for GitHub Pages to build
- Check Settings → Pages to see build status
- Ensure `index.html` is in root folder

**Images not loading**
- Make sure images are in `/images/` folder
- Check that image paths in `index.html` are correct

---

**Need help?** Contact: 9861ashokbhattarai@gmail.com
