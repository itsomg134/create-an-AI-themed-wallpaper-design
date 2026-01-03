# AI Wallpaper Generator

A dynamic, animated AI-themed wallpaper created with pure HTML, CSS, and JavaScript. Features a futuristic neural network visualization with glowing nodes, particles, and animated gradients.

## Features

- **Neural Network Visualization** - Interconnected nodes with dynamic connections
- **Animated Gradient Text** - Eye-catching AI text with flowing colors
- **Floating Particles** - Subtle particle effects for depth
- **Glowing Orbs** - Ambient lighting effects that move around the screen
- **Responsive Design** - Works on any screen size
- **Pure HTML/CSS/JS** - No dependencies or frameworks required
- **Smooth Animations** - Hardware-accelerated CSS animations

## Demo

![AI Wallpaper Preview](preview.png)

## Getting Started

### Prerequisites

No prerequisites needed! Just a modern web browser.

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/ai-wallpaper-generator.git
```

2. Navigate to the project directory
```bash
cd ai-wallpaper-generator
```

3. Open `index.html` in your browser
```bash
open index.html
```

Or simply double-click the `index.html` file.

## Usage

### As a Wallpaper

1. Open the HTML file in your browser
2. Press F11 for fullscreen mode
3. Take a screenshot or use browser tools to capture the design
4. Set as your desktop wallpaper

### Customization

You can easily customize the colors, animations, and effects by modifying the CSS variables:

```css
/* Change the background gradient */
background: linear-gradient(135deg, #0a0e27 0%, #1a1147 50%, #2d1b69 100%);

/* Modify node colors */
background: rgba(138, 180, 255, 0.6);

/* Adjust text gradient */
background: linear-gradient(45deg, #00f5ff, #7b2ff7, #f72585, #00f5ff);
```

## Project Structure

```
ai-wallpaper-generator/
│
├── index.html          # Main HTML file with embedded CSS and JS
├── README.md           # Project documentation
└── preview.png         # Preview image for README
```

## Customization Options

### Changing Colors

Modify the color values in the CSS section:
- Background gradient colors
- Node colors and glow effects
- Text gradient colors
- Particle colors

### Adjusting Animation Speed

Change animation duration values:
```css
animation: pulse 3s ease-in-out infinite;  /* Node pulsing */
animation: gradientShift 6s ease infinite; /* Text gradient */
animation: float 20s linear infinite;       /* Particles */
```

### Number of Elements

Modify JavaScript constants:
```javascript
const nodeCount = 30;  // Number of network nodes
// Loop count for particles (currently 50)
```

## Browser Compatibility

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## Performance

The wallpaper uses CSS animations and is hardware-accelerated for smooth performance. Typical resource usage:
- CPU: 2-5%
- GPU: Minimal
- RAM: ~50MB

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Ideas for Contributions

- Additional color themes
- Different animation patterns
- Export functionality
- Configuration panel
- Multiple wallpaper styles
- Mobile-optimized version

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by modern AI and neural network visualizations
- Built with pure web technologies for maximum compatibility
- Designed for both aesthetics and performance

## Contact

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app

## Support

If you like this project, please give it a ⭐️!

---

Made with ❤️ and CSS animations
