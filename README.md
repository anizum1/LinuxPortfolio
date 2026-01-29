# AkmOS Portfolio - GitHub Setup Guide

## 📦 Files You Need to Upload to GitHub

All these files MUST be in the **same folder** (repository root):

### Required Files:
1. `kali-desktop-portfolio.html` - Main website (rename to `index.html` for GitHub Pages)
2. `Akm_Nizum_Resume__1_.pdf` - Your resume
3. `Certs.pdf` - Your certificates
4. `dragon-logo-blue.png` - Dragon logo
5. `dragon-logo-purple.png` - Alternative dragon logo
6. `wallpaper-code.png` - Desktop wallpaper
7. `wallpaper-ai.png` - Login screen background
8. `wallpaper-hacker.png` - Extra wallpaper

### Optional Files:
- `README.md` - This file (for documentation)

---

## 🚀 Quick Setup Steps

### Step 1: Create GitHub Repository
```bash
1. Go to https://github.com
2. Click "New repository"
3. Name it: "akm-portfolio" (or any name you like)
4. Make it PUBLIC
5. Click "Create repository"
```

### Step 2: Upload Files

**Option A: Using GitHub Web Interface (Easiest)**
```
1. Click "uploading an existing file"
2. Drag and drop ALL the files listed above
3. Write commit message: "Initial portfolio upload"
4. Click "Commit changes"
```

**Option B: Using Git Command Line**
```bash
# Clone your repository
git clone https://github.com/YOUR-USERNAME/akm-portfolio.git
cd akm-portfolio

# Copy all files to this folder
# Then:
git add .
git commit -m "Initial portfolio upload"
git push origin main
```

### Step 3: Rename Main File
```
1. In GitHub, click on "kali-desktop-portfolio.html"
2. Click the pencil icon (Edit)
3. Change filename to: "index.html"
4. Commit changes
```

### Step 4: Enable GitHub Pages
```
1. Go to repository Settings
2. Scroll to "Pages" section (left sidebar)
3. Under "Source", select: main branch
4. Click Save
5. Your site will be live at:
   https://YOUR-USERNAME.github.io/akm-portfolio/
```

---

## 📁 Final Folder Structure

Your GitHub repository should look like this:

```
akm-portfolio/
├── index.html                      (renamed from kali-desktop-portfolio.html)
├── Akm_Nizum_Resume__1_.pdf
├── Certs.pdf
├── dragon-logo-blue.png
├── dragon-logo-purple.png
├── wallpaper-code.png
├── wallpaper-ai.png
├── wallpaper-hacker.png
└── README.md                       (optional)
```

---

## ✅ Testing Your Portfolio

After setup, test these features:

### Login Screen
- Password: `password`
- Should see AI hacker background
- Blue dragon logo should appear

### Desktop
- Should see code wallpaper background
- 10 desktop icons visible
- Dragon logo in top-left corner

### Applications Menu (Top Bar)
- Click "Applications" → dropdown menu appears
- Click any item → opens that application
- System → Shows system info
- Help → Shows help guide

### Desktop Icons
- Terminal → Opens working terminal
- About Me → Opens your bio
- Experience → Opens folder with 2 files
- Certifications → Opens folder with 4 certificates
- Each certificate has "View Certificate PDF" button
- Projects, Skills, Tools → All open as folders
- Contact & Services → Open as single files
- Resume.pdf → Downloads immediately

### Terminal Commands
Test these commands:
- `help` - Shows all commands
- `ls` - Lists files
- `cat about` - Shows about content
- `neofetch` - Shows system info
- `clear` - Clears screen
- `download` - Downloads resume

---

## 🐛 Troubleshooting

### Images Not Loading
**Problem:** Wallpapers or logos not showing
**Solution:** Make sure ALL .png files are in the same folder as index.html

### Certificates Not Opening
**Problem:** PDF doesn't open when clicked
**Solution:** Make sure `Certs.pdf` is in the same folder as index.html

### GitHub Pages Not Working
**Problem:** Site not loading
**Solution:** 
1. Check repository is PUBLIC
2. Make sure main file is named `index.html`
3. Wait 2-3 minutes after enabling Pages
4. Check Settings → Pages for any errors

### Commands Not Working in Terminal
**Problem:** Terminal commands don't respond
**Solution:** Make sure you clicked inside the terminal input box (the text cursor should be blinking)

---

## 🎨 Customization Options

### Change Wallpapers
Replace these files with your own images (keep same names):
- `wallpaper-code.png` - Desktop background
- `wallpaper-ai.png` - Login screen
- `wallpaper-hacker.png` - Alternative (not currently used)

### Change Logo
Replace `dragon-logo-blue.png` with your own logo

### Change Password
Edit `index.html`, find line:
```javascript
if (password === 'password') {
```
Change `'password'` to your desired password

### Add More Content
Edit the `fileSystem` object in the JavaScript section to add more files/folders

---

## 📧 Support

If you have issues:
1. Check all files are uploaded
2. Check file names match exactly (case-sensitive!)
3. Verify GitHub Pages is enabled
4. Wait a few minutes and refresh

---

## 🎉 Your Portfolio is Live!

Share your portfolio:
- Direct link: `https://YOUR-USERNAME.github.io/akm-portfolio/`
- Add to LinkedIn profile
- Add to resume
- Share with recruiters

**Remember:** Every time you update files, commit and push changes to GitHub. GitHub Pages will automatically update your site within a few minutes!

---

## 📝 Notes

- All images load from same directory (no subfolders needed)
- Portfolio works 100% client-side (no server required)
- Fully responsive - works on mobile, tablet, desktop
- No database needed - all content embedded in HTML
- Fast loading - all assets optimized
- Professional Kali Linux aesthetic
- Interactive terminal and GUI modes

Enjoy your awesome cybersecurity portfolio! 🚀🔒
