# VeriTransGH - Verified Global E-Transport

VeriTransGH (VGET) is a digital platform for sustainable transportation solutions across Africa, connecting passengers, drivers, and transport operators through verified infrastructure.

## Overview

VeriTransGH is building the future of electric mobility in Africa. Our platform provides:

- **Passenger App**: Book trips, track vehicles, and pay seamlessly
- **Driver App**: Manage bookings, navigate routes, and optimize earnings
- **Station Management**: DOP app for operators to handle check-ins and operations
- **EV Charging Network**: Growing infrastructure for electric vehicles

## Project Structure

```
veritransgh/
├── css/
│   └── verified.css           # Custom styles
├── images/
│   ├── Pics/                  # Additional images
│   ├── Phone.png
│   ├── Vget buus.png
│   ├── ev_faqs.jpg
│   ├── mission.jpg
│   └── vission.png
├── js/
│   ├── click-scroll.js        # Smooth scroll navigation
│   ├── custom.js              # Custom JavaScript
│   └── jquery.sticky.js       # Sticky navbar plugin
├── index.html                 # Homepage
├── about.html                 # About Us page
├── mission.html               # Our Mission page
├── vision.html                # Our Vision page
├── topics-listing.html        # EV Charge Stations
├── News_letter.html           # Newsletter page
└── README.md                  # This file
```

Note: Bootstrap, Bootstrap Icons, and jQuery are loaded via CDN for optimal performance.

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Main landing page with hero section, features, how it works, FAQs, and contact form |
| `about.html` | Company information, core services, values, and team overview |
| `mission.html` | Detailed mission statement with pillars and impact metrics |
| `vision.html` | Vision for sustainable African transport with roadmap and future technologies |
| `topics-listing.html` | EV charging station locations and information |
| `News_letter.html` | Newsletter subscription and updates |

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with CSS variables
- **Bootstrap 5.2.2**: Responsive framework
- **Bootstrap Icons**: Icon library
- **jQuery 2.2.3**: JavaScript library
- **Google Fonts**: Montserrat and Open Sans

## Features

- Fully responsive design for all devices
- Smooth scroll navigation
- Sticky navigation bar
- Interactive FAQ accordion
- Contact form with validation
- Google Maps integration
- Social media links
- Clean, modern UI design

## Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Green | `#198754` | Buttons, accents, icons |
| Dark Blue | `#0d1b2a` | Headers, dark sections |
| White | `#ffffff` | Backgrounds, text |
| Light Gray | `#f8f9fa` | Section backgrounds |

## Getting Started

1. Clone or download the project files
2. Ensure all files maintain their directory structure
3. Open `index.html` in a web browser
4. For local development, use a local server (e.g., Live Server extension in VS Code)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## Customization

### Changing Colors

Edit the CSS variables in `css/verified.css`:

```css
:root {
    --primary-color: #198754;
    --primary-dark: #146c43;
    --secondary-color: #0d1b2a;
    /* ... other variables */
}
```

### Adding New Pages

1. Copy the structure from an existing page
2. Update the navbar `active` class
3. Update breadcrumbs if applicable
4. Add link to footer navigation

### Updating Content

- Text content is in HTML files
- Images go in the `images/` folder
- Custom styles in `css/verified.css`

## Dependencies

CDN-hosted dependencies:
- Bootstrap 5.2.2 (CSS and JS)
- Bootstrap Icons 1.10.0
- jQuery 3.6.0

Local dependencies:
- jQuery Sticky Plugin (js/jquery.sticky.js)
- Custom scripts (js/custom.js, js/click-scroll.js)

External resources:
- Google Fonts (Montserrat, Open Sans)
- Google Maps Embed API

## Contact

- **Website**: veritransgh.com
- **Email**: info@veritransgh.com
- **Phone**: +233 (0) 24 000 0000
- **Location**: Accra, Ghana

## License

Copyright 2025 VeriTransGH. All rights reserved.

---

Built with purpose for sustainable African mobility.
