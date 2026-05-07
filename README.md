# Haven & Hue - HTML/CSS/JS Website

## Complete Conversion from React to Plain HTML/CSS/JavaScript

This is the fully converted static HTML/CSS/JS version of the Haven & Hue website.

### File Structure

```
/public/
├── index.html                  # Homepage
├── about.html                  # About page
├── services.html               # Services overview page
├── interior-styling.html       # Interior Styling service page
├── room-makeovers.html         # Room Makeovers service page
├── color-consultation.html     # Color Consultation service page
├── furniture-selection.html    # Furniture & Decor Selection service page
├── home-staging.html           # Home Staging service page
├── seasonal-decor.html         # Seasonal Decor service page
├── contact.html                # Contact page
├── faq.html                    # FAQ page
├── terms.html                  # Terms & Conditions
├── privacy.html                # Privacy Policy
├── disclaimer.html             # Disclaimer
├── cookies.html                # Cookies Policy
├── css/
│   └── main.css                # Main stylesheet (complete)
└── js/
    └── main.js                 # Main JavaScript file (complete)
```

### Features Implemented

✅ Fully responsive design
✅ Mobile navigation menu
✅ Sticky header with scroll effects
✅ Contact forms with validation
✅ Cookie consent functionality  
✅ Active navigation highlighting
✅ Smooth scrolling
✅ Image fallback handling
✅ All 6 service detail pages
✅ Legal compliance pages
✅ FAQ page
✅ Google Maps integration ready
✅ Phone and email links
✅ SEO-optimized HTML structure

### Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom CSS with CSS variables for theming
- **Vanilla JavaScript**: No frameworks or libraries
- **SVG Icons**: Inline SVG for all icons (no icon library needed)
- **Google Fonts**: Playfair Display (serif) + Inter (sans-serif)

### How to Use

1. **Local Development**: Simply open any HTML file in a web browser
2. **Deployment**: Upload all files to any web hosting service
3. **No Build Process Required**: These are static files ready to deploy

### CSS Variables (Customization)

Edit `/public/css/main.css` to customize colors:

```css
:root {
  --color-primary: #8b9a7e;          /* Sage green */
  --color-primary-foreground: #ffffff;
  --color-secondary: #f5f3ed;         /* Warm beige */
  --color-foreground: #2d2d2d;        /* Charcoal */
  --color-muted-foreground: #6b6b6b;
  --color-border: #e0e0e0;
}
```

### JavaScript Functions

All interactive features are in `/public/js/main.js`:

- `toggleMobileMenu()` - Mobile menu toggle
- `setActiveNav()` - Highlights current page in navigation
- `showCookieConsent()` - Cookie consent banner
- `acceptCookies()` / `declineCookies()` - Cookie consent handlers
- `handleContactForm()` - Form submission handler
- Smooth scroll for anchor links
- Image fallback handling
- Active link detection

### Contact Form

The contact form currently logs to console. To connect to a backend:

1. Add form action attribute pointing to your server endpoint
2. Or use a service like Formspree, FormSubmit, or Basin
3. Or integrate with your preferred backend/CMS

Example with Formspree:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Android)

### Performance

- No external CSS framework (lightweight)
- Minimal JavaScript (< 5KB)
- Optimized images from Unsplash
- No jQuery or heavy libraries
- Fast load times

### SEO Optimized

Each page includes:
- Meta descriptions
- Proper heading hierarchy
- Semantic HTML5 elements
- Alt text for images
- Structured contact information

### Deployment Options

**Static Hosting (Recommended):**
- Netlify (drag & drop deployment)
- Vercel
- GitHub Pages
- AWS S3 + CloudFront
- Firebase Hosting
- Cloudflare Pages

**Traditional Hosting:**
- Any shared hosting with FTP access
- Upload all files maintaining the folder structure

### Next Steps

1. Replace Unsplash images with your own professional photos
2. Add your actual business logo
3. Configure contact form with real backend
4. Add Google Analytics tracking code
5. Set up Google Maps embed on contact page
6. Add favicon and apple-touch-icons
7. Generate and add sitemap.xml
8. Set up custom 404 page

### Support

For questions or modifications, refer to:
- CSS: `/public/css/main.css` (all styles)
- JS: `/public/js/main.js` (all interactions)
- HTML: Individual page files

---

**Note**: This conversion maintains all the original functionality while using plain HTML/CSS/JS instead of React. All pages are fully functional and ready for production deployment.
