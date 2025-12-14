# Deploying Your Website to GitHub Pages

## Step-by-Step Instructions

### 1. Create a GitHub Repository

1. Go to [GitHub.com](https://github.com)
2. Click the **"+"** icon (top right) → **"New repository"**
3. **IMPORTANT**: Name it exactly: `Geovanaafs.github.io`
   - This must match your GitHub username exactly
   - This creates a GitHub Pages user site (not a project site)
4. Make it **Public**
5. Don't add README, .gitignore, or license (we already have files)
6. Click **"Create repository"**

### 2. Upload Your Website Files

**Option A: Using GitHub Website (Easiest)**
1. Open your new repository
2. Click **"uploading an existing file"**
3. Drag and drop ALL files from your website folder:
   - index.html
   - styles.css
   - script.js
   - README.md
   - assets/ folder (with all images)
4. Scroll down and click **"Commit changes"**

**Option B: Using Git (Command Line)**
```bash
cd /Users/geovanafranca/website
git init
git add .
git commit -m "Initial commit: Personal portfolio website"
git branch -M main
git remote add origin https://github.com/Geovanaafs/Geovanaafs.github.io.git
git push -u origin main
```

### 3. Enable GitHub Pages (if not automatic)

1. Go to your repository settings
2. Click **"Pages"** in the left sidebar
3. Under "Source", select **"main"** branch
4. Click **"Save"**

### 4. Wait and Access Your Website

- GitHub Pages takes 1-5 minutes to build
- Your site will be live at: **https://Geovanaafs.github.io/**
- You'll get a success message when it's ready

## Important Notes

✅ **Your repository name MUST be**: `Geovanaafs.github.io`
- This makes your site appear at the root: `https://Geovanaafs.github.io/`
- Any other name would create: `https://Geovanaafs.github.io/repository-name/`

✅ **Make sure to upload the assets folder** with all images

✅ **The repository must be Public** for free GitHub Pages hosting

## Updating Your Website Later

After making changes locally:

**Option A: Upload via GitHub**
- Go to your repository
- Navigate to the file you want to update
- Click the pencil icon to edit
- Make changes and commit

**Option B: Using Git**
```bash
cd /Users/geovanafranca/website
git add .
git commit -m "Update website content"
git push
```

Changes will appear on your live site within 1-2 minutes!

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Git Tutorial](https://guides.github.com/introduction/git-handbook/)

---

**Your website will be live at: https://Geovanaafs.github.io/** 🎉
