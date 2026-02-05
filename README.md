# FitRival Website & Support Pages

This folder contains all the files for your GitHub Pages website at `https://zaenj.github.io/fitrival-support/`

## Files Overview

- **index.html** - Main landing page with app info and download links
- **support.html** - Support page with comprehensive FAQ
- **terms.html** - Terms of Service
- **privacy.html** - Privacy Policy
- **challenge.html** - Challenge redirect handler (deep linking)
- **styles.css** - Shared styles for all pages

## How to Deploy to GitHub Pages

### 1. Upload Files to Your Repo

1. Go to https://github.com/zaenj/fitrival-support
2. Click "Add file" → "Upload files"
3. Upload ALL files from this folder:
   - index.html
   - support.html
   - terms.html
   - privacy.html
   - challenge.html
   - styles.css

### 2. Enable GitHub Pages

1. Go to repository Settings
2. Scroll to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Select branch: **main** (or master)
5. Select folder: **/ (root)**
6. Click Save

### 3. Wait for Deployment

Your site will be live at: `https://zaenj.github.io/fitrival-support/`

It may take 1-2 minutes to deploy.

## Challenge Links

When users share challenges, they'll generate links like:
```
https://zaenj.github.io/fitrival-support/challenge.html?c=abc123xyz
```

This link:
- ✅ **Has app**: Opens app → Shows challenge
- ✅ **No app**: Shows download buttons → After install → Opens challenge
- ✅ **Works on iOS** devices and web browsers

## Testing

After deploying, test these URLs:

1. **Homepage**: https://zaenj.github.io/fitrival-support/
2. **Support**: https://zaenj.github.io/fitrival-support/support.html
3. **Terms**: https://zaenj.github.io/fitrival-support/terms.html
4. **Privacy**: https://zaenj.github.io/fitrival-support/privacy.html
5. **Challenge redirect**: https://zaenj.github.io/fitrival-support/challenge.html?c=test123

## Customization

### Contact Email

Already configured with: **fitrival@hotmail.com**

### App Store Links

Already configured with your iOS App ID: **6757563823**

## Features

### 🏠 Landing Page
- Hero section with app preview
- Feature showcase
- Download buttons
- Responsive design

### 🆘 Support Page
- Comprehensive FAQ covering:
  - Getting started
  - Challenges
  - Streaks & Progress
  - Account & Settings
  - Troubleshooting
- Contact information

### 📜 Legal Pages
- **Terms of Service**: Complete terms covering all app features
- **Privacy Policy**: GDPR and CCPA compliant, transparent data practices

### 🔗 Challenge Redirect
- Smart deep linking
- Automatic app detection
- App store fallback
- Clean user experience

## Maintenance

### Updating Content

To update any page:
1. Edit the HTML file locally
2. Upload to GitHub (replaces old version)
3. Changes appear in 1-2 minutes

### Adding New Pages

1. Create new HTML file
2. Copy navigation from existing pages
3. Include `<link rel="stylesheet" href="styles.css">`
4. Upload to GitHub

## Support

If you need help with the website, check:
- GitHub Pages docs: https://pages.github.com/
- Or contact GitHub support

## Design

The website uses:
- **Colors**: Teal (#14b8a6) matching your app
- **Font**: System fonts (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto)
- **Style**: Modern, clean, mobile-first design
- **Responsive**: Works perfectly on all screen sizes

Enjoy your new website! 🎉
