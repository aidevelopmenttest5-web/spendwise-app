# 📱 SpendWise PWA - Quick Reference

## 🚀 Deploy in 3 Steps

1. **Create GitHub repo** → Upload 4 files (index.html, manifest.json, service-worker.js, create-icons.html)
2. **Enable GitHub Pages** → Settings → Pages → Source: main branch
3. **Generate & upload icons** → Open create-icons.html → Download → Upload to repo

**Your app will be live at:** `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## 📱 Install on Phone

### Android
1. Open in Chrome
2. Tap "Install" banner OR Menu → Add to Home screen

### iOS  
1. Open in Safari
2. Share button → Add to Home Screen

---

## 💾 Data Safety

### ✅ Your data is safe because:
- Stored in browser's persistent storage
- Separate from regular cache
- Not deleted when clearing browser cache (if app is installed)
- Only accessible on your device

### ⚠️ Data can be lost if:
- You uninstall the app completely
- You clear "Site data" specifically for this site
- You use incognito/private mode (doesn't persist)

### 🛡️ Best Practice:
**Export data monthly** (📥 Export XLSX button) and save to Drive/Phone

---

## 🔄 Update the App

1. Edit files on GitHub (or upload new version)
2. Users automatically get updates on next launch
3. Force update: Close app completely → Reopen

---

## 🎯 Key Features at a Glance

| Feature | Location |
|---------|----------|
| Add expense | Dashboard → "+ Add Expense" |
| Set budgets | Budget → Category cards |
| View reports | Dashboard → Charts |
| Track loans | Loans → "+ Add Loan" |
| Export data | Settings → Export buttons |
| Add members | Settings → Members section |

---

## 🆘 Quick Troubleshooting

| Problem | Solution |
|---------|----------|
| App won't install | Use Chrome (Android) or Safari (iOS) |
| Data disappeared | Check if app is still installed; restore from export |
| Offline not working | Load online once first; check storage space |
| Changes not showing | Close app completely → Clear cache → Reopen |
| Icons not showing | Upload icon-192.png and icon-512.png to repo |

---

## 📊 Storage Capacity

- **App size**: ~150 KB
- **Data per transaction**: ~0.5 KB
- **Can store**: 10,000+ transactions easily
- **Browser limit**: 5-50 MB (plenty for personal use)

---

## 🔗 Important URLs

- **GitHub**: https://github.com
- **Your repo**: `https://github.com/YOUR-USERNAME/REPO-NAME`
- **Live app**: `https://YOUR-USERNAME.github.io/REPO-NAME/`
- **Full guide**: See SETUP-GUIDE.md

---

## ⚡ Pro Tips

1. **Export regularly** - Better safe than sorry
2. **Set realistic budgets** - Adjust based on spending patterns  
3. **Use categories** - Makes analysis more useful
4. **Add notes** - Future you will thank you
5. **Review monthly** - Check Dashboard charts for insights

---

## 🎨 Customize

Want different colors? Edit CSS variables in index.html:
```css
--accent: #c9521a;    /* Change primary color */
--bg: #faf7f2;        /* Change background */
```

---

## 💰 Free Forever

- ✅ No app store fees
- ✅ No hosting costs (GitHub Pages is free)
- ✅ No subscription
- ✅ No ads
- ✅ No tracking

Your data, your device, your control.

---

**Need detailed help?** → Read SETUP-GUIDE.md

**Found a bug?** → Open issue on GitHub

**Want to share?** → Just send the app URL!
