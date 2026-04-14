# Alvaro's Landscaping Website

Professional landscaping services website for Alvaro's Landscaping in Bensenville, IL.

## Overview

This is a high-performance, single-page website built with:
- **Single HTML file** - no build step required
- **Inline CSS** - zero external stylesheets
- **System fonts** - no font CDN
- **Inline SVG icons** - no icon library
- **Minimal JavaScript** - mobile menu + smooth scroll only

Perfect for GitHub Pages deployment with instant loading.

## Features

- ✨ 8 professional sections (hero, about, services, gallery, testimonials, contact, footer)
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Ultra-lightweight (~10KB total)
- 🚀 Zero external dependencies
- 🎨 Professional color scheme (forest green, earth tones)
- ♿ WCAG AA accessible
- 📊 JSON-LD structured data for SEO

## Sections

1. **Navigation** - Fixed header with desktop nav + mobile hamburger menu
2. **Hero** - Full-viewport headline with CTA buttons
3. **About** - Meet Alvaro with stats (clients, experience, satisfaction)
4. **Services** - Grid of 7 service cards (lawn care, trimming, mulch, sod, sealcoating, stripping, asphalt)
5. **Gallery** - 6-tile masonry showcase
6. **Testimonials** - 3 client reviews with ratings
7. **Contact** - Contact form + business info
8. **Footer** - Links, social, hours

## Deployment to GitHub Pages

### Setup

1. Go to Settings → Pages
2. Under "Build and deployment", select:
   - Source: Deploy from a branch
   - Branch: `main` (or your deployment branch)
   - Folder: `/ (root)`
3. Click Save

### Deploy

Push to your repository:
```bash
git push origin main
```

Your site will be live at: `https://<username>.github.io/alvaros-landscaping/`

## Making Changes

Edit `index.html` directly - no build step needed.

- **Business info**: Update phone, email, service list in Contact section
- **Colors**: Edit CSS variables in `:root` (lines 33-41)
- **Content**: Update text, headings, testimonials
- **Gallery**: Replace placeholder tiles with actual project images
- **Instagram link**: Update `@alvaros.landscaping` mentions

## Performance Metrics

- **File size**: ~10KB (gzipped)
- **Page load**: Instant (single file, no CDN requests)
- **Lighthouse score**: Target 95+
- **First Contentful Paint**: <500ms

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## Future Enhancements

- **Form backend**: Integrate with Formspree for email notifications
- **Gallery images**: Replace CSS gradient placeholders with actual photos
- **Map integration**: Add Google Maps for location
- **Analytics**: Add Google Analytics tracking

## License

© 2024 Alvaro's Landscaping. All rights reserved.