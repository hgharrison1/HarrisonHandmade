# Harrison Handmade - Leather Working Portfolio Website

A professional leather-working portfolio website showcasing handcrafted leather goods including wallets, belts, and custom projects.

## Features

- **Responsive Design**: Fully responsive website that works on desktop, tablet, and mobile devices
- **Multiple Collections**: Dedicated pages for wallets, belts, and small projects
- **Professional Layout**: Clean, elegant design that reflects craftsmanship
- **Contact Form**: Get in touch for custom orders and inquiries
- **Image Gallery**: Showcase products with descriptions
- **About Section**: Share your story and commitment to quality
- **FAQ**: Answer common customer questions

## Project Structure

```
HarrisonHandmade/
├── index.html              # Homepage
├── css/
│   └── styles.css          # All styling
├── js/
│   └── script.js           # Interactive features
├── pages/
│   ├── wallets.html        # Wallets collection
│   ├── belts.html          # Belts collection
│   ├── projects.html       # Small projects collection
│   ├── about.html          # About page
│   └── contact.html        # Contact page
└── README.md               # This file
```

## Getting Started

### Option 1: GitHub Pages (Recommended)

1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Select `main` branch as source
4. Your site will be live at `https://hgharrison1.github.io/HarrisonHandmade/`

### Option 2: Local Development

1. Clone the repository
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   # Visit http://localhost:8000
   ```

## Customization

### Adding Your Photos

1. Create an `images/` directory with subdirectories:
   - `images/wallets/`
   - `images/belts/`
   - `images/projects/`
   - `images/gallery/`

2. Update the `.product-image` sections in HTML files to use your images:
   ```html
   <div class="product-image" style="background-image: url('../../images/wallets/wallet1.jpg');"></div>
   ```

### Updating Product Information

- Edit the product details in each collection page (`pages/wallets.html`, `pages/belts.html`, `pages/projects.html`)
- Update titles, descriptions, materials, and dimensions
- Add or remove product items as needed

### Color Customization

Edit the color variables in `css/styles.css`:
```css
:root {
    --primary-color: #8b6f47;      /* Main brown */
    --secondary-color: #d4a574;    /* Tan/gold */
    --text-dark: #2c2c2c;          /* Dark text */
    --text-light: #f5f5f5;         /* Light text */
    --accent: #c9a877;             /* Accent color */
}
```

### Updating Contact Information

Edit `pages/contact.html`:
- Update email address in the `.info-item` and mailto link
- Update phone number
- Update location information
- Customize the contact form as needed

## Content Tips

### Product Descriptions

For each item, include:
- **Title**: Clear, descriptive name
- **Material**: Type of leather and construction details
- **Description**: 2-3 sentences about the piece
- **Specifications**: Dimensions, sizes, or other relevant info

### Photography

- Use high-quality photos of your work
- Show multiple angles when possible
- Ensure consistent lighting
- Include lifestyle shots if available

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimize images before adding them (compress to reduce file size)
- Use modern image formats (WebP, JPEG)
- Keep file sizes under 200KB per image

## SEO Tips

1. Update the `<title>` tags on each page
2. Add meaningful descriptions in `<meta>` tags
3. Use descriptive alt text for images
4. Keep URLs clean and descriptive

## Future Enhancements

Consider adding:
- E-commerce integration for online sales
- Instagram feed integration
- Blog section for leather care tips
- Newsletter signup
- Customer testimonials section
- Photo gallery with lightbox
- Mobile menu hamburger icon

## Hosting

### GitHub Pages (Free)
- Automatic deployment
- Custom domain support
- No database needed

### Other Options
- Netlify
- Vercel
- AWS Amplify
- Traditional web hosting

## Support

For questions or issues, refer to:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Help](https://help.github.com)

## License

This project is open source and available under the MIT License.

---

**Made with ❤️ for Harrison Handmade**
