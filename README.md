# 🌍 Traditional Clothes E-commerce Platform

A comprehensive, responsive e-commerce website showcasing traditional clothing from various cultures worldwide. This project features a modern, dark-themed UI with smooth animations, optimized performance, and an intuitive user experience.

![Website Hero Section](images/h.jpg)

## ✨ Key Features

### 🛍️ Product Showcase
- Browse multiple traditional clothing categories (Bridal, Kurta, Salwar, Frock, and more)
- High-quality product images with zoom functionality
- Detailed product descriptions and specifications
- Related items suggestions

### 🎨 Design & UX
- **Dark Theme**: Eye-friendly dark color scheme with slate-950 background
- **Responsive Layout**: Fully responsive design that works on all devices (desktop, tablet, mobile)
- **Smooth Animations**: Subtle animations for better user engagement
- **Accessibility**: High contrast text and proper heading hierarchy

### ⚡ Performance
- Optimized images for fast loading
- Minified CSS and JavaScript
- Lazy loading for images below the fold
- Efficient asset loading with proper caching

### 🔧 Technical Features
- Built with vanilla HTML5, CSS3, and JavaScript
- Bootstrap 5 for responsive grid and components
- Font Awesome for beautiful icons
- Custom CSS animations and transitions
- Mobile-first approach

## 🚀 Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Styling with CSS Variables for theming
- **JavaScript** - Interactive elements and animations
- **Bootstrap 5** - Responsive framework
- **jQuery** - DOM manipulation and AJAX
- **Font Awesome** - Icons
- **Animate.css** - Pre-built animations

### Development Tools
- Git for version control
- VS Code with Live Server extension
- Chrome DevTools for debugging
- Lighthouse for performance testing

## 📋 Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code, Sublime Text, etc.)
- Git (for version control)
- (Optional) Local web server (e.g., Live Server in VS Code, Python's `http.server`)

## 🛠️ Installation & Setup

### Option 1: Using a Local Web Server (Recommended)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vincent8494/traditional-clothessite.git
   cd traditional-clothessite
   ```

2. **Serve the website**:
   - **VS Code**: Install "Live Server" extension, right-click `index.html` and select "Open with Live Server"
   - **Python**:
     ```bash
     python -m http.server 8000
     ```
     Then open `http://localhost:8000` in your browser

### Option 2: Direct File Opening
Simply open `index.html` directly in your web browser (note: some features might be limited due to CORS policy)

## 🏗️ Project Structure

```
traditional-clothes/
├── css/                    # Stylesheets
│   ├── bootstrap/          # Bootstrap framework files
│   └── styles.css          # Custom styles and theming
├── js/                     # JavaScript files
│   ├── bootstrap/          # Bootstrap JavaScript
│   └── main.js             # Custom JavaScript functionality
├── images/                 # Image assets (optimized)
│   ├── products/           # Product images
│   └── banners/            # Banner/hero images
├── about.html              # About us page
├── bridal.html             # Bridal collection
├── contact.html            # Contact page
├── frock.html              # Frock collection
├── index.html              # Homepage
├── kurta.html              # Kurta collection
├── kurtaset.html           # Kurtaset collection
├── salwar.html             # Salwar collection
├── services.html           # Services page
└── README.md               # This documentation
```

## 🎨 Customization Guide

### Changing Colors
Edit the CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #ff69b4;
    --secondary-color: #ff1493;
    --text-color: #ffffff;
    --light-bg: #020617;      /* slate-950 */
    --dark-bg: #0a1122;
    --card-bg: #1e293b;       /* slate-800 */
    --transition: all 0.3s ease;
}
```

### Adding New Pages
1. Create a new HTML file (e.g., `new-collection.html`)
2. Use the following template structure:
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Page Title | Traditional Clothes</title>
       <!-- Add necessary CSS and JS includes -->
   </head>
   <body>
       <!-- Content goes here -->
   </body>
   </html>
   ```

### Updating Products
1. Add product images to the `images/products/` directory
2. Update the corresponding HTML file with new product cards
3. Ensure all images are optimized for web (recommended: WebP format, max width 1200px)

## 🧪 Testing

### Browser Compatibility
Tested on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile Safari (iOS)
- Chrome for Android

### Performance
- Use Chrome DevTools Lighthouse for performance testing
- Aim for scores above 90 in Performance, Accessibility, Best Practices, and SEO

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

### Development Workflow
1. Create an issue describing the feature/bug
2. Assign yourself if you want to work on it
3. Follow the existing code style and patterns
4. Write clear commit messages
5. Test your changes thoroughly
6. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

- **GitHub Issues**: [Open an issue](https://github.com/vincent8494/traditional-clothessite/issues)
- **Email**: [Your Email]
- **Website**: [Your Website URL]

## 🙏 Acknowledgments

- [Bootstrap](https://getbootstrap.com/) for the responsive framework
- [Font Awesome](https://fontawesome.com/) for the beautiful icons
- [Animate.css](https://animate.style/) for the smooth animations
- All contributors who have helped improve this project

---

*Made with ❤️ for traditional fashion enthusiasts worldwide*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/vincent8494/traditional-clothessite?style=social)](https://github.com/vincent8494/traditional-clothessite/stargazers)
