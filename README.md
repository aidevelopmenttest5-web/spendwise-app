# 💰 SpendWise Tracker - PWA Edition

A beautiful, privacy-focused expense tracking Progressive Web App (PWA) that works offline and installs like a native app.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![PWA](https://img.shields.io/badge/PWA-Ready-purple)

## ✨ Features

### 📊 Expense Tracking
- Track daily expenses with categories
- Multiple family members support
- Custom categories and budgets
- Transaction history with search & filter

### 💡 Smart Budgeting
- Category-wise budget limits
- Real-time budget alerts
- Visual progress indicators
- Monthly and yearly views

### 📈 Analytics
- Spending trends over time
- Category-wise breakdown
- Monthly comparison charts
- Donut charts for distribution

### 🏦 Loan Management
- Track multiple loans
- Payment history
- Interest calculations
- Outstanding balance tracking

### 📱 PWA Benefits
- ✅ Install like a native app
- ✅ Works completely offline
- ✅ Fast loading with caching
- ✅ No app store needed
- ✅ Cross-platform (Android & iOS)
- ✅ Auto-updates

### 🔒 Privacy First
- All data stored locally on your device
- No server, no tracking, no analytics
- Export data anytime as Excel
- Complete data ownership

## 🚀 Quick Start

### For Users
1. Visit the app URL: `https://YOUR-USERNAME.github.io/spendwise-app/`
2. Click "Install" when prompted
3. Start tracking expenses!

### For Developers
See [SETUP-GUIDE.md](SETUP-GUIDE.md) for detailed deployment instructions.

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/spendwise-app.git

# Navigate to directory
cd spendwise-app

# Open in browser
open index.html
# OR deploy to GitHub Pages (recommended)
```

## 📦 Project Structure

```
spendwise-app/
│
├── index.html           # Main app file
├── manifest.json        # PWA manifest
├── service-worker.js    # Offline support & caching
├── create-icons.html    # Icon generator tool
├── icon-192.png        # App icon (192x192)
├── icon-512.png        # App icon (512x512)
├── SETUP-GUIDE.md      # Detailed setup instructions
└── README.md           # This file
```

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js 4.4.1
- **Excel Export**: SheetJS (xlsx) 0.18.5
- **Storage**: LocalStorage (browser persistent storage)
- **PWA**: Service Workers, Web App Manifest
- **Fonts**: DM Sans, DM Mono, Playfair Display

## 📱 Browser Support

| Browser | Version | Install Support |
|---------|---------|----------------|
| Chrome (Android) | 67+ | ✅ Full |
| Safari (iOS) | 11.3+ | ✅ Full |
| Edge | 79+ | ✅ Full |
| Firefox | 60+ | ⚠️ Limited |
| Samsung Internet | 8+ | ✅ Full |

## 💾 Storage

- **Type**: LocalStorage (PWA-optimized)
- **Capacity**: 5-10 MB typical (thousands of transactions)
- **Persistence**: Survives cache clearing when app is installed
- **Sync**: Local only (no cloud sync)

## 📤 Export Options

- **Excel (.xlsx)**: Full transaction history
- **Excel (.xlsx)**: Loan summary with payment history
- **Format**: Compatible with Excel, Google Sheets, LibreOffice

## 🎨 Customization

### Change Colors
Edit CSS variables in `index.html`:
```css
:root {
  --accent: #c9521a;      /* Primary color */
  --bg: #faf7f2;          /* Background */
  --text: #2c1f0e;        /* Text color */
}
```

### Add Categories
Modify the `DEFAULT_CATS` array in `index.html`:
```javascript
const DEFAULT_CATS = [
  'Food & Dining',
  'Transport',
  'Your Custom Category',
  // ... add more
];
```

## 🔄 Updates

App automatically checks for updates when opened while online. Users will see the latest version on next launch.

### Manual Update
1. Edit files in GitHub repository
2. Commit changes
3. GitHub Pages auto-deploys
4. Users get update on next app open

## 🐛 Known Issues

- iOS Safari: Install prompt only shows via Share → Add to Home Screen
- Firefox: Limited PWA support, better used in browser mode
- Old Android: Service Workers require Android 5.0+

## 🤝 Contributing

This is a personal project, but improvements are welcome!

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Chart.js for beautiful charts
- SheetJS for Excel export functionality
- Google Fonts for typography
- Icons designed with HTML Canvas

## 📧 Support

For issues or questions:
- Open an issue on GitHub
- Check [SETUP-GUIDE.md](SETUP-GUIDE.md) for troubleshooting

## 🎯 Roadmap

Future features under consideration:
- [ ] Dark mode toggle
- [ ] Multiple currency support
- [ ] Receipt photo attachments
- [ ] Cloud backup (optional)
- [ ] Recurring expense templates
- [ ] Budget forecasting
- [ ] Split transactions
- [ ] Multi-language support

---

**Made with ❤️ for better personal finance management**

⭐ Star this repo if you find it useful!
