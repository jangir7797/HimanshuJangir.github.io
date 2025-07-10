# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and is fully customizable.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and smooth transitions
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **SEO Optimized**: Semantic HTML structure
- **Fast Loading**: Optimized for performance

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### 1. Personal Information

Update the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>
<h2 class="hero-subtitle">Your Title</h2>
<p class="hero-description">
    Your personal description here...
</p>
```

#### About Section
```html
<p>
    Update your about text here...
</p>
<div class="about-stats">
    <div class="stat">
        <h3>3+</h3>
        <p>Years Experience</p>
    </div>
    <!-- Update other stats -->
</div>
```

#### Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### 2. Skills Section

Update the skills in `index.html`:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add/remove skills as needed -->
    </div>
</div>
```

### 3. Projects Section

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### 4. Experience Section

Update your work experience:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <p class="timeline-date">2022 - Present</p>
        <p>Job description...</p>
    </div>
</div>
```

### 5. Social Links

Update your social media links:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="your-linkedin-url" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="your-twitter-url" class="social-link">
        <i class="fab fa-twitter"></i>
    </a>
</div>
```

### 6. Colors and Styling

To change the color scheme, update the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #7c3aed;
--accent-color: #fbbf24;

/* Background colors */
--bg-light: #f8fafc;
--bg-dark: #1f2937;
```

## 🚀 Deployment

### Option 1: GitHub Pages (Free)

1. Create a new repository on GitHub
2. Upload your files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch"
5. Choose the main branch
6. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be deployed instantly
4. You can add a custom domain later

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub account
3. Import your repository
4. Deploy with one click

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: ES6+ features and modern APIs
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

If you need help customizing your portfolio or have any questions, feel free to reach out!

---

**Happy coding! 🎉** 