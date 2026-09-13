# Project RAE SA Website 🐾

**Rescue. Animals. Everywhere.**

A professional, warm, and welcoming website for Project RAE SA, a South African animal welfare initiative.

## Features

- **Responsive Design** - Works beautifully on desktop, tablet, and mobile devices
- **Easy to Update** - Simple HTML/CSS structure with no external dependencies
- **Professional Color Scheme** - Forest green, cream, and gold throughout
- **Smooth Navigation** - Sticky header and smooth scrolling between sections
- **Accessible** - Clean, semantic HTML structure

## Pages Included

1. **Home** - Hero section with tagline and call-to-action buttons
2. **About Us** - Mission statement, vision, and core values
3. **What We Do** - Service offerings with icons and descriptions
4. **Report an Animal** - Contact methods for animal emergencies
5. **Get Involved** - Ways to volunteer, donate, foster, and spread awareness
6. **Contact** - Direct contact information and social media links

## Files

- `index.html` - Main website structure
- `styles.css` - All styling, colors, and responsive design
- `script.js` - Smooth scrolling and interactive features
- `README.md` - This file

## Color Palette

- **Forest Green**: `#2d5016` - Primary color for headings and accents
- **Light Green**: `#4a7c2f` - Accent and hover states
- **Cream**: `#f5f1e8` - Background and card backgrounds
- **Gold**: `#d4a574` - Highlights, buttons, and borders

## How to Update

### Changing Content
1. Open `index.html` in a text editor
2. Find the section you want to update (marked with `<!-- Section Name -->`)
3. Edit the text, keeping HTML tags intact
4. Save and refresh in your browser

### Adding Contact Information
Update these locations in `index.html`:
- Email links: Search for `projectraesa@outlook.com`
- Social media: Search for `@projectraesa`

### Customizing Colors
Edit the CSS variables in `styles.css` under `:root`:
```css
--forest-green: #2d5016;
--cream: #f5f1e8;
--gold: #d4a574;
```

## Quick Start

1. Place these three files in a folder
2. Open `index.html` in a web browser
3. The website is ready to use!

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Logo

The paw print emoji (🐾) is used throughout the site as the logo. To replace with a custom logo:

1. Save your logo image (e.g., `logo.png`) in the same folder
2. In `index.html`, find `.logo` and `.hero-logo` elements
3. Replace the emoji with: `<img src="logo.png" alt="Project RAE SA Logo">`
4. Add to `styles.css`:
   ```css
   .logo img,
   .hero-logo img {
       height: 40px; /* or desired size */
       width: auto;
   }
   ```

## Contact

**Email**: projectraesa@outlook.com  
**Social Media**: @projectraesa

---

**Project RAE SA** - Building a future for animal welfare in South Africa
