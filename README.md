# Ruthvik Chary's Portfolio

A personal portfolio built to showcase AI-assisted development projects and my frontend engineering skills.

## Week 7 Frontend AI Engineering Assignment
**"Your First 3D Experience on the Web"**

### What was built
Added an interactive 3D developer workspace directly into the existing vanilla HTML portfolio. The scene features a desk setup with a laptop and a customizable object, built using Three.js. Users can toggle auto-rotation and interactively change the color of a specific object in the scene. A fallback experience is provided for users with reduced motion preferences.

### Performance Note
The 3D canvas is lazy-loaded using the `IntersectionObserver` API. This ensures that the heavy 3D rendering engine and scripts are only executed and rendered when the user scrolls the 3D section into view, keeping the initial page load fast and mobile-friendly. Only lightweight geometric primitives are used to minimize resource usage.

### Future Improvements
With more time, I would:
- Import optimized glTF models (like a detailed room or character) instead of using primitive geometries.
- Bake lighting and shadows in Blender to significantly improve visual realism without the runtime performance cost of real-time lighting.
- Add more interactive elements like clicking on the laptop screen to open a project link.
