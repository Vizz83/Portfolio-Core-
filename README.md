# Vishwa A H - Portfolio Website

> **A modern, professional portfolio website for Electronics & Communication Engineering professional specializing in Embedded Systems**

## 🚀 Quick Start

1. Open `index.html` in your web browser
2. Navigate through sections using the top navigation or scroll
3. All your resume information is already integrated!

## 📁 Project Structure

```
portfolio-vishwa/
├── index.html          # Main HTML file with all content
├── style.css           # Comprehensive styling with dark theme
├── script.js           # Interactive JavaScript features
└── README.md           # This file
```

## ✨ Features

- **Modern Dark Theme** with gradient accents and glassmorphism effects
- **Fully Responsive** design for desktop, tablet, and mobile
- **Smooth Animations** including parallax backgrounds and scroll effects
- **Interactive Elements** with hover effects and transitions
- **SEO Optimized** with proper meta tags and semantic HTML
- **Fast Loading** - No external dependencies except Google Fonts

## 📋 Sections

1. **Hero** - Your name, title, and professional photo placeholder
2. **About** - Professional summary with animated stats
3. **Skills** - Technical skills organized by category
4. **Experience** - Work experience with timeline layout
5. **Education** - Academic credentials
6. **Certifications** - Professional certifications with image placeholders
7. **Contact** - Contact information and social links

## 🖼️ Adding Your Images

### Profile Photo
Replace the placeholder in the hero section (line 51-58 in index.html):
```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Vishwa A H" style="width: 100%; border-radius: var(--radius-xl); box-shadow: var(--shadow-lg);">
</div>
```

### Certificate Images
Replace `.cert-image-placeholder` divs with actual images:
```html
<img src="certificate.jpg" alt="Certificate Name" style="width: 100%; height: 100%; object-fit: cover;">
```

## 🔗 Update Social Links

Edit the GitHub and LinkedIn URLs in index.html (lines 280-296):
```html
<a href="https://github.com/yourusername" class="social-link" id="github-link">
<a href="https://linkedin.com/in/yourusername" class="social-link" id="linkedin-link">
```

## 🎨 Customization

All colors and styling can be customized through CSS variables in `style.css`:
```css
:root {
    --primary: #6366f1;
    --secondary: #ec4899;
    --accent: #8b5cf6;
    /* ... more variables */
}
```

## 🌐 Deployment

### GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch
5. Your portfolio will be live at `https://yourusername.github.io/repository-name`

### Netlify (Free)
1. Drag and drop the folder to netlify.com
2. Get instant deployment
3. Custom domain support available

### Vercel (Free)
1. Import your GitHub repository
2. Deploy with one click
3. Automatic HTTPS and custom domains

## 📱 Browser Compatibility

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile browsers

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript** - Interactive features
- **Google Fonts** - Inter & Space Grotesk

## 📧 Contact Information

- **Email**: vh9997@srmist.edu.in
- **Phone**: +91 8825593889
- **Location**: Chennai, India

---

**Built with ❤️ for core company job applications**

Good luck with your job search! 🚀
