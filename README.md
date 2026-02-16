# Vakit : Ezan & Namaz - Marketing Landing Page

Modern, responsive marketing landing page for the Prayer Reminder mobile app.

## 🌐 Live Preview

Open `index.html` in your browser or run:
```bash
npx serve .
# Then visit http://localhost:3000
```

## 📁 File Structure

```
├── index.html              # Main landing page
├── privacy-policy.html     # Privacy policy page
└── assets/
    └── images/
        └── app-icon.png    # App icon (1024x1024)
```

## ✅ Completed

- ✅ Modern, responsive design with teal/emerald theme
- ✅ Hero section with real app icon
- ✅ Stats section (869 districts, 76 duas, etc.)
- ✅ 12 feature cards with gradient icons
- ✅ Screenshot slider (ready for images)
- ✅ CTA section
- ✅ Footer with links
- ✅ Mobile-responsive design
- ✅ Smooth animations
- ✅ SEO meta tags

## 📝 TODO Before Publishing

### 1. Update Store Links
Replace placeholder URLs in `index.html`:

```html
<!-- Find and replace these URLs (appears twice in the file): -->
https://apps.apple.com/YOUR_APP_LINK  → Your actual App Store URL
https://play.google.com/store/apps/YOUR_APP_LINK  → Your actual Google Play URL
```

### 2. Add Screenshots (Optional)
Add app screenshots to the slider section. For each screenshot:

```html
<div class="screenshot-frame">
  <div class="screenshot-notch"></div>
  <!-- Add this: -->
  <img src="assets/images/screenshot-1.png" alt="App Screenshot"
       style="width:100%; height:100%; object-fit:cover;">
</div>
```

Recommended screenshot dimensions: **1170x2532px** (iPhone mockup size)

### 3. Update Contact Email
Replace placeholder email in footer:
```html
<a href="mailto:support@vakit.app">Destek</a>
```

### 4. Add Social Media Links
Update footer social media link (currently placeholder #)

## 🎨 Customization

### Colors
Main color variables are defined at the top of `<style>`:

```css
--primary: #0D9488;        /* Teal */
--primary-dark: #0F766E;   /* Dark Teal */
--secondary: #14B8A6;      /* Light Teal */
--accent: #F59E0B;         /* Gold */
```

### Feature Icons
Currently using emoji with gradient backgrounds. To replace with custom images:

```html
<div class="feature-icon">
  <img src="path/to/icon.png" alt="Feature" style="width:100%; height:100%;">
</div>
```

## 🚀 Deployment Options

### GitHub Pages
1. Push to GitHub repository
2. Go to Settings → Pages
3. Select source branch (main/master)
4. Your site will be at: `https://username.github.io/repo-name`

### Netlify
```bash
# Drag and drop the folder to Netlify
# Or connect your GitHub repo
```

### Firebase Hosting
```bash
firebase init hosting
firebase deploy
```

## 📱 Mobile Responsiveness

The design is fully responsive with breakpoints at:
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

## 🖼️ Adding More Screenshots

To add more screenshots to the slider:

```html
<div class="screenshot-item">
  <div class="screenshot-frame">
    <div class="screenshot-notch"></div>
    <img src="assets/images/screenshot-5.png" alt="Screenshot">
  </div>
</div>
```

## 📊 SEO & Meta Tags

Already included:
- Title tag
- Meta description
- Meta keywords
- Open Graph tags (for social sharing) - can be added if needed

## 🔗 Links to Update

Search for `#` in the HTML and replace with actual URLs:
- App Store link (2 places)
- Google Play link (2 places)
- Privacy Policy link ✅ (already correct)
- Social media links in footer
- Support email

## 💡 Tips

1. **Image Optimization:** Compress app-icon.png and screenshots using TinyPNG or similar
2. **Performance:** Consider lazy loading for images below the fold
3. **Analytics:** Add Google Analytics or similar tracking code before `</body>`
4. **A/B Testing:** Test different headlines and CTAs for better conversion

## 📞 Support

For questions about the landing page design, refer to this README.
For app development questions, see the main project README.md and CLAUDE.md files.
