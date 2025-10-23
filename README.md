Exora — Creative Studio (Sri Lanka)

A simple, fast, mobile-first static website for Exora to showcase drone videography services and web development work. Built with Bootstrap 5 and deployable on GitHub Pages for free.

Features
- Responsive Bootstrap 5.3 layout
- Brand gradient (deep blue → purple), gold accents, white text
- Sections: Hero, Services, Pricing, Portfolio, About/License, Contact
- TikTok link for growth; WhatsApp note (to add once eligible)
- SEO-ready: meta tags, Open Graph, fast loading, lazy-loaded images
- Easy to extend as your portfolio grows

Getting Started
1. Edit content in `index.html` (texts, links, images).
2. Replace the placeholder logo by saving your circular Exora logo as `assets/img/logo.png`.
3. Replace Unsplash placeholder images in the Portfolio section with your own.

Local Preview
Open `index.html` directly in your browser, or use a simple static server (recommended for correct caching):

```bash
# Using Python 3
cd D:/ExoraSite
python -m http.server 8000
# Then open http://localhost:8000
```

Deploy to GitHub Pages (Free)
1. Create a new GitHub repo named `exora-site` (or any name).
2. Push this folder's contents to the repo's `main` branch.
3. In GitHub > Settings > Pages: set Source to `Deploy from a branch`, Branch to `main / root`.
4. Wait 1–2 minutes. Your site will be live at the GitHub Pages URL shown.

Optional: Add a custom domain later via the same Pages settings.

Editing Notes
- Colors and spacing are defined in `assets/css/styles.css` via CSS variables.
- Images are lazy-loaded (`loading="lazy"`). Keep image sizes optimized for speed.
- Scripts are deferred. Keep third-party scripts minimal.

License & Credits
- Bootstrap 5.3+ (MIT)
- Placeholder images from Unsplash (replace as you build your portfolio)












