# Modern Responsive Portfolio Website

A clean, professional, and mobile-friendly personal portfolio website built with semantic HTML5, modern CSS, and vanilla JavaScript. Features elegant design with soft pastels and warm neutral colors, smooth animations, and comprehensive responsive design.

## 🌟 Features

### Design & Layout
- **Modern & Elegant**: Inspired by premium layouts with clean visual hierarchy
- **Responsive Design**: Mobile-first approach that works perfectly on all devices
- **Color Palette**: Soft pastels, warm neutrals, and elegant deep shades (sage green, warm beige, lavender, slate)
- **Typography**: Beautiful font pairing with Inter and Playfair Display

### Sections
1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Me**: Personal bio with profile image and key highlights
3. **Skills**: Grid-based skills showcase with hover animations
4. **Projects**: Featured project gallery with overlay effects
5. **Contact**: Contact form and social media links
6. **Navigation**: Sticky navigation with smooth scrolling
7. **Footer**: Clean and minimal footer

### Interactive Features
- **Dark/Light Theme Toggle**: Persistent theme switching with localStorage
- **Smooth Scrolling**: Elegant navigation between sections
- **Mobile Menu**: Responsive hamburger menu for mobile devices
- **Form Handling**: Contact form with validation and user feedback
- **Scroll Animations**: Fade-in effects and parallax elements
- **Button Interactions**: Ripple effects and hover animations

### Technical Features
- **Semantic HTML5**: Accessible and SEO-friendly markup
- **Modern CSS**: Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript**: No external dependencies, clean and efficient code
- **Performance Optimized**: Debounced scroll events, efficient animations
- **Accessibility**: Keyboard navigation, ARIA labels, focus management

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A local web server (optional but recommended)

### Installation
1. Clone or download the repository
2. Open `index.html` in your web browser, or
3. Serve the files using a local web server for best experience

### Using a Local Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📁 Project Structure

```
responsive-portfolio-web/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🎨 Customization

### Changing Colors
The color palette is defined using CSS custom properties in the `:root` selector at the top of `styles.css`. Simply modify these values:

```css
:root {
  --primary-color: #6b7280;      /* Main color */
  --secondary-color: #a7f3d0;    /* Accent color */
  --accent-color: #fbbf24;       /* Highlight color */
  /* ... more colors */
}
```

### Adding Content
1. **Personal Information**: Edit the hero section and about section in `index.html`
2. **Skills**: Modify the skills grid in the skills section
3. **Projects**: Update project cards with your own projects
4. **Contact Information**: Change contact details and social media links

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation links
4. Add any JavaScript functionality needed

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## ⚡ Performance Features

- **Optimized Animations**: RequestAnimationFrame for smooth scrolling
- **Debounced Events**: Efficient scroll and resize handling
- **Lazy Loading**: Intersection Observer for scroll animations
- **Minimal Dependencies**: No external libraries or frameworks

## 🎯 SEO & Accessibility

- Semantic HTML5 elements
- Proper heading hierarchy
- Alt text for images (when added)
- ARIA labels for interactive elements
- Keyboard navigation support
- Focus management
- Screen reader friendly

## 🛠️ Development

### Adding New Animations
Animations are handled through CSS and the Intersection Observer API. To add new animations:

1. Define the animation in CSS
2. Add the element to the observer in `script.js`
3. Use the `.fade-in` class for scroll-triggered animations

### Theme System
The theme system uses CSS custom properties and data attributes:
- Light theme: `data-theme="light"` (default)
- Dark theme: `data-theme="dark"`

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements that could benefit others, pull requests are welcome!

## 📧 Contact

For questions or suggestions about this portfolio template, feel free to reach out!

---

**Built with ❤️ and lots of ☕**