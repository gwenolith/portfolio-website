# 🌌 Galaxy Portfolio Website

A stunning, responsive portfolio website with a beautiful galaxy color scheme and modern animations. Built with HTML, CSS, and JavaScript.

## ✨ Features

### 🎨 Design
- **Galaxy Color Scheme**: Deep purples, blues, and cosmic gradients
- **Animated Background**: Twinkling stars and floating clouds
- **Glass Morphism**: Modern glass-like cards with backdrop blur
- **Responsive Design**: Works perfectly on all devices

### 🚀 Animations
- **Smooth Scrolling**: Seamless navigation between sections
- **Intersection Observer**: Elements animate as they come into view
- **Hover Effects**: Interactive project cards and skill items
- **Typing Animation**: Hero title types out on page load
- **Floating Elements**: Particles and cards with gentle floating motion

### 📱 Sections
1. **Hero Section**: Eye-catching introduction with animated avatar
2. **About Section**: Personal story with statistics and journey timeline
3. **Projects Section**: Showcase of featured projects with hover effects
4. **Skills Section**: Organized by category (Frontend, Backend, Tools)
5. **Contact Section**: Contact form and social media links

### 🛠️ Technologies Used
- **HTML5**: Semantic structure
- **CSS3**: Modern styling with gradients and animations
- **JavaScript**: Interactive functionality and smooth animations
- **Font Awesome**: Icons for skills and social media
- **Google Fonts**: Inter font family for clean typography

## 🎯 Key Features

### Responsive Navigation
- Fixed navigation bar with glass morphism effect
- Mobile hamburger menu
- Smooth scrolling to sections
- Active state indicators

### Interactive Elements
- Project cards with hover overlays
- Skill items with hover animations
- Contact form with validation
- Social media links with hover effects

### Performance Optimized
- Throttled scroll events
- Efficient animations using CSS transforms
- Lazy loading of animations
- Optimized for 60fps

## 🚀 Getting Started

1. **Clone or Download** the files to your local machine
2. **Open `index.html`** in your web browser
3. **Customize** the content to match your personal information
4. **Deploy** to your preferred hosting service

## 📝 Customization

### Personal Information
Edit the following sections in `index.html`:
- Name and title in the hero section
- About me description
- Project details and links
- Skills and technologies
- Contact information

### Colors and Styling
Modify the CSS variables in `styles.css`:
```css
/* Main galaxy colors */
--primary: #667eea;
--secondary: #764ba2;
--accent: #f093fb;
--background: #0c0c0c;
```

### Adding Projects
To add new projects, copy this structure:
```html
<div class="project-card">
    <div class="project-image">
        <div class="project-overlay">
            <div class="project-links">
                <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i></a>
                <a href="#" class="project-link"><i class="fab fa-github"></i></a>
            </div>
        </div>
        <div class="project-placeholder">
            <i class="fas fa-rocket"></i>
        </div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Title</h3>
        <p class="project-description">Your project description</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
    </div>
</div>
```

## 🎨 Color Palette

The website uses a beautiful galaxy-inspired color scheme:

- **Primary Purple**: `#667eea`
- **Secondary Purple**: `#764ba2`
- **Accent Pink**: `#f093fb`
- **Dark Background**: `#0c0c0c`
- **Deep Blue**: `#1a1a2e`
- **Navy Blue**: `#16213e`

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🔧 Advanced Customization

### Adding More Animations
You can enable additional animations by uncommenting these lines in `script.js`:
```javascript
// createCursorTrail();
// addInteractiveParticles();
```

### Performance Tuning
For better performance on older devices:
1. Reduce the number of floating particles
2. Disable some animations
3. Use simpler gradients

### SEO Optimization
Add meta tags to the `<head>` section:
```html
<meta name="description" content="Your portfolio description">
<meta name="keywords" content="portfolio, developer, web design">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Your portfolio description">
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them with the community!

## 📞 Support

If you have any questions or need help customizing the portfolio, feel free to reach out!

---

**Made with ❤️ and lots of ☕**

*This portfolio template is designed to showcase your skills and projects in a beautiful, professional way. The galaxy theme creates a unique and memorable experience for visitors while maintaining excellent usability and performance.* 