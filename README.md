# 🌐 Mohamed Faroug Hassan — Personal Portfolio Website

> A bilingual (Arabic / English) personal portfolio website for **Mohamed Faroug Hassan Soliman**, L2/L3 Network & Infrastructure Engineer based in Jeddah, Saudi Arabia.

---

## 🔗 Live Preview

**https://mfh.genrealtech.com/**  

---

## 📸 Screenshots

| Home | About | Portfolio |
|------|-------|-----------|
| Hero section with social links | Experience timeline & skills | Project cards |

---

## ✨ Features

- 🌍 **Bilingual** — Full Arabic (RTL) and English (LTR) toggle
- 🌙 **Dark / Light mode** toggle
- 📱 **Fully responsive** — mobile, tablet & desktop
- 🧭 **Multi-page SPA** — Home, About, Portfolio, Blog, Contact
- ✍️ **Blog system** — write and publish posts directly from the browser
- 📊 **Animated skill bars** and counter stats
- 🎨 **Smooth animations** — fade-in, floating orbs, pulse effects
- 🔗 **Social links** — WhatsApp, LinkedIn, GitHub, YouTube, Twitter, Facebook
- 📄 **CV download** button

---

## 🗂️ File Structure

```
portfolio/
├── index.html          # Main website (single file)
├── 1755410972131.png   # Profile photo
├── cv.pdf              # CV / Resume file
└── README.md           # This file
```

---

## 📥 How to Clone & Run Locally

Anyone can download this project and run it on their own computer in 3 steps.

### Step 1 — Clone the repository

Open your terminal and run:

```bash
git clone https://github.com/Mohamed-Faroug/My_Personal_Portfolio_Website.git
```

Or click the green **"Code"** button on this page → **"Download ZIP"** → extract the folder.

### Step 2 — Open in your browser

No installation or server needed. Just open the file:

```bash
cd Mohamed-Faroug.github.io
open index.html        # Mac
start index.html       # Windows
xdg-open index.html    # Linux
```

Or drag `index.html` directly into any browser (Chrome, Firefox, Edge).

### Step 3 — Edit with any text editor

Open `index.html` in:
- **VS Code** *(recommended)* — [code.visualstudio.com](https://code.visualstudio.com)
- Notepad++ (Windows)
- Any plain text editor

---

## ✏️ How to Customize for Yourself

All content lives inside one file: **`index.html`**

Use **Ctrl+F** (or Cmd+F on Mac) to search and find what you want to change.

### 🔤 Change Name & Title
Search for: `Mohamed Faroug`
Replace with your own name throughout the file.

### 🖼️ Change Profile Photo
Replace the file `1755410972131.png` with your own photo.
Keep the **same filename**, or update this line in `index.html`:
```html
<img src="1755410972131.png" alt="Mohamed Faroug" class="profile-img">
```

### 📄 Change CV File
Replace the PDF file with your own.
Update this line in `index.html`:
```html
<a href="YOUR_CV_FILENAME.pdf" download ...>
```

### 💼 Change Work Experience
Search for: `timeline-item`
Each block looks like this — edit the company, role, dates and bullet points:
```html
<div class="timeline-item fade-in">
  <div class="timeline-period">Oct 2024 — Jan 2026</div>
  <div class="timeline-company">COMPANY NAME</div>
  <div class="timeline-role">Your Role Title</div>
  <ul class="timeline-points">
    <li>What you did here...</li>
  </ul>
</div>
```

### 📊 Change Skill Percentages
Search for: `skill-bar-fill`
Change the `width` value (0–100%):
```html
<div class="skill-bar-fill" style="width:90%"></div>
```

### 🔗 Change Social Links
Search for: `hero-socials`
Update the `href` values with your own profile URLs:
```html
<a href="https://wa.me/YOUR_NUMBER" ...>
<a href="https://linkedin.com/in/YOUR_PROFILE" ...>
<a href="https://github.com/YOUR_USERNAME" ...>
```

### 📧 Change Email
Search for: `mohamedfaroughassan@gmail.com`
Replace with your own email address.

### ✍️ Change Blog Posts
Search for: `samplePosts`
Edit the title, category, date, and content of each post:
```javascript
const samplePosts = [
  {
    title: "Your Blog Post Title",
    category: "Networking",
    date: "March 2026",
    content: `Your content here...`
  }
];
```

### 🎨 Change Colors
Search for: `:root {`
Edit the CSS color variables at the top:
```css
:root {
  --blue: #2563EB;    /* Main accent color */
  --green: #10B981;   /* Secondary accent */
  --navy: #0F172A;    /* Background */
}
```

---

## 🚀 How to Deploy on GitHub Pages

### Step 1 — Create a Repository

1. Go to [github.com](https://github.com) and sign in
2. Click **"New repository"**
3. Name it exactly: `YOUR-USERNAME.github.io`
4. Set it to **Public**
5. Click **"Create repository"**

### Step 2 — Upload Files

1. Click **"uploading an existing file"**
2. Drag & drop all files:
   - `index.html`
   - your photo (`.png`)
   - your CV (`.pdf`)
   - `README.md`
3. Click **"Commit changes"**

### Step 3 — Enable GitHub Pages

1. In your repository → click **Settings**
2. Scroll to **"Pages"** in the left sidebar
3. Under **"Source"** select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait ~2 minutes, then visit:

```
https://YOUR-USERNAME.github.io
```

---

## 🛠️ Built With

| Technology | Usage |
|------------|-------|
| HTML5 / CSS3 | Structure & styling |
| Vanilla JavaScript | Interactivity, language toggle, blog |
| Google Fonts | Cairo (Arabic) · Poppins (English) |
| Inline SVG | Brand social icons |
| CSS Animations | Fade-in, floating orbs, skill bars |

> ✅ No frameworks. No npm. No build step. Works offline.

---

## 📬 Contact

| Platform | Link |
|----------|------|
| 📧 Email | mohamedfaroughassan@gmail.com |
| 💬 WhatsApp | [wa.me/966548239346](https://wa.me/966548239346) |
| 💼 LinkedIn | [linkedin.com/in/mohamed-faroug](https://linkedin.com/in/mohamed-faroug) |
| 🐙 GitHub | [github.com/Mohamed-Faroug](https://github.com/Mohamed-Faroug) |
| ▶️ YouTube | [youtube.com/@Mohamed-Faroug](https://www.youtube.com/@Mohamed-Faroug) |
| 🐦 Twitter | [twitter.com/MohamedFroug](https://twitter.com/MohamedFroug) |
| 📘 Facebook | [facebook.com/Mohamed.Froug](https://facebook.com/Mohamed.Froug) |

---

## 📜 License

This project is open source. Feel free to clone, edit, and use it as a template for your own portfolio.
If you use it, a credit or a ⭐ star on this repo is appreciated!

---

© 2026 Mohamed Faroug Hassan Soliman — All Rights Reserved
