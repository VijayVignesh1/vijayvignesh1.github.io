# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing skills, projects, and experience.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, typing animations, and scroll effects

## 🚀 Quick Start

### Option 1: Deploy to GitHub Pages (Recommended)

1. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

2. **Access your website:**
   - Your website will be available at: `https://username.github.io`
   - It may take a few minutes to deploy initially

### Option 2: Local Development

1. **Open locally:**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended for testing):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   npx live-server
   ```

## 📝 Customization Guide

### 1. Personal Information

- Edit `index.html` to update the personal information, skills, experiences etc.

### 2. Styling

Customize the design in `style.css`:
- **Colors**: Change the color scheme by updating CSS variables
- **Fonts**: Modify the Google Fonts import and font-family properties
- **Layout**: Adjust spacing, sizes, and responsive breakpoints

### 3. Add Your Photo

Replace the placeholder in the hero section:
1. Add your photo to the project folder
2. Update the `.hero-placeholder` section in `index.html`:
   ```html
    <img src="your-photo.jpg" alt="Username" class="hero-pic">
   ```
3. Add CSS for the photo in `style.css`:
   ```css
    .hero-pic {
        width: 300px;          /* size of circle */
        height: 300px;
        border-radius: 50%;    /* makes it circular */
        overflow: hidden;      /* crop anything outside circle */
        display: flex;
        justify-content: center;
        align-items: center;
        background: #ddd;      /* placeholder background color */
        font-size: 5rem;       /* size of icon inside circle */
        color: #555;           /* icon color */
    }
   ```

## 📁 File Structure

```
vijayvignesh1.github.io/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
|__ images/             # Required images
```

## 🎨 Color Scheme

The website uses a modern color palette:
- **Primary**: `#6366f1` (Indigo)
- **Secondary**: `#fbbf24` (Amber)
- **Background**: `#f8fafc` (Light gray)
- **Text**: `#333333` (Dark gray)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## ⚡ Performance Tips

1. **Optimize Images**: Compress images before adding them
2. **Minify Code**: Consider minifying CSS and JS for production
3. **Use CDN**: External resources (fonts, icons) are loaded from CDN

## 🔧 Advanced Features

### Adding a Contact Form

To add a functional contact form, you can integrate with:
- **Netlify Forms** (if using Netlify)
- **Formspree** (for GitHub Pages)
- **EmailJS** (client-side email service)

### Analytics

Add Google Analytics or other tracking:
```html
<!-- Add before closing </head> tag -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🚀**

Make sure to customize all the placeholder content with your actual information before deploying.