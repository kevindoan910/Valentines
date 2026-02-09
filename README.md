# Valentine's Day Website ❤️

A beautiful Valentine's Day website with an animated red heart.

## How to Publish to GitHub Pages

### Step 1: Install Git (if not already installed)
1. Download Git from: https://git-scm.com/download/win
2. Install it with default settings

### Step 2: Create a GitHub Account
1. Go to: https://github.com
2. Sign up for a free account (if you don't have one)

### Step 3: Create a New Repository on GitHub
1. Log into GitHub
2. Click the "+" icon in the top right → "New repository"
3. Name it: `valentines-website` (or any name you like)
4. Make sure it's set to **Public**
5. **DO NOT** check "Initialize with README"
6. Click "Create repository"

### Step 4: Upload Your Files
After creating the repository, GitHub will show you instructions. Use these commands in PowerShell (run from the `valentines-website` folder):

```powershell
cd c:\Users\td062\Desktop\valentines-website
git init
git add .
git commit -m "Initial commit - Valentine's Day website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/valentines-website.git
git push -u origin main
```

**Replace `YOUR_USERNAME` with your actual GitHub username!**

### Step 5: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"
7. Wait a few minutes, then your site will be live at:
   `https://YOUR_USERNAME.github.io/valentines-website/`

## Alternative: Use GitHub Desktop (Easier!)

If you prefer a visual interface:
1. Download GitHub Desktop: https://desktop.github.com/
2. Install and sign in with your GitHub account
3. Click "File" → "Add Local Repository"
4. Browse to `c:\Users\td062\Desktop\valentines-website`
5. Click "Publish repository" button
6. Then follow Step 5 above to enable GitHub Pages

---

Your website will be live and shareable! 🎉