# Noon Islamic - Web Pages

This repository contains the marketing and support pages for the Noon Islamic mobile app.

## 📱 Pages

- **[market.html](market.html)** - Premium marketing landing page with app screenshots
- **[index.html](index.html)** - Support and information page

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions.

### Setup GitHub Pages:

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"
4. Push your changes to the `main` branch
5. GitHub Actions will automatically deploy your site

### Your site will be available at:
```
https://[your-username].github.io/noon-suport/
```

**Direct page URLs:**
- Marketing page: `https://[your-username].github.io/noon-suport/market.html`
- Support page: `https://[your-username].github.io/noon-suport/index.html`

## 📂 Repository Structure

```
noon-suport/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions workflow
├── assets/
│   └── *.png                   # App screenshots
├── index.html                  # Support page
├── market.html                 # Marketing page
└── README.md                   # This file
```

## 🔄 Auto-Deployment

Every time you push to the `main` branch, GitHub Actions will:
1. Checkout your code
2. Setup GitHub Pages
3. Upload all files as artifacts
4. Deploy to GitHub Pages

You can also manually trigger the deployment from the **Actions** tab.

## 📝 Making Changes

1. Edit your HTML files locally
2. Commit your changes:
   ```bash
   git add .
   git commit -m "Update pages"
   git push origin main
   ```
3. Wait ~1-2 minutes for automatic deployment
4. Your changes will be live!

## 📧 Support

For questions about the Noon Islamic app, email: mohammedragehzxz@gmail.com

---

© 2026 Noon Islamic. Made with ❤️ for the Muslim Ummah
