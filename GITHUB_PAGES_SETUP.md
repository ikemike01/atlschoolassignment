# 🚀 Complete GitHub Pages Setup Guide

This guide will help you deploy your personal webpage to GitHub Pages for public access.

## 📋 What You Need
- A GitHub account (free at github.com)
- Your webpage files (already ready in this folder!)

## 🎯 Step-by-Step Setup

### **STEP 1: Create GitHub Repository**

1. **Go to GitHub**
   - Visit: https://github.com
   - Sign in to your account (or create one if needed)

2. **Create New Repository**
   - Click the green **"New"** button (or the **"+"** icon → "New repository")
   - Fill in the details:
     ```
     Repository name: personal-webpage
     Description: My AltSchool personal profile with fragment navigation
     Visibility: ✅ Public (required for free GitHub Pages)
     Initialize: ❌ Do NOT check any initialization options
     ```
   - Click **"Create repository"**

### **STEP 2: Connect Your Local Code to GitHub**

After creating the repository, GitHub will show you a page with commands. 

**Copy your repository URL** (it will look like):
```
https://github.com/YOUR_USERNAME/personal-webpage.git
```

Then run these commands in your terminal (replace YOUR_USERNAME with your actual GitHub username):

```bash
# Add GitHub as remote repository
git remote add origin https://github.com/YOUR_USERNAME/personal-webpage.git

# Set main branch
git branch -M main

# Push your code to GitHub
git push -u origin main
```

### **STEP 3: Enable GitHub Pages**

1. **Navigate to Repository Settings**
   - Go to your repository on GitHub
   - Click the **"Settings"** tab (far right in the repository menu)

2. **Find Pages Section**
   - Scroll down the left sidebar
   - Click **"Pages"** (under "Code and automation")

3. **Configure Pages Settings**
   - **Source**: Select **"Deploy from a branch"**
   - **Branch**: Select **"main"** 
   - **Folder**: Select **"/ (root)"**
   - Click **"Save"**

4. **Wait for Deployment**
   - GitHub will show a message: "Your site is ready to be published"
   - It takes 1-2 minutes to build and deploy
   - Refresh the page to see the live URL

### **STEP 4: Access Your Live Website**

Once deployed, your website will be available at:

**Main URL:**
```
https://YOUR_USERNAME.github.io/personal-webpage/
```

**Direct Section Links (Fragment Navigation):**
```
https://YOUR_USERNAME.github.io/personal-webpage/#basic-info
https://YOUR_USERNAME.github.io/personal-webpage/#biography
https://YOUR_USERNAME.github.io/personal-webpage/#why-joined
https://YOUR_USERNAME.github.io/personal-webpage/#goals
```

## 🔧 Troubleshooting

### Common Issues:

**1. "Repository not found" error**
- Make sure repository is **Public**
- Check the repository URL is correct

**2. "Pages not building"**
- Ensure `index.html` is in the root folder
- Check that the branch name is correct (main)

**3. "404 Page Not Found"**
- Wait 5-10 minutes after enabling Pages
- Clear browser cache
- Check the exact URL format

**4. "Changes not showing"**
- After pushing new changes, wait 1-2 minutes
- GitHub Pages rebuilds automatically
- Force refresh browser (Ctrl+F5 or Cmd+Shift+R)

## 🎉 Success Checklist

- ✅ GitHub repository created and public
- ✅ Code pushed to GitHub
- ✅ GitHub Pages enabled
- ✅ Website accessible via public URL
- ✅ Fragment navigation working
- ✅ All sections (Basic Info, Biography, Why Joined, Goals) accessible

## 📱 Sharing Your Website

Once live, you can share your website with:
- **AltSchool instructors and classmates**
- **Potential employers**
- **Professional network**
- **Social media profiles**

## 🔄 Future Updates

To update your website:
1. Make changes to your HTML file
2. Save and commit: `git add . && git commit -m "Update content"`
3. Push to GitHub: `git push`
4. Changes will automatically appear on your live site in 1-2 minutes!

## 📞 Need Help?

If you encounter issues:
1. Check GitHub's Pages documentation
2. Verify all steps above
3. Ensure your repository is public
4. Try the troubleshooting steps

---

**Your files are ready to deploy! 🚀**

**Next action:** Go to github.com and create your repository!
