# CashBook PWA — GitHub Pages Deployment

## Files in this package
```
cashbook-pwa/
├── index.html       ← Main app
├── manifest.json    ← PWA config
├── sw.js            ← Service worker (offline support)
├── README.md        ← This file
└── icons/
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

## Deploy to GitHub Pages (5 minutes)

### Step 1 — Create GitHub account
Go to https://github.com and sign up (free)

### Step 2 — Create a new repository
1. Click the green "New" button
2. Name it: `cashbook`
3. Set to **Public**
4. Click "Create repository"

### Step 3 — Upload files
1. Click "uploading an existing file" link
2. Drag and drop ALL files from this folder (including the icons/ folder)
3. Click "Commit changes"

### Step 4 — Enable GitHub Pages
1. Go to your repo → Settings → Pages
2. Under "Source" select: **Deploy from a branch**
3. Branch: **main** / Folder: **/ (root)**
4. Click Save

### Step 5 — Your app is live!
Wait 2 minutes, then visit:
`https://YOUR-GITHUB-USERNAME.github.io/cashbook`

## Install on Android Phone

1. Open Chrome on your Android phone
2. Visit your GitHub Pages URL
3. Chrome will show a banner: **"Add CashBook to Home screen"**
4. Tap **Install** or **Add**
5. CashBook icon appears on your home screen!
6. Tap it — opens full screen like a real app ✅

## Share with family/friends
Send them the same URL — they open it in Chrome,
tap "Add to Home screen" and they're all set.
All data syncs via Supabase cloud in real time.
