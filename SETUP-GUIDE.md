# SpendWise PWA - Setup Guide

## 📱 What You're Getting

A **Progressive Web App (PWA)** version of SpendWise Tracker that:
- ✅ Works offline after first load
- ✅ Installs like a native app on phone
- ✅ Data persists even if you clear browser cache
- ✅ Fast loading with caching
- ✅ Works on both Android & iOS
- ✅ **100% FREE** - No app store fees

---

## 🚀 Quick Setup (5 minutes)

### Step 1: Create GitHub Account (if you don't have one)
1. Go to https://github.com
2. Click "Sign up" 
3. Create free account

### Step 2: Upload Files to GitHub Pages

#### Option A: Using GitHub Web Interface (Easiest)
1. Go to https://github.com/new
2. Repository name: `spendwise-app` (or any name you like)
3. Select **Public** (required for free GitHub Pages)
4. Click "Create repository"
5. Click "uploading an existing file"
6. Upload these 4 files:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `create-icons.html`
7. Click "Commit changes"

#### Option B: Using GitHub Desktop (Recommended for regular updates)
1. Download GitHub Desktop: https://desktop.github.com/
2. Install and sign in
3. Click "Create New Repository"
4. Name: `spendwise-app`, choose local path
5. Copy all 4 files into that folder
6. Click "Commit to main"
7. Click "Publish repository"

### Step 3: Enable GitHub Pages
1. Go to your repository on github.com
2. Click "Settings" tab
3. Scroll to "Pages" in left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 2-3 minutes
7. Your app will be live at: `https://YOUR-USERNAME.github.io/spendwise-app/`

### Step 4: Generate App Icons
1. Open `create-icons.html` in your browser (double-click the file)
2. Download both icon-192.png and icon-512.png
3. Upload them to your GitHub repository (same folder as other files)

---

## 📱 Installing on Your Phone

### Android (Chrome)
1. Open Chrome browser on your phone
2. Go to: `https://YOUR-USERNAME.github.io/spendwise-app/`
3. Wait for the "Install SpendWise app" banner to appear
4. Tap "Install" button
5. Or tap the menu (⋮) → "Add to Home screen"
6. Done! App icon appears on home screen

### iOS (Safari)
1. Open Safari on iPhone
2. Go to: `https://YOUR-USERNAME.github.io/spendwise-app/`
3. Tap the Share button (square with arrow)
4. Scroll down and tap "Add to Home Screen"
5. Tap "Add"
6. Done! App icon appears on home screen

---

## 💾 How Data Storage Works

### PWA Storage (localStorage)
- Data stored in browser's persistent storage
- **Will NOT be deleted** when you clear cache (as long as app is installed)
- Separate from regular browser data
- Only accessible to your device

### Data Backup (Recommended)
Even though PWA storage is reliable, it's good practice to:
1. Export data monthly (use "📥 Export XLSX" button)
2. Save backup to Google Drive / Phone storage
3. This protects against accidental uninstall

---

## 🔄 Updating the App

When you want to add features or fix bugs:

### Method 1: Edit on GitHub
1. Go to your repository
2. Click on the file (e.g., `index.html`)
3. Click the pencil icon (Edit)
4. Make changes
5. Click "Commit changes"
6. App updates automatically! (users may need to refresh once)

### Method 2: Upload New Version
1. Download updated files
2. Go to your repository
3. Click "Add file" → "Upload files"
4. Replace old files
5. Commit changes

### Forcing Update on Phone
If changes don't appear:
1. Open the app
2. Close it completely (swipe away)
3. Reopen - new version loads

---

## 🌐 Sharing with Others

### Share the URL
Just send them: `https://YOUR-USERNAME.github.io/spendwise-app/`

They can:
- Use it in browser
- Install on their phone (same steps)
- Each person has their own separate data

### Custom Domain (Optional)
Want `spendwise.yourdomain.com` instead?
1. Buy domain from Namecheap/GoDaddy (~₹500/year)
2. In GitHub repository Settings → Pages
3. Add custom domain
4. Update DNS records (GitHub provides instructions)

---

## 🛠️ Troubleshooting

### "App won't install"
- Make sure you're using Chrome (Android) or Safari (iOS)
- Try opening in browser, not in-app browser (like Instagram/Facebook browser)
- Check that GitHub Pages is enabled and site is live

### "Data disappeared"
- Did you uninstall the app? Data is tied to installation
- Try checking exports/backups
- For future: export data regularly

### "Offline not working"
- Must load the app online at least once
- Service worker needs to cache files (happens automatically on first load)
- Check if you have storage space on device

### "Changes not showing"
- Close app completely
- Clear browser cache for that specific site
- Reopen app

---

## 📊 Storage Limits

### Browser Storage Limits
- **Chrome**: ~6% of free disk space (typically 1-2 GB)
- **Safari**: ~1 GB
- **SpendWise data**: Extremely small (~1-5 MB even with years of data)

You can track **thousands of expenses** without any issues.

---

## 🔐 Privacy & Security

### Your Data
- ✅ Stored only on your device
- ✅ Not sent to any server
- ✅ Not accessible to others
- ✅ No tracking or analytics
- ✅ Works completely offline

### GitHub Pages
- Only hosts the app code (HTML/JS/CSS)
- Does NOT store your expense data
- Your data never leaves your device

---

## 💡 Next Steps

### After Setup
1. ✅ Install on your phone
2. ✅ Add first expense to test
3. ✅ Set up budgets for categories
4. ✅ Add family members (if sharing)
5. ✅ Export data as backup

### Optional Enhancements
- Customize colors in CSS
- Add more categories
- Modify budget alerts
- Add charts/reports

### Want to Sell It?
See the monetization guide for:
- Adding payment integration
- Creating landing page
- Marketing strategies

---

## 📞 Need Help?

Common issues and solutions:
- GitHub Pages not working → Check if repository is Public
- Icons not showing → Make sure they're in same folder as index.html
- App won't update → Clear browser cache, reinstall app

---

## ✅ Checklist

- [ ] GitHub account created
- [ ] Repository created and files uploaded
- [ ] GitHub Pages enabled
- [ ] Icons generated and uploaded
- [ ] App URL tested in browser
- [ ] Installed on phone
- [ ] First expense added successfully
- [ ] Data persists after closing/reopening
- [ ] Export function tested

---

**Congratulations! Your SpendWise PWA is now live! 🎉**

Your app URL: `https://YOUR-USERNAME.github.io/spendwise-app/`

Share it with friends, family, or keep it personal. Enjoy tracking your expenses! 💰
