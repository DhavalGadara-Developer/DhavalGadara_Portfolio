# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio features a clean design with smooth animations and is fully responsive across all devices.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Seamless navigation between sections
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Scroll to Top**: Convenient button to return to the top
- **Loading Animations**: Typing effect and fade-in animations
- **Counter Animations**: Animated statistics counters

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Showcase of completed projects
5. **Contact Section**: Contact form and social links
6. **Footer**: Copyright information

## Customization Guide

### Personal Information

Edit the following in `index.html`:

1. **Name and Title**:
   ```html
   <title>Portfolio - Your Name</title>
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   <h2 class="hero-subtitle">Your Title</h2>
   ```

2. **About Section**:
   - Update the description paragraphs
   - Modify statistics (years, projects, clients)

3. **Contact Information**:
   - Update email, phone, and location
   - Add your social media links

### Skills

Add or modify skills in the skills section:

```html
<div class="skill-item">
    <i class="fab fa-your-icon"></i>
    <span>Skill Name</span>
</div>
```

### Projects

Add your projects by duplicating the project card structure:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-project-icon"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="btn btn-small">Live Demo</a>
            <a href="#" class="btn btn-small btn-outline">GitHub</a>
        </div>
    </div>
</div>
```

### Colors and Styling

The main color scheme is defined in `style.css`:

- Primary Blue: `#2563eb`
- Secondary Blue: `#1d4ed8`
- Accent Yellow: `#fbbf24`
- Text Dark: `#1f2937`
- Text Light: `#6b7280`

To change colors, update the CSS variables or color values throughout the file.

### Fonts

The website uses Google Fonts (Poppins). To change fonts:

1. Update the Google Fonts link in `index.html`
2. Modify the font-family in `style.css`

## How to Use

1. **Download/Clone** the files to your local machine
2. **Customize** the content as described above
3. **Test** the website locally by opening `index.html` in a browser
4. **Deploy** to your preferred hosting service (GitHub Pages, Netlify, Vercel, etc.)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for better performance
- Responsive images and icons
- Smooth animations using CSS transforms
- Intersection Observer for efficient scroll animations

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- High contrast color scheme
- Responsive design for all screen sizes

## Future Enhancements

Potential improvements you can add:

- Dark mode toggle
- Blog section
- Testimonials section
- Downloadable resume
- Portfolio filters
- Image gallery
- Blog integration
- Analytics tracking

## Credits

- **Fonts**: Google Fonts (Poppins)
- **Icons**: Font Awesome
- **Design Inspiration**: Modern portfolio trends

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Happy Coding! 🚀** 