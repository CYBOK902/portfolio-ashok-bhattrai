# 🚀 Push to GitHub - Step by Step (Your Account: CYBOK902)

Everything is ready locally! Follow these exact steps to push to your GitHub account.

## ✅ Step 1: Create the Repository on GitHub

1. **Go to GitHub:** https://github.com/new
2. **Repository Name:** `portfolio-ashok`
3. **Description:** Ashok Bhattarai's Graphic Design Portfolio
4. **Visibility:** Select **PUBLIC** (so people can see it)
5. **Don't initialize** with README (we already have one)
6. Click **"Create repository"**

## ✅ Step 2: Get Your Personal Access Token

Since GitHub doesn't allow password authentication, you need a token:

1. Go to: https://github.com/settings/tokens
2. Click **"Generate new token"** → **"Generate new token (classic)"**
3. Give it a name: `portfolio-push`
4. Select these scopes:
   - ✅ `repo` (Full control of private repositories)
   - ✅ `workflow` (Update GitHub Action workflows)
5. Click **"Generate token"**
6. **COPY** the token (you'll only see it once!)
7. Paste it somewhere safe temporarily

## ✅ Step 3: Push to GitHub Using Your Token

Once you have the token and repository created, run these commands:

```bash
cd "/Users/sudiprajmandal/Downloads/Downloads/Ashok/untitled folder"

git remote set-url origin https://CYBOK902:YOUR_TOKEN_HERE@github.com/CYBOK902/portfolio-ashok.git

git push -u origin main
```

**Replace `YOUR_TOKEN_HERE` with your actual token from Step 2**

Example:
```bash
git remote set-url origin https://CYBOK902:ghp_aBcDeFgHiJkLmNoPqRsTuVwXyZ1234567@github.com/CYBOK902/portfolio-ashok.git

git push -u origin main
```

Then you'll see:
```
Counting objects: 12, done.
Writing objects: 100% (12/12), ...
remote: Resolving deltas: 100% (5/5), done.
...
* [new branch] main -> main
Branch 'main' set up to track remote branch 'main' from origin.
```

## ✅ Step 4: Enable GitHub Pages (Make It Live)

After successful push:

1. Go to: https://github.com/CYBOK902/portfolio-ashok
2. Click **Settings** (gear icon)
3. Scroll to **Pages** (left sidebar)
4. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** / **/(root)**
5. Click **Save**
6. Wait 2-3 minutes for GitHub to build

## 🎉 Your Portfolio is LIVE!

Once GitHub Pages is enabled, it will be available at:

```
https://CYBOK902.github.io/portfolio-ashok
```

📍 **Share this link with your friend!**

## 🔒 Security Note

- **Don't share your token** with anyone
- You can delete it later in Settings → Developer settings → Personal access tokens
- Or create new tokens for different projects

## 🐛 Troubleshooting

**"fatal: could not read from remote repository"**
- Make sure repository exists on GitHub
- Check your token is correct
- Verify username `CYBOK902` is correct

**"remote: Repository not found"**
- Go to github.com and create the repository first
- Make sure visibility is PUBLIC

**"Authentication failed"**
- Your token may be expired
- Generate a new one from GitHub settings

## 📋 Summary

| Step | Action | Status |
|------|--------|--------|
| 1 | Create repo on GitHub | ⏳ Do this |
| 2 | Get Personal Access Token | ⏳ Do this |
| 3 | Run git push command | ⏳ Do this |
| 4 | Enable GitHub Pages | ⏳ Do this |
| 5 | Portfolio is LIVE! | 🎉 Done! |

---

**Questions?** Check GitHub Docs: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens

**Your local files are 100% ready - just need to create the empty repo on GitHub!** ✅
