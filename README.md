# Ashik Kumar - Personal Portfolio Website

A modern, responsive portfolio website built with vanilla HTML5, CSS3, and JavaScript. Features a dark theme with vibrant accent colors, smooth animations, and interactive elements.

## 🎨 Features

- **Responsive Design**: Mobile-first approach, works perfectly on all devices
- **Dark Theme**: Eye-friendly dark background with cyan, red, and yellow accents
- **Smooth Animations**: Scroll-triggered animations, parallax effects, and smooth transitions
- **Interactive Navigation**: Sticky navbar with smooth scrolling and active link indicators
- **Hero Section**: Captivating headline with call-to-action buttons
- **About Me**: Detailed background, education, experience, and animated statistics
- **Skills Showcase**: Categorized skill tags with hover effects
- **Projects Gallery**: 6 featured projects with descriptions, tech stack, and links
- **Contact Form**: Fully functional contact form with validation and notifications
- **Social Links**: Quick access to social media profiles
- **Back to Top**: Smooth scroll button to return to the top
- **Mobile Menu**: Responsive hamburger menu for mobile devices

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete styling with CSS3 animations
├── script.js           # JavaScript for interactivity and animations
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required!

### Installation

1. Clone or download the repository:
   ```bash
   git clone <repository-url>
   cd portfolio
   ```

2. Open `index.html` in your web browser:
   - Double-click the file, or
   - Use a local server for better performance:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js with http-server
     npx http-server
     ```

3. Navigate to `http://localhost:8000` in your browser

## 🎯 Customization Guide

### Update Personal Information

1. **Open `index.html`** and update:
   - Title: `<title>Your Name - Your Title</title>`
   - Logo: `<div class="logo">Your Name</div>`
   - Hero Section: Update headline, subtitle, and description
   - About Section: Update bio, education, experience, and certifications
   - Contact Info: Email, phone, location, and social links

2. **Update Profile Picture**:
   - Replace the placeholder circle (`.profile-placeholder`) with an actual image
   - Add an `<img>` tag instead of the text placeholder

### Customize Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00d4ff;      /* Cyan - change to your accent color */
    --secondary-color: #ff6b6b;    /* Red - change as needed */
    --accent-color: #ffd93d;       /* Yellow - change as needed */
    --dark-bg: #0a0e27;            /* Dark background */
    --darker-bg: #050811;          /* Darker background */
    --text-light: #e0e0e0;         /* Light text */
    --text-muted: #a0a0a0;         /* Muted text */
}
```

### Add Projects

In the "Projects" section of `index.html`, add more `.project-card` elements:

```html
<div class="project-card">
    <div class="project-image">
        <div class="placeholder-image">Project Name</div>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Project description here...</p>
        <div class="project-tags">
            <span class="tag">Technology 1</span>
            <span class="tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourlink" class="link">View Code</a>
            <a href="https://demo-link.com" class="link">Live Demo</a>
        </div>
    </div>
</div>
```

### Update Skills

Modify the skill tags in the "Skills" section:

```html
<div class="skill-category">
    <h3>Your Category</h3>
    <div class="skill-list">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
        <span class="skill-tag">Skill 3</span>
    </div>
</div>
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above (full multi-column layout)
- **Tablet**: 769px - 1199px (adjusted grid layouts)
- **Mobile**: 480px - 768px (single column with hamburger menu)
- **Small Mobile**: Below 480px (optimized for small screens)

## 🎬 JavaScript Features

### 1. Smooth Scrolling
- Click any navigation link to smoothly scroll to that section

### 2. Scroll Animations
- Elements fade in and slide up as they enter the viewport
- Powered by Intersection Observer API

### 3. Animated Counters
- Statistics animate to their target values when visible

### 4. Contact Form
- Email validation
- Success/error notifications
- Form submission handling

### 5. Mobile Menu
- Hamburger menu for mobile devices
- Automatically closes when a link is clicked

### 6. Navbar Effects
- Changes appearance on scroll
- Active link highlighting based on current section

### 7. Parallax Effect
- Hero section creates a subtle parallax effect on scroll

## 🎨 Color Scheme

The portfolio uses a dark theme with accent colors:

| Color | Hex | Usage |
|-------|-----|-------|
| Primary (Cyan) | #00d4ff | Links, buttons, accents |
| Secondary (Red) | #ff6b6b | Gradients, highlights |
| Accent (Yellow) | #ffd93d | Highlights, hover effects |
| Dark BG | #0a0e27 | Main background |
| Darker BG | #050811 | Footer, borders |
| Light Text | #e0e0e0 | Main text color |
| Muted Text | #a0a0a0 | Secondary text |

## 🚀 Deployment

### Deploy to GitHub Pages

1. Create a GitHub repository
2. Push your files:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```
3. Go to Settings → Pages → Select `main` branch
4. Your site will be live at `https://yourusername.github.io/portfolio`

### Deploy to Netlify

1. Drag and drop the folder to [Netlify](https://netlify.com)
2. Or connect your GitHub repository for auto-deploys

### Deploy to Vercel

1. Go to [Vercel](https://vercel.com)
2. Click "New Project" and import your repository
3. Deploy!

## 🔧 Browser Compatibility

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ IE11 (basic functionality, no animations)

## 📊 Performance Tips

1. **Optimize Images**: Compress profile and project images
2. **Lazy Loading**: Add `loading="lazy"` to images
3. **Minify CSS/JS**: For production, minify the files
4. **CDN**: Consider using a CDN for faster delivery
5. **Caching**: Enable browser caching for static assets

## 🤝 Contributing

Feel free to customize and improve this portfolio template!

## 📝 License

This portfolio template is free to use and modify for personal projects.

## 🙏 Credits

Built with vanilla HTML5, CSS3, and JavaScript - no frameworks required!

---

**Last Updated**: May 2024

For questions or improvements, feel free to reach out!
