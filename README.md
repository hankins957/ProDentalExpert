# ProDentalExpert - Modern Dental Website

A responsive, modern dental practice website featuring patient-centered care information and advanced dental implant technology content. Built with pure HTML, CSS, and JavaScript—no external dependencies or image assets.

## Project Overview

**ProDentalExpert** is a professional dental practice website designed to showcase a patient-centered approach to oral healthcare. The site emphasizes personalized attention, advanced implant technology, and a welcoming environment for patients.

### Key Features

- **Fully Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern CSS-Only Styling**: No images—visual appeal created through CSS gradients, typography, and layout
- **Patient-Centered Content**: Comprehensive article on modern implant technology (1,500+ words)
- **Multiple Pages**: Home, About, Contact, and Privacy Policy
- **Optimized for Deployment**: Compatible with GitHub Pages and Deno Deploy
- **SEO-Friendly**: Proper meta tags and semantic HTML structure
- **Accessibility**: Clean, readable typography and proper heading hierarchy

## File Structure

```
ProDentalExpert/
├── index.html          # Home page with full blog article
├── about.html          # About the practice page
├── contact.html        # Contact form and information
├── privacy.html        # Privacy policy page
├── style.css           # Main stylesheet (all styling)
└── README.md           # This file
```

## Pages Included

### 1. **Home (index.html)**
- Hero section with call-to-action
- Full blog article: "Exploring the Benefits of Modern Implant Technology"
- Article includes the anchor link to Indental Castle Hill (third paragraph)
- Call-to-action section
- Footer with links and information

### 2. **About (about.html)**
- Mission statement
- Practice philosophy and approach
- Team information
- Why choose us section
- Core values

### 3. **Contact (contact.html)**
- Contact form with validation
- Office hours table
- Contact information
- Emergency dental care information
- Multiple contact methods

### 4. **Privacy Policy (privacy.html)**
- Comprehensive privacy policy
- Data collection and usage information
- User rights and choices
- CCPA compliance information
- Cookie and tracking information

## Deployment Instructions

### Option 1: Deploy to GitHub Pages

1. **Create a GitHub Repository**
   - Go to GitHub and create a new repository named `ProDentalExpert`
   - Clone it to your local machine

2. **Add Files**
   - Copy all files from the ProDentalExpert folder to your repository
   - Ensure all files are in the root directory (not in subfolders)

3. **Commit and Push**
   ```bash
   git add .
   git commit -m "Initial commit: ProDentalExpert website"
   git push origin main
   ```

4. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and root directory
   - Click Save

5. **Access Your Site**
   - Your site will be available at: `https://yourusername.github.io/ProDentalExpert`

### Option 2: Deploy to Deno Deploy

1. **Connect GitHub to Deno Deploy**
   - Go to [dash.deno.com](https://dash.deno.com)
   - Sign in with your GitHub account
   - Click "New Project"
   - Select "Deploy from GitHub"

2. **Select Your Repository**
   - Choose the `ProDentalExpert` repository
   - Select the production branch (main)

3. **Configure Deployment**
   - Deno Deploy will automatically detect static files
   - Ensure the root directory is set as the deployment source

4. **Deploy**
   - Click "Deploy" to publish your site
   - Your site will be available at a Deno Deploy URL

5. **Custom Domain (Optional)**
   - Add a custom domain in project settings
   - Update DNS records as instructed

## File Compatibility Notes

### For GitHub Pages
- All files are in the root directory
- CSS references: `style.css` (direct reference)
- HTML references: `index.html`, `about.html`, `contact.html`, `privacy.html`
- No subdirectories or complex paths
- Static files only (no server-side processing needed)

### For Deno Deploy
- All files are static HTML, CSS, and JavaScript
- No backend processing required
- Works with Deno Deploy's static file serving
- No environment variables or secrets needed
- No database connections required

## Important: Single Hyperlink Rule

⚠️ **IMPORTANT**: This website contains **ONLY ONE HYPERLINK** in the entire site:
- **Location**: Third paragraph of the main article (index.html)
- **Anchor Text**: "Indental Castle Hill"
- **URL**: https://www.google.com/maps/place/?cid=14034812201885535339
- **Navigation Links**: The navigation menu and footer links are styled as links but should be treated as internal navigation only

## Customization Guide

### Update Contact Information
Edit the following files to add your actual contact details:
- `contact.html`: Update phone number, email, address
- `about.html`: Update practice information
- `index.html`: Update footer information

### Modify Colors
Edit `style.css` and update the CSS variables in the `:root` selector:
```css
:root {
    --primary-color: #0066cc;
    --secondary-color: #00a8e8;
    --accent-color: #ff6b6b;
    /* ... other colors ... */
}
```

### Update Content
- Edit the HTML files directly to update text content
- Modify article content in `index.html`
- Update service descriptions and information as needed

### Change Typography
Modify font families in `style.css`:
```css
--font-primary: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
--font-secondary: 'Georgia', serif;
```

## Browser Compatibility

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimization

- Pure CSS design (no image assets)
- Minimal JavaScript (form validation only)
- Optimized CSS with CSS variables
- Fast loading times across all devices
- Mobile-first responsive design

## SEO Optimization

- Semantic HTML structure
- Meta descriptions for all pages
- Proper heading hierarchy
- Mobile-responsive design
- Clean, descriptive URLs
- Fast page load times

## Support and Maintenance

### Common Issues

**Styles not loading after deployment:**
- Verify `style.css` is in the root directory
- Check that CSS reference in HTML is `href="style.css"` (not `href="./style.css"`)
- Clear browser cache and hard refresh (Ctrl+Shift+R or Cmd+Shift+R)

**Links not working:**
- Ensure all HTML files are in the root directory
- Verify internal links use correct filenames (e.g., `href="about.html"`)
- Check that file extensions are included in links

**Form not submitting:**
- The contact form includes client-side validation
- For actual form submissions, integrate with a service like Formspree or Netlify Forms
- Update the form action URL in `contact.html`

## License

This website template is provided as-is for ProDentalExpert. All content and design are proprietary to ProDentalExpert.

## Contact

For questions or support regarding this website, please contact:
- Email: info@prodentalexpert.com
- Phone: (555) 123-4567

---

**Version**: 1.0  
**Last Updated**: February 2026  
**Compatibility**: GitHub Pages, Deno Deploy, Netlify, Vercel
