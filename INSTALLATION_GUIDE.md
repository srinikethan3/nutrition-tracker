# 📱 Pregnancy Nutrition Tracker - Installation Guide

## What You Need
1. `pregnancy-nutrition-tracker.html` (the main app file)
2. `manifest.json` (app configuration)
3. `sw.js` (service worker for offline use)

All three files must be in the same folder!

---

## 🍎 Installation on iPhone/iPad

### Method 1: Using Safari (Recommended)

1. **Upload files to a web hosting service** (see options below)
   
2. **Open the URL in Safari** on your iPhone
   
3. **Tap the Share button** (square with arrow pointing up) at the bottom
   
4. **Scroll down and tap "Add to Home Screen"**
   
5. **Tap "Add"** in the top right
   
6. The app icon (🤰) will appear on your home screen!

### Method 2: Save Locally and Open

1. **Save all 3 files to iCloud Drive** or **Files app**
   
2. **Open `pregnancy-nutrition-tracker.html` in Safari**
   
3. **Follow steps 3-6 from Method 1 above**

---

## 🤖 Installation on Android

### Using Chrome (Recommended)

1. **Upload files to a web hosting service** (see options below)
   
2. **Open the URL in Chrome** on your Android phone
   
3. **Look for the "Install" prompt** that appears at the bottom
   - OR tap the **three dots menu** (⋮) at the top right
   - Select **"Add to Home Screen"** or **"Install App"**
   
4. **Tap "Install"**
   
5. The app will be added to your home screen and app drawer!

### Alternative: Save Locally

1. **Save all 3 files to your phone** (Downloads folder)
   
2. **Open `pregnancy-nutrition-tracker.html` with Chrome**
   
3. **Follow steps 3-5 from above**

---

## 🌐 Hosting Options (Required for Full PWA Features)

To get the full app experience with install prompts and offline support, you need to host the files online. Here are FREE options:

### Option 1: GitHub Pages (Free, Easy)

1. Create a free account at https://github.com
2. Create a new repository (name it anything, e.g., "nutrition-tracker")
3. Upload all 3 files to the repository
4. Go to Settings → Pages
5. Enable GitHub Pages (select "main" branch)
6. You'll get a URL like: `https://yourusername.github.io/nutrition-tracker/pregnancy-nutrition-tracker.html`
7. Open this URL on your phone and install!

### Option 2: Netlify (Free, Very Easy)

1. Go to https://www.netlify.com
2. Sign up for free
3. Drag and drop the folder containing all 3 files
4. You'll get a URL like: `https://random-name.netlify.app/pregnancy-nutrition-tracker.html`
5. Open on your phone and install!

### Option 3: Google Drive (Quick but Limited)

1. Upload all files to Google Drive
2. Right-click → "Get link" → "Anyone with the link"
3. Open the HTML file link in mobile browser
4. This works but won't show "Install App" prompt

### Option 4: Local Network (No Internet Needed)

If you have a computer and phone on the same WiFi:

1. **Windows:** 
   - Put files in `C:\xampp\htdocs\` or use Python: `python -m http.server 8000`
   
2. **Mac:** 
   - Put files in a folder, then run: `python3 -m http.server 8000`
   
3. **Find your computer's IP address**
   - Windows: Open CMD, type `ipconfig`, look for "IPv4 Address"
   - Mac: System Preferences → Network
   
4. **On your phone, open:** `http://YOUR_IP:8000/pregnancy-nutrition-tracker.html`

---

## ✅ Verification

After installation, the app should:
- ✅ Appear as an icon on your home screen
- ✅ Open in full screen (no browser UI)
- ✅ Work offline after first load
- ✅ Save all your meal data permanently
- ✅ Look and feel like a native app

---

## 🔧 Troubleshooting

**"Add to Home Screen" option not showing?**
- Make sure you're using Safari (iPhone) or Chrome (Android)
- Some browsers don't support PWA installation

**App not installing?**
- Ensure all 3 files are in the same folder/directory
- Check that the URL ends with `.html` not `.txt`

**Data not saving?**
- The app uses browser storage - don't clear Safari/Chrome data
- Make sure you're opening the same file/URL each time

**Install prompt not appearing?**
- This is normal if opening locally - the app still works!
- For full PWA features, use one of the hosting options above

---

## 📝 Usage Tips

1. **Log meals daily** for best tracking
2. **Check analysis weekly** to see trends
3. **Screenshot recommendations** to share with your doctor
4. **Export data:** Currently manual (write down important insights)
5. **Backup:** The data is stored in browser - don't clear browser data!

---

## 🆘 Need Help?

If you face issues:
1. Make sure all 3 files are together
2. Try opening in Safari (iOS) or Chrome (Android)
3. Check that JavaScript is enabled in browser settings
4. Try one of the hosting options for best experience

---

**Enjoy tracking your pregnancy nutrition! 🤰✨**
