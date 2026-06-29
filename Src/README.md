# SRFusion Technologies Premium Website

A modern, premium multi-page corporate website for SRFusion Technologies featuring a professional design with the company's signature blue and orange color scheme.

## Features

- **Multi-Page Structure**: Separate pages for Home, About, Services, and Contact
- **Premium Design**: Modern, professional UI with advanced animations and transitions
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**:
  - Smooth page navigation with active state indicators
  - Mobile hamburger menu with smooth transitions
  - Scroll-triggered fade-in animations
  - Counter animations for statistics
  - FAQ accordion functionality
  - Interactive contact form with validation
  - Hover effects on cards and buttons

## Pages

### Home Page (`home.html`)
- Hero section with animated logo and statistics
- Trusted by section
- Services preview with featured cards
- Why choose us section with achievements
- Client testimonials
- Call-to-action section

### About Page (`about.html`)
- Company story with timeline
- Mission, vision, and values
- Team member profiles
- Statistics section with animated counters
- Company culture and values

### Services Page (`services.html`)
- Comprehensive service offerings (6 services)
- Detailed service descriptions with features
- Development process (6 steps)
- Technology stack categories
- Flexible pricing plans (3 tiers)

### Contact Page (`contact.html`)
- Enhanced contact form with multiple fields
- Contact information with icons
- Social media links
- Map placeholder section
- FAQ accordion with 6 questions

## Color Scheme

- **Primary Blue**: #0066CC
- **Primary Orange**: #FF6B00
- **Dark Blue**: #1a237e
- **Light Blue**: #e3f2fd

## File Structure

```
srfusion-website/
├── home.html       # Home page
├── about.html      # About page
├── services.html   # Services page
├── contact.html    # Contact page
├── styles.css      # All styling and responsive design
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## How to Use

1. **Extract the zip file** to your desired location
2. **Open home.html** in any modern web browser to start
3. **Navigate** between pages using the navigation menu
4. **No build process required** - this is a static website that runs directly in the browser

## Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-blue: #0066CC;
    --primary-orange: #FF6B00;
    --dark-blue: #1a237e;
    --light-blue: #e3f2fd;
    /* ... other variables */
}
```

### Updating Content
- **Text content**: Edit directly in the respective HTML files
- **Services**: Modify service cards in `services.html`
- **Team members**: Update team section in `about.html`
- **Contact information**: Update contact details in `contact.html`
- **Navigation**: Update nav menu links in all HTML files

### Adding Images
To add your company logo or team photos:
1. Place images in the project folder
2. Reference them in HTML using `<img>` tags
3. Update CSS background images where needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

This website can be deployed to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any traditional web server

Simply upload all files to your hosting service, and the website will work immediately.

## Contact Form

The contact form currently shows a success message when submitted. To make it functional:
1. Connect it to a backend service (Formspree, Netlify Forms, Formsubmit)
2. Or integrate with your own server-side processing
3. Update the form submission handler in `script.js`

## License

This website is custom-built for SRFusion Technologies.

---

**SRFusion Technologies - Innovate • Build • Transform**
