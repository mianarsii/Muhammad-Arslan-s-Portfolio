# Muhammad Arslan Sabir - Portfolio Website

A clean, responsive portfolio website built from scratch using HTML, CSS, and JavaScript. This website was rebuilt from a Gamma-generated site to remove watermarks and provide full customization control.

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Functional buttons with smooth scrolling navigation
- **Performance Optimized**: Fast loading with optimized images and fonts
- **Cross-Browser Compatible**: Works across all modern browsers

## Project Structure

```
rebuilt_website/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet with responsive design
├── js/
│   └── script.js       # JavaScript functionality and interactions
├── images/
│   ├── hero_image.jpeg # Hero section image
│   └── Learning-to-Learn-online.jpg # Additional image asset
├── fonts/
│   ├── JTUSjIg1_i6t8kCHKm459Wlhyw.woff2 # Montserrat font
│   └── NGS6v5_NC0k9P9H2TbE.woff2        # Heebo font
└── README.md           # This documentation file
```

## How to Run Locally

### Method 1: Simple HTTP Server (Python)
1. Open terminal/command prompt
2. Navigate to the project directory:
   ```bash
   cd path/to/rebuilt_website
   ```
3. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```
   Or for Python 2:
   ```bash
   python -m SimpleHTTPServer 8000
   ```
4. Open your browser and go to: `http://localhost:8000`

### Method 2: Live Server (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Method 3: Direct File Opening
Simply double-click on `index.html` to open it in your default browser (some features may not work due to CORS restrictions).

## Website Sections

1. **Hero Section**: Introduction with name, title, and call-to-action buttons
2. **Education Section**: Academic background and qualifications
3. **Skills Section**: Technical skills organized by category
4. **Services Section**: Professional services offered
5. **About Me Section**: Personal introduction and professional summary

## Interactive Features

- **Learn More Button**: Smoothly scrolls to the About Me section
- **Hire Me Button**: Smoothly scrolls to the Services section
- **Scroll-to-Top Button**: Appears when scrolling down, returns to top when clicked
- **Hover Effects**: Interactive animations on skill and service cards
- **Typing Animation**: Animated typing effect for the main title
- **Scroll Animations**: Sections fade in as they come into view

## Customization

### Colors
The color scheme is defined in CSS custom properties in `css/style.css`:
```css
:root {
    --primary-color: #3182ce;
    --secondary-color: #2d3748;
    --text-color: #2d3748;
    --light-text: #718096;
    --background-color: #ffffff;
    --accent-color: #4299e1;
}
```

### Fonts
The website uses three font families:
- **Montserrat**: For headings and titles
- **Heebo**: For body text (fallback)
- **Inter**: For general text (Google Fonts fallback)

### Images
Replace images in the `images/` folder with your own:
- `hero_image.jpeg`: Main hero section image
- Add additional images as needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Notes

- Images are optimized for web
- Fonts are self-hosted for better performance
- CSS and JavaScript are minified for production use
- Responsive images adapt to different screen sizes

## Development Notes

- Built with vanilla HTML, CSS, and JavaScript (no frameworks)
- Uses CSS Grid and Flexbox for responsive layouts
- Implements modern CSS features like custom properties
- JavaScript uses modern ES6+ features
- Follows semantic HTML best practices
- Optimized for accessibility

## Credits

- **Developer**: Muhammad Arslan Sabir
- **Fonts**: Montserrat, Heebo (Google Fonts)
- **Images**: Custom portfolio images

## License

This project is for personal portfolio use. Feel free to use as a template for your own portfolio website.

---

For any questions or support, please contact Muhammad Arslan Sabir.

