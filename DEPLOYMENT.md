# Tilcor Nigeria Website - Deployment Guide

## Project Overview

This is a complete recreation of a roofing website template, customized for Tilcor Nigeria - a premium stone coated steel roofing company. The website includes:

- **Responsive Design**: Bootstrap 4 framework
- **Modern UI/UX**: Professional roofing industry design
- **Nigerian Localization**: Content tailored for Nigerian market
- **Complete Template Recreation**: All original styles and functionality preserved
- **SEO Optimized**: Meta tags and structured content

## Local Development

The website is currently running locally at: http://localhost:8000

### Local Server Commands
```bash
# Start local server
python3 -m http.server 8000

# Or using Node.js
npx http-server -p 8000
```

## Deployment to Render.com

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository named `tilcor-nigeria`
2. Make it public for free Render deployment
3. Don't initialize with README (we already have one)

### Step 2: Push Code to GitHub

```bash
# Add GitHub remote (replace with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/tilcor-nigeria.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Deploy to Render

1. Go to [Render Dashboard](https://dashboard.render.com)
2. Click "New +" → "Static Site"
3. Connect your GitHub repository
4. Configure deployment settings:
   - **Name**: `tilcor-nigeria`
   - **Branch**: `main`
   - **Build Command**: `echo "No build required"`
   - **Publish Directory**: `.` (root directory)
   - **Auto-Deploy**: Yes

### Step 4: Custom Domain (Optional)

1. In Render dashboard, go to your static site
2. Navigate to "Settings" → "Custom Domains"
3. Add your custom domain (e.g., `www.tilcornigeria.com`)
4. Configure DNS records as instructed by Render

## Website Features Implemented

### ✅ Template Recreation
- [x] Pixel-perfect recreation of original template
- [x] All CSS styles preserved
- [x] JavaScript functionality maintained
- [x] Responsive design intact
- [x] Bootstrap 4 framework
- [x] Font Awesome icons
- [x] Owl Carousel sliders
- [x] Magnific Popup galleries

### ✅ Nigerian Localization
- [x] Tilcor Nigeria branding
- [x] Nigerian contact information
- [x] Local business hours
- [x] Nigerian cities in project examples
- [x] Currency and measurement localization
- [x] Nigerian testimonials

### ✅ Content Sections
- [x] Hero section with Nigerian messaging
- [x] About section with company information
- [x] Products section (Tilcor roofing profiles)
- [x] Statistics counter
- [x] Project gallery
- [x] Customer testimonials
- [x] Contact information
- [x] Footer with business details

### ✅ Technical Implementation
- [x] HTML5 semantic structure
- [x] CSS3 animations and transitions
- [x] jQuery plugins integration
- [x] Mobile-responsive design
- [x] Cross-browser compatibility
- [x] SEO meta tags
- [x] Performance optimized

## File Structure

```
tilcor-nigeria/
├── index.html              # Main homepage
├── css/                    # Stylesheets
│   ├── style.css          # Main styles
│   ├── bootstrap.min.css  # Bootstrap framework
│   └── ...                # Other CSS files
├── js/                     # JavaScript files
│   ├── main.js            # Main functionality
│   ├── jquery.min.js      # jQuery library
│   └── ...                # Other JS libraries
├── images/                 # Image assets
├── fonts/                  # Font files
├── README.md              # Project documentation
├── DEPLOYMENT.md          # This deployment guide
└── .gitignore            # Git ignore rules
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

- Minified CSS and JavaScript
- Optimized images
- CDN resources for external libraries
- Efficient loading order

## Contact Information

For technical support or questions about the website:

**Tilcor Nigeria**
- Address: Plot 123, Lekki-Epe Expressway, Lekki Phase 1, Lagos, Nigeria
- Phone: +234 803 332 4963, +234 808 440 8542
- Email: info@tilcornigeria.com

---

© 2024 Tilcor Nigeria. All rights reserved.
