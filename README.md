# Raunak Pandey — Product Portfolio

A dark, metrics-forward portfolio showcasing product leadership across B2B SaaS, Data & AI platforms.

## 🚀 Quick Deploy to GitHub Pages

1. Create a new GitHub repository (e.g., `portfolio` or `pandeyraunak007.github.io`)
2. Upload all files from this folder maintaining the structure:
   ```
   /
   ├── index.html
   ├── images/
   │   ├── ai-data-modeler-canvas.png
   │   ├── ai-modeler-architecture.png
   │   ├── ai-modeler-flow.png
   │   └── rag-assistant-ui.png
   └── README.md
   ```
3. Go to **Settings → Pages**
4. Under "Source", select **main** branch and **/ (root)** folder
5. Click Save — your site will be live at `https://[username].github.io/[repo-name]`

## 📷 Adding Images Later

For the **Data Product Analytics Platform** and **AI Data Dictionary Generator** projects:

1. Add your screenshots to the `/images` folder with descriptive names like:
   - `analytics-platform-dashboard.png`
   - `data-dictionary-ui.png`

2. In `index.html`, find the project cards (search for `project-placeholder`) and replace:

```html
<!-- Before -->
<div class="project-placeholder">
    📷 Screenshots coming soon
</div>

<!-- After -->
<div class="visual-card" onclick="openLightbox(this)" style="margin-top: 24px;">
    <img src="images/analytics-platform-dashboard.png" alt="Analytics Platform Dashboard">
    <div class="visual-card-label">Feature Usage Dashboard</div>
</div>
```

## 🎨 Customization

**Colors** — Edit CSS variables at the top of `index.html`:
```css
:root {
    --accent: #d4a039;  /* Change this for different accent color */
}
```

**Content** — All text is in the HTML. Search for section names to edit.

## 📱 Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Animated metric counters
- ✅ Image lightbox for screenshots
- ✅ Smooth scroll navigation
- ✅ Dark + Amber/Gold theme
- ✅ No external dependencies (except Google Fonts)

## 📝 License

Personal portfolio — feel free to use as inspiration for your own.
