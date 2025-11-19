# 🚀 Deploy Instructions untuk GitHub

## Step 1: Upload Files ke GitHub Repository

### Files yang perlu di-upload:

1. **index.html** - Main application (Wajib)
2. **logo.svg** - App logo (Wajib)
3. **manifest.json** - PWA configuration (Wajib)
4. **sw.js** - Service worker (Wajib)
5. **README.md** - Documentation (Recommended)

### Upload Process:

#### Method A: GitHub Web Interface (Easiest)
1. Go to: **https://github.com/synexistech/Nuha_MiniTv**
2. Click **"uploading an existing file"** link
3. Drag & drop ALL files atau select them one by one:
   - index.html
   - logo.svg  
   - manifest.json
   - sw.js
   - README.md
4. Add commit message: **"Initial commit - Nuha's Mini TV app"**
5. Click **"Commit new files"**

#### Method B: Git Commands (If you have Git installed)
```bash
# Clone repository
git clone https://github.com/synexistech/Nuha_MiniTv.git
cd Nuha_MiniTv

# Copy all files to repository folder
# (copy index.html, logo.svg, manifest.json, sw.js, README.md)

# Add files
git add .

# Commit
git commit -m "Initial commit - Nuha's Mini TV app"

# Push to GitHub
git push origin main
```

## Step 2: Enable GitHub Pages

1. Go to repository **Settings**
2. Scroll to **"Pages"** in left sidebar
3. Under **"Source"**, select:
   - **"Deploy from a branch"**
   - **Branch: main**
   - **Folder: / (root)**
4. Click **"Save"**
5. Wait 2-3 minutes untuk deployment complete

## Step 3: Get Your Live URL

After Pages enabled, you will get:
```
https://synexistech.github.io/Nuha_MiniTv/
```

## Step 4: Test Your App

1. Open the URL dalam browser
2. Check semua features:
   - ✅ Logo loads
   - ✅ Colorful buttons work
   - ✅ Videos play (Ms Rachel)
   - ✅ Timer counts down
   - ✅ Parent controls (PIN: 1234)

## Step 5: Install di Android Phone

1. Open URL dalam Chrome browser
2. Browser akan show **"Install"** prompt
3. Tap **"Install"** or **"Add to Home screen"**
4. App icon akan appear di home screen!

---

## 📱 App Information:

**App Name:** Nuha's Mini TV  
**Default Timer:** 45 minutes  
**Parent PIN:** 1234  
**Age Target:** 12+ months  
**Content:** Ms Rachel educational videos  

**Categories:**
- Letters (ABC learning)
- Numbers (Counting)
- Colors (Color recognition)
- Songs (Educational songs)
- Animals (Animal sounds)

---

## 🎯 Quick Test URLs:

**Main App:** https://synexistech.github.io/Nuha_MiniTv/  
**Test Page:** https://synexistech.github.io/Nuha_MiniTv/test.html

## 🔧 Troubleshooting:

**Pages not working:**
- Wait 5-10 minutes after enabling
- Check repository name matches URL
- Ensure files are in root folder, not in subfolder

**App not installing:**
- Try Chrome browser (not Safari)
- Clear browser cache
- Try Samsung Internet browser

**Videos not loading:**
- Check internet connection
- YouTube videos require internet
- Try different category if one doesn't work

---

**🚀 Your app will be live at: https://synexistech.github.io/Nuha_MiniTv/**