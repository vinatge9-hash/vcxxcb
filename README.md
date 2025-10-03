# Brew & Beans Coffee Co. - Coffee Shop Website

## Overview
This is a modern, responsive website for Brew & Beans Coffee Co., a cozy neighborhood coffee shop offering freshly roasted beans, pastries, and a welcoming space for customers to work, meet, or relax. The design emphasizes warmth, readability, and a friendly, artisanal atmosphere suitable for a coffee-focused brand.

## Pages Included

- Home (index.html)
  - Hero section with large background image and strong value proposition
  - Quick highlights of roasts, pastries, and ambiance
  - Menu preview and call-to-action to view full menu
- About (about.html)
  - Our story, sourcing, roasting philosophy, and community emphasis
  - Photos of the team and cafe environment
- Menu (menu.html)
  - Full menu sections with beverages and pastries
  - Item cards with descriptions and pricing
  - Visuals for highlighted items
- Contact (contact.html)
  - Contact form
  - Location, hours, and contact details

## Setup Instructions

1. View Locally:
   - Save all files in a single folder
   - Open index.html in a web browser
   - Navigate using the top navigation bar

2. Deploy Online:
   - Upload all HTML files to your web host
   - Ensure all files are in the same directory
   - Set index.html as your default page

## Customization Guide

### Images
- Replace all image placeholders (https://images.unsplash.com/photo-1630749848606-ae12a27a1de0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw3fHwuLi58ZW58MHwwfHx8MTc1OTQyNzU1OXww&ixlib=rb-4.1.0&q=80&w=1080) with actual images
- Use high-quality images (1200px+ wide recommended)
- Optimize images for web usage

### Colors
- Primary color (brand tint), secondary color (accents), and background color are defined per category. For this coffee shop, primary is amber/brown tones; update as needed in the Tailwind utility classes and inline gradient styles where used.

### Fonts
- The coffee shop design uses Montserrat for headings and Open Sans for body text.
- Google Fonts are imported in a style block in each HTML file.

### Content
- Update business name, address, phone, and email
- Replace placeholder quotes with real testimonials if needed
- Update hours and services as required

### Accessibility
- Ensure all images have descriptive alt attributes
- Maintain semantic HTML structure (header, nav, main, section, article, footer)
- Provide keyboard focus indicators and proper ARIA attributes where applicable

## Browser Compatibility
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome on Android)

## Dependencies
- Tailwind CSS CDN for utilities
- Font Awesome CDN for icons
- Google Fonts for typography (Montserrat, Open Sans)

## Content Structure
- index.html: Home page with hero, highlights, and menu teaser
- about.html: Brand story and values
- menu.html: Full coffee and pastry menu with images and prices
- contact.html: Contact form and cafe information

## Validation & Quality
- All pages use Tailwind utilities for styling (no external CSS files)
- Background hero uses gradient overlay with a descriptive image placeholder
- One H1 per page; proper heading order with H2/H3 as needed
- Internal links point to existing pages
- Interactive elements have hover and focus states with transition-all duration-300

## Support & Maintenance
- Regularly update menu items, hours, and events
- Test on multiple devices and browsers
- Keep dependencies up to date

**Last Updated:** 2025-10-03