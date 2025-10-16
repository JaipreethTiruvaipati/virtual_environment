# Enchanted Forest 3D Environment

A dynamic 3D virtual forest environment featuring a complete day-night cycle, animated wildlife, and atmospheric effects. Built with Three.js to demonstrate computer graphics concepts including lighting, shading, textures, and real-time rendering.

## 🌟 Features

### Core Graphics Concepts Demonstrated
- **Dynamic Lighting System**: Realistic sun and moon lighting with shadow mapping
- **Day-Night Cycle**: Smooth transitions between day and night with atmospheric changes
- **Procedural Textures**: Programmatically generated ground textures
- **Particle Systems**: Dust motes and starfield for atmospheric depth
- **Real-time Shadows**: High-quality shadow mapping for all objects
- **Camera Controls**: Orbit controls for interactive exploration

### Environment Elements
- **Terrain**: Large forest floor with procedural ground textures
- **Vegetation**: 150+ procedurally generated pine trees with realistic canopies
- **Water Feature**: Reflective river running through the forest
- **Geology**: Scattered rocks and boulders for natural variation
- **Wildlife**: Animated deer and rabbits with AI movement patterns
- **Avian Life**: Flying birds with circular flight patterns
- **Atmospheric Effects**: Fog, dust particles, and dynamic sky colors

### Technical Implementation
- **WebGL Rendering**: Hardware-accelerated 3D graphics
- **Performance Optimization**: Efficient geometry and material usage
- **Responsive Design**: Adapts to different screen sizes
- **Modern JavaScript**: ES6 modules and modern browser APIs

## 🚀 Getting Started

### Prerequisites
- Modern web browser with WebGL support
- No additional software installation required

### Installation & Running
1. Clone or download this repository
2. Open `index.html` in a modern web browser
3. Use mouse/touch controls to explore the environment:
   - **Left click + drag**: Rotate camera around the scene
   - **Right click + drag**: Pan camera
   - **Scroll wheel**: Zoom in/out

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎮 Controls

| Action | Control |
|--------|---------|
| Rotate View | Left Mouse Button + Drag |
| Pan Camera | Right Mouse Button + Drag |
| Zoom | Mouse Wheel / Pinch |
| Reset View | Double-click |

## 🏗️ Architecture

### Core Components
- **Scene Management**: Three.js scene with proper hierarchy
- **Lighting System**: Directional lights for sun/moon with ambient lighting
- **Material System**: PBR materials with realistic roughness and metalness
- **Animation Loop**: 60fps rendering with delta time calculations
- **Camera System**: Perspective camera with orbit controls

### Key Classes and Functions
- `createPineTree()`: Procedural tree generation with multiple canopy layers
- `createDeer()` / `createRabbit()`: Animal mesh generation
- `animate()`: Main rendering loop with day-night cycle
- Lighting calculations for realistic sun/moon positioning

## 🌅 Day-Night Cycle

The environment features a complete 40-second day-night cycle with:
- **Sun Movement**: Arc trajectory across the sky
- **Moon Movement**: Opposite phase to the sun
- **Dynamic Lighting**: Intensity changes based on celestial position
- **Atmospheric Changes**: Background color transitions
- **Particle Effects**: Dust motes visible during day, stars at night
- **Fog Adaptation**: Fog color matches sky color

## 🎨 Visual Features

### Lighting & Shadows
- High-resolution shadow maps (4096x4096)
- Soft shadow filtering for realistic penumbra
- Multiple light sources with proper falloff
- Ambient lighting for night scenes

### Materials & Textures
- Procedurally generated ground textures
- Realistic material properties (roughness, metalness)
- Water reflection using Three.js Reflector
- Particle systems for atmospheric effects

### Animation
- Smooth animal movement with AI pathfinding
- Bird flight patterns with realistic banking
- Procedural tree swaying (future enhancement)
- Particle system animations

## 📊 Performance

### Optimization Techniques
- Efficient geometry reuse for trees and animals
- Level-of-detail considerations for distant objects
- Optimized shadow map resolution
- Particle count management for smooth performance

### System Requirements
- **Minimum**: Integrated graphics, 4GB RAM
- **Recommended**: Dedicated graphics card, 8GB RAM
- **Target**: 60fps on modern hardware

## 🔧 Technical Details

### Dependencies
- **Three.js v0.160.0**: Core 3D graphics library
- **OrbitControls**: Camera interaction
- **Reflector**: Water reflection effects

### Code Structure
```
├── index.html          # Main application file
├── README.md           # Project documentation
├── package.json        # Project metadata
├── LICENSE             # MIT license
└── .gitignore          # Git ignore rules
```

## 🎯 Assignment Objectives Met

This project demonstrates practical application of computer graphics concepts:

1. **3D Modeling**: Procedural generation of complex forest geometry
2. **Lighting**: Multiple light sources with realistic shadow mapping
3. **Texturing**: Procedural texture generation and material properties
4. **Animation**: Real-time animation of multiple object types
5. **Camera Control**: Interactive 3D navigation system
6. **Rendering Pipeline**: Complete WebGL rendering pipeline
7. **Performance**: Optimized for real-time rendering

## 🚀 Future Enhancements

- Weather system with rain and snow effects
- Seasonal changes with foliage color transitions
- Sound design with spatial audio
- VR/AR support for immersive experience
- Multiplayer support for shared exploration
- Advanced AI for more complex animal behaviors

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created as a computer graphics assignment demonstrating 3D environment design and real-time rendering techniques.

---

*Built with ❤️ using Three.js and modern web technologies*
