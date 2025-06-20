# CV Portfolio - Nguyễn Duy Minh

A modern, responsive CV portfolio website showcasing skills, projects, and professional experience.

## 🚀 Features

- **Modern Design**: Clean, professional interface with smooth animations
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Dark/Light Theme**: Toggle between themes with floating action button
- **Interactive Elements**: 
  - Animated skill bars
  - Smooth scrolling navigation
  - Particle background effects
  - Loading screen
  - Scroll progress indicator
- **Accessibility**: 
  - Keyboard navigation support
  - ARIA labels
  - Screen reader friendly
- **Performance**: 
  - Optimized animations
  - Lazy loading
  - Efficient event handling

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: 
  - CSS Grid & Flexbox
  - CSS Variables
  - Animations & Transitions
  - Media Queries
- **JavaScript (ES6+)**: 
  - Classes & Modules
  - Intersection Observer API
  - Event handling
  - DOM manipulation

## 📁 Project Structure

```
WebGiuaKy/
├── index.html          # Main HTML file
├── css/
│   └── main.css        # Main stylesheet
├── js/
│   └── main.js         # Main JavaScript file
├── images/             # Image assets
│   ├── logo.png
│   ├── facebook.png
│   ├── github.png
│   ├── linkedin.svg
│   ├── mail.png
│   └── phone.png
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation

1. Clone or download the project files
2. Open `index.html` in your web browser
3. For development, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 🎨 Customization

### Colors & Theme

Edit CSS variables in `css/main.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #3498db;
    /* ... more variables */
}
```

### Content

Update the content in `index.html`:
- Personal information
- Skills and proficiency levels
- Projects and descriptions
- Contact links

### Skills

Modify skill levels by changing the `data-width` attribute:

```html
<div class="skill-progress" data-width="85%"></div>
```

## 📱 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎯 Features in Detail

### Navigation
- Smooth scrolling to sections
- Active section highlighting
- Keyboard navigation (Arrow keys, Page Up/Down, Home/End)
- Mobile swipe gestures

### Animations
- Fade-in effects for sections
- Staggered card animations
- Skill bar progress animations
- Particle background effects

### Interactive Elements
- Floating Action Button (FAB) with menu
- Theme toggle (Dark/Light)
- Print functionality
- Scroll to top

### Performance
- Debounced scroll events
- Throttled animations
- Efficient DOM queries
- Optimized CSS animations

## 🔧 Development

### Code Style
- Consistent indentation (2 spaces)
- Descriptive variable names
- Comprehensive comments
- Modular function structure

### Best Practices
- Semantic HTML
- CSS custom properties
- Progressive enhancement
- Accessibility first approach

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Nguyễn Duy Minh**
- GitHub: [@Minhkoi0103](https://github.com/Minhkoi0103)
- LinkedIn: [minhkoi2503](https://www.linkedin.com/in/minhkoi2503)
- Email: nguyenduyminhnt2503@email.com

## 🤝 Contributing

1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 Changelog

### Version 2.0
- Complete code refactoring
- Improved file structure
- Enhanced accessibility
- Better performance optimization
- Modern JavaScript implementation

### Version 1.0
- Initial release
- Basic portfolio functionality
- Responsive design
- Core animations

---

**Note**: This portfolio is designed to showcase web development skills and professional experience. Feel free to customize it for your own use!