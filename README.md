# A Child's Place - Daycare Website

Welcome to the A Child's Place daycare website! This is a modern, responsive website designed specifically for childcare centers and daycares.

## Features

### 🎨 Design
- Modern, warm, and child-friendly design
- Colorful gradient themes perfect for daycare branding
- Fully responsive design that works on all devices
- Beautiful animations and interactive elements
- Professional typography using Google Fonts (Poppins & Comic Neue)

### 📱 Responsive Design
- Mobile-first approach
- Tablet and desktop optimized layouts
- Touch-friendly navigation and buttons
- Flexible grid system using Bootstrap 5

### 🚀 Functionality
- Smooth scrolling navigation
- Interactive contact form with validation
- Animated elements and loading effects
- Scroll-to-top functionality
- Form submission handling (demo mode)

### 📋 Sections Included
1. **Header** - Navigation with smooth scrolling
2. **Hero Section** - Welcoming introduction with animated elements
3. **About Us** - Information about the daycare with statistics
4. **Services** - Core programs (Infant Care, Toddler Care, Preschool, etc.)
5. **Benefits** - Why choose this daycare
6. **Contact** - Contact form and information
7. **Footer** - Links and social media placeholders

## Getting Started

### Quick Setup
1. Extract the zip file to your desired location
2. Open `index.html` in your web browser
3. The website is ready to use!

### For Web Hosting
1. Upload all files to your web server
2. Ensure the folder structure is maintained:
   ```
   /
   ├── index.html
   ├── css/
   │   └── styles.css
   ├── js/
   │   └── scripts.js
   └── images/ (for future image uploads)
   ```
3. Access your website through your domain

## Customization

### Colors
The website uses CSS custom properties (variables) for easy color customization. Edit the `:root` section in `css/styles.css`:

```css
:root {
    --primary-color: #FF6B6B;      /* Main brand color */
    --secondary-color: #4ECDC4;    /* Secondary brand color */
    --accent-color: #45B7D1;       /* Accent color */
    --success-color: #96CEB4;      /* Success/positive color */
    --warning-color: #FFEAA7;      /* Warning/attention color */
}
```

### Content
- Edit `index.html` to update text content, contact information, and services
- Replace placeholder contact details with your actual information
- Update social media links in the footer

### Images
- Add your daycare photos to the `images/` folder
- Update image references in the HTML
- Recommended image sizes:
  - Hero section: 1200x800px
  - Service icons: 200x200px
  - About section: 600x400px

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+ (with graceful degradation)

## Dependencies
All external dependencies are loaded via CDN:
- Bootstrap 5.3.2 (CSS Framework)
- Font Awesome 6.0.0 (Icons)
- Google Fonts (Typography)

## Contact Form
The contact form includes:
- Real-time validation
- Required field checking
- Email format validation
- Phone number validation
- Success/error messaging
- Demo submission (logs to browser console)

To connect to a real backend:
1. Modify the `submitForm()` function in `js/scripts.js`
2. Replace the setTimeout simulation with actual API calls
3. Update form action and method as needed

## File Structure
```
daycare_website/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All CSS styles
├── js/
│   └── scripts.js      # JavaScript functionality
├── images/             # Image assets (empty, ready for your photos)
└── README.md           # This file
```

## Performance Features
- Optimized CSS with efficient selectors
- Debounced scroll events for better performance
- Lazy loading animations
- Minimal JavaScript footprint
- CDN-hosted external libraries

## Accessibility
- Semantic HTML structure
- Proper heading hierarchy
- Alt text placeholders for images
- Keyboard navigation support
- Screen reader friendly
- High contrast color ratios

## SEO Ready
- Proper meta tags
- Semantic HTML structure
- Fast loading times
- Mobile-friendly design
- Clean, crawlable code

## Support
This website template is designed to be user-friendly and easy to maintain. For advanced customizations, basic HTML, CSS, and JavaScript knowledge is recommended.

## License
This template is provided as-is for educational and commercial use. Feel free to modify and customize according to your needs.

---

**A Child's Place** - Where Every Child's Journey Begins with Love, Care, and Wonder
