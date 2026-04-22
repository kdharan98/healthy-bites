# Healthy Bites Website

Premium artisan delicacies website for Healthy Bites brand.

## 🌟 Features

- **3 Premium Products:**
  - Nuts Chocolates (₹450) - Handmade, no preservatives
  - Bottle Poetry Wine Juice (₹650) - NON-ALCOHOLIC grape juice
  - Fruit Jam (₹350) - Fresh fruits, no additives

- **Design:**
  - Luxury aesthetic with black backgrounds
  - Smooth parallax scrolling effects
  - Custom cursor animations
  - Fully responsive (mobile, tablet, desktop)
  - Curved product card layouts
  - Elegant typography (Cinzel, Cormorant Garamond, Jost)

## 📁 Files Included

```
healthy-bites-website/
├── index.html                              # Main website file
├── images/                                 # Product images
│   ├── luxury-products-transparent.png     # Hero section (3 products)
│   ├── chocolate-box-luxury.png            # Chocolate product card
│   ├── image.png                           # Wine bottle product card
│   ├── jam-jar-luxury.png                  # Jam product card
│   └── wine-gift-box-black-bg.png          # Features section
└── README.md                               # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right → **New repository**
3. Name your repository (e.g., `healthy-bites-website`)
4. Choose **Public** (required for free GitHub Pages)
5. Click **Create repository**

### Step 2: Upload Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **uploading an existing file**
2. Drag and drop ALL files from the `healthy-bites-website` folder:
   - `index.html`
   - `images/` folder with all 5 images
   - `README.md`
3. Click **Commit changes**

**Option B: Using Git Command Line**

```bash
# Navigate to the healthy-bites-website folder
cd healthy-bites-website

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Healthy Bites website"

# Add remote repository (replace YOUR-USERNAME and YOUR-REPO)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your GitHub repository, go to **Settings**
2. Scroll down to **Pages** section (left sidebar)
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: Access Your Website

Your website will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO/
```

For example: `https://johnsmith.github.io/healthy-bites-website/`

## 🎨 Customization

### Update Contact Information

Edit `index.html` and find the Contact section (around line 1200):

```html
<span class="contact-detail-val">contact@healthybites.com</span>
<span class="contact-detail-val">+91 98765 43210</span>
```

### Update Product Prices

Find the Products section (around line 1100) and update:

```html
<span class="product-price">₹450</span>
```

### Change Colors

Edit the CSS variables at the top of `index.html`:

```css
:root {
  --black: #0a0705;
  --gold: #c9a84c;
  --cream: #f0e6d3;
  /* ... */
}
```

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Details

- **Pure HTML/CSS/JavaScript** - No build process required
- **No dependencies** - Works standalone
- **Fonts:** Google Fonts (Cinzel, Cormorant Garamond, Jost)
- **File size:** ~50KB HTML + ~2MB images
- **Load time:** < 2 seconds on average connection

## 📞 Support

For issues or questions about deployment, check:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Pages Troubleshooting](https://docs.github.com/en/pages/getting-started-with-github-pages/troubleshooting-404-errors-for-github-pages-sites)

## 📄 License

All rights reserved - Healthy Bites © 2024

---

**Made with ❤️ for Healthy Bites**
