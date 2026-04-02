# MyHub PWA — Setup Instructions

## How to get this on your phone in 5 steps

### Step 1 — Create a free GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the "+" icon top right → "New repository"
2. Name it: `myhub`
3. Set it to **Public**
4. Check "Add a README file"
5. Click "Create repository"

### Step 3 — Upload your files
1. Inside your new repo, click "Add file" → "Upload files"
2. Upload ALL files from this folder:
   - index.html
   - manifest.json
   - sw.js
   - icons/ (the whole folder with both icons)
3. Click "Commit changes"

### Step 4 — Enable GitHub Pages
1. Go to your repo Settings → Pages (left sidebar)
2. Under "Source" select "Deploy from a branch"
3. Select branch: `main`, folder: `/ (root)`
4. Click Save
5. Wait 1-2 minutes, then your app will be live at:
   `https://YOUR-USERNAME.github.io/myhub`

### Step 5 — Add to your phone home screen
**iPhone:**
1. Open the URL in Safari (must be Safari, not Chrome)
2. Tap the Share button (box with arrow)
3. Scroll down → tap "Add to Home Screen"
4. Tap "Add" — done!

**Android:**
1. Open the URL in Chrome
2. Tap the 3-dot menu
3. Tap "Add to Home Screen" or "Install app"

---

## Updating the app
When you want to add new features, come back to Claude, describe what you want changed, and Claude will give you updated files. Just re-upload them to GitHub and your app updates automatically.
