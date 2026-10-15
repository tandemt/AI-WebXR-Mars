# Mars Base WebXR Demo

An interactive WebXR demo showcasing a Mars base environment with terrain, habitat modules, landed rocket, animated UFO, moon, and starfield. Built with Three.js and WebXR API for VR/AR support with keyboard/mouse fallback.

## Features

- **WebXR Support**: Detects VR capabilities and provides immersive VR experience when available, with seamless fallback to keyboard/mouse controls
- **First-Person Controls**: 
  - Mouse/touch: Click and drag to look around
  - Keyboard: WASD/arrow keys for horizontal movement, Space for upward movement, Shift to sprint
  - Mouse wheel: Forward/backward movement
- **Visual Feedback**: Info panel turns green when moving
- **VR Button**: Enter immersive VR mode with one click when supported
- **Responsive Design**: Adapts to window size changes
- **Performance Optimized**: Efficient rendering with frustum culling and level-of-detail considerations

## Scene Elements

- **Mars Terrain**: Procedurally generated with geological variation, craters, and elevated base area
- **Habitat Modules**: Four inflatable dome-style habitats with solar arrays, airlocks, and communication dishes
- **Landed Rocket**: Multi-stage rocket with fins and engines
- **Animated UFO**: Flies in a circular path with pulsing lights and gentle bobbing
- **Moon**: Slowly rotating moon in the distance
- **Starfield**: Background starfield with slow rotation for depth perception
- **Player Avatar**: Astronaut model that follows the camera position

## Technologies Used

- **Three.js r128**: Core 3D rendering library
- **WebXR API**: For VR/AR device support
- **HTML5/CSS3/JavaScript**: Standard web technologies
- **Procedural Generation**: Terrain, rocks, and object placement
- **Animation Loop**: RequestAnimationFrame based with clock-based timing

## File Structure

```
mars-webxr-demo/
├── index.html          # Main demo file (HTML, CSS, JavaScript)
├── PROGRESS.md         # Development progress report
└── README.md           # This file
```

## How to Run

### Local Development

1. Ensure Python 3 is installed
2. Navigate to the project directory:
   ```bash
   cd /path/to/mars-webxr-demo
   ```
3. Start a local HTTP server:
   ```bash
   # Python 3
   python3 -m http.server 3000
   ```
4. Open your browser to:
   - Local machine: `http://localhost:3000`
   - Other devices on your network: Use your machine's IP address (e.g., `http://192.168.x.x:3000`)

### Direct File Access (Not Recommended)

Due to browser security restrictions, opening `index.html` directly from the file system (`file://` protocol) may cause issues with certain features. Always use a local HTTP server for the best experience.

## Deployment

The demo is a static site that can be hosted on any static web hosting service:
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting
- Or any traditional web server

Simply upload the contents of the repository to your hosting provider.

## Browser Support

- Chrome (recommended for best WebXR support)
- Firefox
- Edge
- Safari (limited WebXR support)
- Mobile browsers with WebXR support

## Acknowledgements

- Three.js team for the excellent 3D library
- Mozilla and Google for WebXR API development
- Open-source community for various procedural generation techniques

## License

This project is open source and available for modification and distribution.

---

*Mars Base WebXR Demo - Created with Three.js and WebXR API*