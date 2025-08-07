# Academic Personal Website

A modern, responsive personal website designed specifically for PhD students and academics. Features a clean, professional design with sections for research, publications, experience, and contact information.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Academic Focus**: Sections specifically designed for research, publications, and academic experience
- **Interactive Elements**: Smooth scrolling, mobile navigation, and hover effects
- **SEO Friendly**: Semantic HTML structure for better search engine optimization
- **Fast Loading**: Optimized CSS and JavaScript for quick page loads

## Sections Included

1. **Hero Section**: Introduction with your name, field, and research focus
2. **About**: Personal background and research areas
3. **Research**: Detailed description of your research interests and methodology
4. **Publications**: List of your academic publications with links
5. **Experience**: Timeline of your academic and professional experience
6. **Contact**: Contact information and social media links

## Quick Start

1. **Download the files** to your local machine
2. **Customize the content** in `index.html` with your information
3. **Test locally** by opening `index.html` in your browser
4. **Deploy** to GitHub Pages or your preferred hosting service

## Customization Guide

### 1. Personal Information

Replace the placeholder text in `index.html` with your actual information:

```html
<!-- Replace "Your Name" with your actual name -->
<h1 class="hero-title">Your Name</h1>
<h2 class="hero-subtitle">PhD Student in [Your Field]</h2>

<!-- Update your research description -->
<p class="hero-description">
    I'm a PhD student at [University Name] researching [Your Research Area]. 
    My work focuses on [Brief description of your research interests].
</p>
```

### 2. About Section

Update the about section with your background:

```html
<p>
    I am a PhD student in [Your Field] at [University Name], working under the supervision of 
    [Supervisor Name]. My research interests lie at the intersection of [Field 1] and [Field 2], 
    with a particular focus on [Specific Research Topic].
</p>
```

### 3. Research Areas

Replace the placeholder research areas with your actual research interests:

```html
<div class="skill-tags">
    <span class="skill-tag">[Research Area 1]</span>
    <span class="skill-tag">[Research Area 2]</span>
    <span class="skill-tag">[Research Area 3]</span>
    <span class="skill-tag">[Research Area 4]</span>
</div>
```

### 4. Publications

Add your actual publications:

```html
<div class="publication-item">
    <div class="publication-year">2024</div>
    <div class="publication-content">
        <h3>Title of Your Latest Publication</h3>
        <p class="publication-authors">Your Name, Co-author Name, Supervisor Name</p>
        <p class="publication-venue">Journal/Conference Name</p>
        <div class="publication-links">
            <a href="[DOI_LINK]" class="publication-link"><i class="fas fa-external-link-alt"></i> DOI</a>
            <a href="[PDF_LINK]" class="publication-link"><i class="fas fa-file-pdf"></i> PDF</a>
        </div>
    </div>
</div>
```

### 5. Experience Timeline

Update the timeline with your academic and professional experience:

```html
<div class="timeline-item">
    <div class="timeline-date">2022 - Present</div>
    <div class="timeline-content">
        <h3>PhD Student</h3>
        <h4>[University Name]</h4>
        <p>Research focus on [Your Research Topic]. Supervised by [Supervisor Name].</p>
    </div>
</div>
```

### 6. Contact Information

Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>your.email@university.edu</p>
    </div>
</div>
```

## Deployment Options

### GitHub Pages (Recommended)

1. **Create a new repository** on GitHub
2. **Upload your files** to the repository
3. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Save

Your site will be available at `https://yourusername.github.io/repositoryname`

### Other Hosting Options

- **Netlify**: Drag and drop your website folder
- **Vercel**: Connect your GitHub repository
- **Traditional Web Hosting**: Upload files via FTP

## Customization Tips

### Colors
The website uses a blue color scheme. To change colors, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #3498db;
    --secondary-color: #2c3e50;
    --accent-color: #667eea;
}
```

### Fonts
The website uses Inter font from Google Fonts. To change fonts:

1. Update the Google Fonts link in `index.html`
2. Change the font-family in `styles.css`

### Adding Sections
To add new sections:

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Update the navigation menu

### Adding a Blog
To add a blog section:

1. Create a new section in `index.html`
2. Add blog post cards with images and excerpts
3. Link to individual blog post pages

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Optimization

The website is optimized for performance with:

- Minimal JavaScript
- Optimized CSS
- Compressed images (when you add them)
- Fast loading times

## Contributing

Feel free to customize this template for your needs. If you make improvements that could benefit others, consider sharing them!

## License

This template is free to use for personal and academic websites.

## Support

If you need help customizing your website, check out:

- [HTML/CSS tutorials](https://developer.mozilla.org/en-US/docs/Web)
- [GitHub Pages documentation](https://pages.github.com/)
- [Font Awesome icons](https://fontawesome.com/icons)

---

**Happy coding!** 🎓 