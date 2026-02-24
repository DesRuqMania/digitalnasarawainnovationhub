# Digital Nasarawa Innovation Hub - Website

A modern, responsive HTML and CSS website for the Digital Nasarawa Innovation Hub.

## 📁 File Structure

```
dni-hub-html/
├── index.html          # Main homepage
├── team.html           # Team members page
├── css/
│   └── styles.css      # All styling
├── js/                 # JavaScript directory (for future enhancements)
├── images/             # Images directory (for future use)
└── README.md           # This file
```

## 🚀 Getting Started

### Option 1: Open Directly in Browser
Simply open `index.html` in your web browser. The website is fully self-contained and requires no server setup.

### Option 2: Run with a Local Server
For better performance and to avoid CORS issues with external resources:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npx http-server
```

**Using PHP:**
```bash
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📄 Pages

### index.html
The main landing page featuring:
- Navigation bar with links to all sections
- Hero section with brand messaging
- About section with hub information
- Previous work showcase (YouTube content)
- Team preview section
- Call-to-action section
- Footer with contact information

### team.html
Detailed team members page featuring:
- Full team member profiles
- Roles and responsibilities
- Contact information
- Team values section
- Call-to-action for joining the team

## 🎨 Design Features

- **Modern Design**: Clean, professional layout with African heritage aesthetics
- **Responsive**: Fully responsive design that works on mobile, tablet, and desktop
- **Color Scheme**: 
  - Primary: Forest Green (#1B5E20)
  - Secondary: Warm Gold (#D4A574)
  - Accent: Vibrant Teal (#00897B)
- **Typography**: Professional font pairing with Poppins and Inter
- **Animations**: Smooth transitions and fade-in effects
- **Accessibility**: Semantic HTML and proper contrast ratios

## 📱 Responsive Breakpoints

- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

## 🔗 External Resources

The website uses external images hosted on CDN:
- Hero image
- About section image
- Work section background images

All images are loaded from secure CDN URLs and will display correctly as long as internet connection is available.

## 📞 Contact Information

- **Address**: Opposite Fire Service Lafia Nasarawa State, Nigeria
- **Email**: dnihubs@gmail.com
- **Phone**: +2348069501129
- **YouTube**: https://www.youtube.com/@digitalnasarawainnovationh6282

## 🛠️ Customization

### Changing Colors
Edit the CSS variables in `css/styles.css`:
```css
:root {
  --primary: #1B5E20;
  --secondary: #D4A574;
  --accent: #00897B;
  /* ... other colors ... */
}
```

### Updating Contact Information
Find and replace contact details in:
- `index.html` (footer section)
- `team.html` (footer section)

### Adding New Sections
Follow the existing pattern in `index.html` and add corresponding CSS classes in `css/styles.css`.

## 📦 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

© 2026 Digital Nasarawa Innovation Hub. All rights reserved.

## 🤝 Support

For questions or issues, please contact:
- Email: dnihubs@gmail.com
- Phone: +2348069501129

---

**Last Updated**: February 24, 2026
