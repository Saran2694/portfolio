# Sri Saran Loganathan - Developer Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases professional skills, projects, and contact information in a clean and engaging design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: CSS animations and JavaScript interactions
- **SEO Optimized**: Proper meta tags and semantic HTML

## Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Featured projects with descriptions
5. **Contact Section**: Contact information and contact form
6. **Footer**: Social links and copyright information

## Files Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Download/Clone** the portfolio files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting platform

## Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Contact Information
```html
<!-- Update in the contact section -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h4>Email</h4>
        <p>srisaran2694@gmail.com</p>  <!-- Update this -->
    </div>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <div>
        <h4>Phone</h4>
        <p>+91-7418570190</p>  <!-- Update this -->
    </div>
</div>
<div class="contact-item">
    <i class="fab fa-linkedin"></i>
    <div>
        <h4>LinkedIn</h4>
        <p>in/Sri Saran-Developer</p>  <!-- Update this -->
    </div>
</div>
```

#### Hero Section
```html
<!-- Update in the hero section -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">Your Title</h2>
<p class="hero-description">
    Your personal description here.
</p>
```

### Skills

Update the skills section in `index.html`:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add or remove skill items as needed -->
    </div>
</div>
```

### Projects

Update the projects section with your own projects:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-shopping-cart"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description here.</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="your-live-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### Statistics

Update the statistics in the About section:

```html
<div class="about-stats">
    <div class="stat">
        <h3>2+</h3>  <!-- Update number -->
        <p>Years Experience</p>  <!-- Update text -->
    </div>
    <!-- Add more stats as needed -->
</div>
```

## Styling Customization

### Colors

The main color scheme can be modified in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #fbbf24;
--accent-color: #667eea;

/* Background colors */
--bg-primary: #ffffff;
--bg-secondary: #f8fafc;
```

### Fonts

The portfolio uses Google Fonts (Poppins). To change fonts:

1. Update the Google Fonts link in `index.html`
2. Change the font-family in `styles.css`

```css
body {
    font-family: 'Your-Font-Name', sans-serif;
}
```

## Adding Your Photo

To add your profile photo:

1. **Replace** the placeholder in the hero section:
```html
<div class="hero-image">
    <img src="path/to/your/photo.jpg" alt="Your Name" class="profile-image">
</div>
```

2. **Add CSS** for the image in `styles.css`:
```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid rgba(255, 255, 255, 0.2);
}
```

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Upload all portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your portfolio will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop your portfolio folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. You can customize the domain name

### Vercel

1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Vercel will automatically deploy your site
3. Updates are deployed automatically when you push to GitHub

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

The portfolio is optimized for:
- Fast loading times
- Mobile performance
- SEO best practices
- Accessibility standards

## License

This portfolio template is free to use for personal and commercial projects.

## Support

If you need help customizing your portfolio, feel free to reach out!

---

**Created by**: Sri Saran Loganathan  
**Email**: srisaran2694@gmail.com  
**Phone**: +91-7418570190 