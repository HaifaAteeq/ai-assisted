# PWA Setup Instructions

## Files Included

- `index.html` - Main app page
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline support
- `icon-192.svg` - App icon (SVG format)

## Before Uploading to GitHub Pages

### Step 1: Create PNG Icons

You need to convert the SVG icon to PNG. Use any of these:

**Online (easiest):**
1. Go to https://svgtopng.com/
2. Upload `icon-192.svg`
3. Download as `icon-192.png`
4. Download again at 512x512 as `icon-512.png`

**Or use Canva/Figma:**
1. Import the SVG
2. Export as PNG at 192x192 and 512x512

### Step 2: Update GitHub Username

In `index.html`, find this line at the bottom:
```html
<a href="https://github.com/yourusername/ai-assisted-thinking">
```
Change `yourusername` to your actual GitHub username.

### Step 3: Upload to GitHub

1. Create a repository named `ai-assisted-thinking` (or any name)
2. Upload all files from this `pwa` folder to the root
3. Go to Settings → Pages
4. Set Source to "main" branch
5. Save

### Step 4: Your PWA is Live!

Your app will be at:
```
https://yourusername.github.io/ai-assisted-thinking/
```

## Features

- ✅ Works on phone and computer
- ✅ Can be installed as app
- ✅ Works offline (after first visit)
- ✅ Copy prompt with one click
- ✅ Simple 2-tab interface

## Sharing

Just share the link:
```
https://yourusername.github.io/ai-assisted-thinking/
```

People can:
1. Open link
2. See instructions
3. Copy prompt
4. Start learning

---
