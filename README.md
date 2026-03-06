# 🖥️ Personal Website

A dark-mode, techy personal resume/CV website — ready for GitHub Pages deployment.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it **`yourusername.github.io`** (replace `yourusername` with your actual GitHub username)
3. Set it to **Public**
4. Click **Create repository**

### Step 2: Push this code
```bash
# Clone your new repo
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io

# Copy index.html into this folder, then:
git add .
git commit -m "Initial commit: personal website"
git push origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch and **/ (root)** folder
4. Click **Save**
5. Your site will be live at: `https://yourusername.github.io`

## ✏️ Customise

Open `index.html` and search/replace these placeholders:

| Placeholder | Replace With |
|---|---|
| `Your Name Here` | Your actual name |
| `your_name` | Your name/handle |
| `your@email.com` | Your email address |
| `yourusername` | Your GitHub/LinkedIn/Twitter username |
| `Birmingham, UK` | Your location |
| `Full-Stack Developer` | Your actual role |

Update the **About Me** text, **Projects**, **Skills**, and **Stats** to reflect your real experience.

## 📁 Structure

```
/
├── index.html    ← Entire site (single file, zero dependencies)
└── README.md     ← This file
```

## 🎨 Features

- Dark mode with cyberpunk/terminal aesthetic
- Scroll-triggered animations
- Responsive mobile layout
- Scroll progress indicator
- Scanline + grid background effects
- Contact form (connect to Formspree/Netlify for functionality)
- Zero external dependencies (just Google Fonts)

## 📝 License

Free to use and modify for personal use.
