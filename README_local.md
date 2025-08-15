# Fireworks Display

A stunning interactive fireworks simulation built with HTML5 Canvas and JavaScript. Experience realistic fireworks with customizable effects, sound, and responsive controls.

## Features

✨ **Interactive Fireworks**
- Click/tap to launch fireworks from any position
- Multiple shell types with unique visual effects
- Realistic physics simulation with gravity and air resistance

🎨 **Visual Effects**
- 11 different firework shell types (Crysanthemum, Ring, Palm, Strobe, etc.)
- Dynamic sky lighting that responds to firework brightness
- High-quality particle trails and spark effects
- Fullscreen support for immersive viewing

🔊 **Audio Experience**
- Realistic sound effects for launches and bursts
- Volume scaling based on firework size
- Toggle sound on/off

⚙️ **Customization Options**
- Shell type selection (Random, Crackle, Crossette, etc.)
- Shell size control (3" to 16")
- Quality settings (Low, Normal, High)
- Auto-launch mode with intelligent sequences
- Finale mode for intense bursts
- Scale factor adjustment
- Long exposure effect

📱 **Responsive Design**
- Works on desktop, tablet, and mobile devices
- Touch-friendly controls
- Adaptive quality based on device performance
- Mobile-optimized defaults

## Demo

Open `fireworks.html` in your web browser to see the fireworks in action!

## Controls

### Mouse/Touch Controls
- **Click/Tap anywhere**: Launch a firework at that position
- **Settings button (gear icon)**: Open customization menu
- **Play/Pause button**: Toggle animation
- **Sound button**: Toggle audio on/off
- **Bottom edge**: Drag to control simulation speed

### Keyboard Controls
- **P**: Toggle pause
- **O**: Open/close settings menu
- **Esc**: Close settings menu

## Shell Types

| Type | Description |
|------|-------------|
| **Random** | Randomly selects from all available shell types |
| **Crysanthemum** | Classic round burst with optional pistil and streamers |
| **Ring** | Circular pattern with customizable effects |
| **Palm** | Drooping willow-like effect with heavy glitter |
| **Strobe** | Flashing stars with strobe effects |
| **Crossette** | Stars that split into smaller crossettes |
| **Floral** | Multi-colored flower-like burst |
| **Ghost** | Invisible stars that transition to visible colors |
| **Horse Tail** | Long trailing sparks |
| **Crackle** | Crackling sound effects with golden sparks |
| **Falling Leaves** | Leaf-like particles that fall gracefully |
| **Willow** | Long golden trails resembling willow branches |

## Technical Details

### Technologies Used
- **HTML5 Canvas** for rendering
- **JavaScript ES6+** for logic and physics
- **Web Audio API** for sound effects
- **CSS3** for styling and responsive design

### Performance Features
- Object pooling for particle management
- Adaptive quality based on hardware capabilities
- Efficient rendering with blend modes
- Hardware acceleration detection

### Browser Support
- Modern browsers with Canvas and Web Audio support
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Structure

```
fire works/
├── fireworks.html      # Main HTML file
├── fireworks.css       # Styling and responsive design
├── fireworks.js        # Core application logic and physics
└── README.md          # This documentation
```

## Setup & Installation

1. **Clone or download** the project files
2. **Open** `fireworks.html` in a modern web browser
3. **Enjoy** the fireworks display!

No build process or server required - it runs entirely in the browser.

## Configuration Options

### Quality Settings
- **Low**: Reduced particle count, optimized for older devices
- **Normal**: Balanced performance and visual quality
- **High**: Maximum visual fidelity with enhanced effects

### Shell Sizes
- **3"** - Small, quick bursts
- **4"** - Standard size
- **6"** - Medium fireworks
- **8"** - Large displays
- **12"** - Very large shells
- **16"** - Massive finale-style bursts

### Sky Lighting
- **None**: Black background
- **Dim**: Subtle background illumination
- **Normal**: Dynamic sky coloring based on firework brightness

## Advanced Features

### Auto-Launch Sequences
When enabled, the system automatically launches various firework sequences:
- Single random shells
- Coordinated dual launches
- Triple formations
- Pyramid barrages
- Small rapid-fire sequences

### Finale Mode
Activates intense rapid-fire sequences for dramatic finale effects.

### Long Exposure Effect
Simulates camera long-exposure photography, creating extended light trails.

## Performance Tips

1. **Adjust Quality**: Lower quality settings on older devices
2. **Reduce Shell Size**: Smaller shells require less processing
3. **Disable Sky Lighting**: Improves performance on low-end devices
4. **Scale Factor**: Reduce scale for better performance

## Credits

- **Inspired by**: [Caleb Miller](https://cmiller.tech/)
- **Created by**: Y.S (tiktok meowish)
- **External Libraries**: 
  - fscreen (fullscreen API)
  - Stage.js (canvas management)
  - MyMath.js (mathematical utilities)

## License

This project is open source. Feel free to use, modify, and distribute.

---

🎆 **Enjoy the show!** 🎆
