# 🚀 Quick Start Checklist - Deploy in 5 Minutes

Follow these steps to get your Food Desert Mapper live on GitHub Pages:

## ☑️ Pre-Deployment Checklist

- [ ] Have a GitHub account (create free at github.com)
- [ ] Downloaded all project files
- [ ] Read through README.md

## 📋 Step-by-Step Deployment

### Step 1: Create Repository (2 minutes)
1. Go to https://github.com/new
2. Repository name: `food-desert-mapper` (or your choice)
3. Description: "Interactive tool for mapping food deserts"
4. Make it **Public** ✓
5. Do NOT initialize with README (we have our own)
6. Click **Create repository**

### Step 2: Upload Files (2 minutes)

**Method A: Web Upload (Easiest - No Git Required)**
1. On your new empty repository, click **uploading an existing file**
2. Drag and drop ALL these files:
   ```
   ✓ food-desert-mapper.html
   ✓ README.md
   ✓ LICENSE
   ✓ API_INTEGRATION_GUIDE.md
   ✓ GITHUB_DEPLOYMENT_GUIDE.md
   ```
3. Scroll down, click **Commit changes**
4. For the `.github` folder:
   - Click **Add file** → **Create new file**
   - Name it: `.github/workflows/deploy.yml`
   - Copy contents from `deploy.yml` file
   - Click **Commit new file**

**Method B: Git Command Line**
```bash
# In your project folder
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR-USERNAME/food-desert-mapper.git
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages (1 minute)
1. In your repository, click **Settings** tab
2. Click **Pages** in left sidebar
3. Under **Source**:
   - Branch: Select `main`
   - Folder: Select `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes (GitHub will build your site)

### Step 4: Test Your Site! 🎉

Your site is now live at:
```
https://YOUR-USERNAME.github.io/food-desert-mapper/food-desert-mapper.html
```

**Replace YOUR-USERNAME with your actual GitHub username**

## ✅ Verification Checklist

Test these features on your live site:

- [ ] Map loads and displays Chicago
- [ ] Can see colored census tracts
- [ ] Store markers appear (🏪)
- [ ] Click a tract shows info panel
- [ ] Sliders change parameters
- [ ] Statistics display correctly
- [ ] Works on mobile device
- [ ] No console errors (F12 to check)

## 🎨 Customization (Optional)

Before deploying, you can customize:

### In README.md:
- [ ] Replace "YOUR-USERNAME" with your GitHub username
- [ ] Replace "YOUR-REPO-NAME" with your repository name
- [ ] Add your name and contact info at bottom
- [ ] Add screenshots (optional)

### In food-desert-mapper.html:
- [ ] Change default city (line ~570: `value="Chicago, IL"`)
- [ ] Add more demo cities to DEMO_DATA object
- [ ] Customize color scheme (CSS variables at top)
- [ ] Change map tiles (Leaflet options)

## 🔧 Troubleshooting

### "404 - Page not found"
**Solution:** 
- Check that GitHub Pages is enabled
- Wait 2-3 minutes after enabling
- Make sure URL includes the filename: `.../food-desert-mapper.html`

### "Map doesn't load"
**Solution:**
- Check browser console (F12)
- Ensure Leaflet CDN is accessible
- Try different browser

### "Files aren't showing in repository"
**Solution:**
- Make sure you committed all files
- Check that file names are exact (case-sensitive)
- Try refreshing the GitHub page

### "GitHub Pages section not appearing"
**Solution:**
- Repository must be Public (not Private)
- You must have at least one file committed
- Try Settings → Pages → Source → Save again

## 🚀 Next Steps After Deployment

1. **Share your link!**
   - Post on social media
   - Share with colleagues
   - Add to your portfolio

2. **Get feedback**
   - Ask friends to test it
   - Note any bugs or improvements
   - Consider adding GitHub Issues

3. **Enable live APIs** (optional)
   - Get free Census API key
   - Follow API_INTEGRATION_GUIDE.md
   - Consider Netlify deployment

4. **Enhance the project**
   - Add more demo cities
   - Improve mobile experience
   - Add data export feature

## 📚 Resources

- **GitHub Pages Guide:** https://pages.github.com/
- **Full Deployment Guide:** See GITHUB_DEPLOYMENT_GUIDE.md
- **API Integration:** See API_INTEGRATION_GUIDE.md
- **Git Basics:** https://guides.github.com/introduction/git-handbook/

## 🎓 Learning Opportunities

Once deployed, you can use this project to learn:
- [ ] GIS and spatial analysis
- [ ] Public health data visualization
- [ ] API integration
- [ ] Responsive web design
- [ ] Open data analysis

## 🤝 Get Help

- **GitHub Discussions:** Create a discussion in your repo
- **Stack Overflow:** Tag with `github-pages`
- **GitHub Docs:** https://docs.github.com/en/pages

---

## ⏱️ Estimated Time

- **Total time:** 5-10 minutes
- **Method A (Web):** 5 minutes
- **Method B (Git CLI):** 8 minutes
- **Testing:** 2 minutes

## 🎉 Success!

Once you see your map at `https://YOUR-USERNAME.github.io/food-desert-mapper/food-desert-mapper.html`, you're done!

**Don't forget to:**
- ⭐ Star your own repository
- 📝 Update the README with your info
- 📱 Test on different devices
- 🎨 Customize to make it your own

---

**Questions?** Open an issue in your repository or refer to GITHUB_DEPLOYMENT_GUIDE.md

**Ready to deploy?** Start with Step 1 above! 🚀
