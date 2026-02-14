# Time vs Books - PWA Installation Guide

## Quick Setup (5 minutes)

### Step 1: Upload to GitHub Pages

1. Go to https://github.com and sign in (or create free account)
2. Click "New repository" (green button)
3. Name it: `time-vs-books`
4. Make it Public
5. Check "Add a README file"
6. Click "Create repository"

### Step 2: Upload Files

1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop these files:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
3. Click "Commit changes"

### Step 3: Enable GitHub Pages

1. Go to repository Settings
2. Click "Pages" in left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes

### Step 4: Install on Android

1. GitHub will show you a URL like: `https://yourusername.github.io/time-vs-books`
2. Open that URL on your Android phone in Chrome
3. Chrome will show a banner "Add to Home Screen" or tap ⋮ menu → "Install app"
4. Tap "Install"
5. Done! The app appears on your home screen like a native app

## Alternative: Netlify Drop (Even Easier!)

1. Go to https://app.netlify.com/drop
2. Drag the `pwa-app` folder onto the page
3. Get instant URL like `random-name.netlify.app`
4. Open on Android Chrome → Install

## Files Included

- `index.html` - The main app (your time tracker)
- `manifest.json` - App metadata (name, icon, colors)
- `service-worker.js` - Makes it work offline
- This README

## Features When Installed

✅ Works offline
✅ Appears as separate app (not in browser)
✅ Full screen (no browser UI)
✅ App icon on home screen
✅ Saves progress locally

## Troubleshooting

**"Add to Home Screen" doesn't appear?**
- Make sure you're using Chrome on Android
- Wait a few seconds on the page
- Try ⋮ menu → "Install app" manually

**App not working offline?**
- Open it once while online first
- Close and reopen to activate service worker

Need help? The app works great as a regular webpage too - just open the HTML file!
