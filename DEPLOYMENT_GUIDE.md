# Quick Deployment Guide

## Upload to GitHub Pages (5 minutes)

### Step 1: Get the Files

All your website files are in the `github-pages` folder:
- ✅ index.html (Landing page)
- ✅ support.html (Support/FAQ)
- ✅ terms.html (Terms of Service)
- ✅ privacy.html (Privacy Policy)
- ✅ challenge.html (Challenge redirect - THIS IS IMPORTANT!)
- ✅ styles.css (All styling)

### Step 2: Upload to GitHub

1. Go to: https://github.com/zaenj/fitrival-support

2. Click "Add file" → "Upload files"

3. Drag ALL 6 files from the `github-pages` folder into GitHub

4. Scroll down and click "Commit changes"

### Step 3: Enable GitHub Pages (if not already enabled)

1. Go to repository Settings

2. Click "Pages" in the left sidebar

3. Under "Source":
   - Branch: **main** (or master)
   - Folder: **/ (root)**

4. Click "Save"

5. Wait 1-2 minutes

### Step 4: Test Your Site

Visit these URLs to make sure everything works:

1. **Homepage**: https://zaenj.github.io/fitrival-support/
2. **Support**: https://zaenj.github.io/fitrival-support/support.html
3. **Challenge Test**: https://zaenj.github.io/fitrival-support/challenge.html?c=test123

### Step 5: Test Challenge Sharing

1. Open the app
2. Go to any challenge
3. Tap the share button (top-right)
4. Share the link to yourself
5. Click the link:
   - **With app installed**: Should open app and show challenge ✓
   - **Without app**: Should show download buttons ✓

## What Changed in Your App

The app now shares links like:
```
https://zaenj.github.io/fitrival-support/challenge.html?c=abc123
```

Instead of:
```
fitrival://challenge/abc123
```

This means it works for **everyone**:
- ✅ Users with the app → Opens in app
- ✅ Users without app → Directed to download
- ✅ Works on iOS devices and web browsers

## Troubleshooting

**Website not appearing?**
- Wait 2-3 minutes after uploading
- Check GitHub Pages settings are correct
- Make sure files are in the root directory (not in a subfolder)

**Challenge links not working?**
- Make sure `challenge.html` is uploaded
- Check the URL format: `...challenge.html?c=CHALLENGE_ID`
- Test with a real challenge from the app

**Links going to old domain?**
- The app is already updated
- Just rebuild the app or restart it
- Share links will now use GitHub Pages

## Custom Domain (Optional)

Want to use `go.fitrival.app` instead of `zaenj.github.io`?

1. Buy a domain (if you don't have one)
2. In GitHub Pages settings → Add custom domain: `go.fitrival.app`
3. In your DNS provider, add a CNAME record:
   ```
   go.fitrival.app → zaenj.github.io
   ```
4. Wait 24-48 hours for DNS to propagate
5. Update the app code to use your custom domain

## Need Help?

If something isn't working:
1. Check the README.md file for more details
2. GitHub Pages docs: https://pages.github.com/
3. Or let me know!

---

**That's it!** Your professional website with challenge sharing is ready to go! 🎉
