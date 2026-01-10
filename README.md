# KineticCosmos - Interactive 3D Particle System

A single-file 3D web application where particles react to hand gestures in real-time.

## Features
- **Hand Tracking**: Uses MediaPipe to detect hand tension (open/closed fist).
- **Interactive Particles**: 15,000 particles respond to your movements.
- **Shape Templates**: Transform particles into:
  - Sphere
  - Heart
  - Flower
  - Saturn
  - Buddha
  - Fireworks
- **Customizable**: Real-time color picker.

## How to Run
1. Serve the directory:
   ```bash
   python3 -m http.server 8080
   ```
2. Open `http://localhost:8080` in your browser.
3. Allow camera permissions.

## Technologies
- **Three.js**: 3D Rendering.
- **MediaPipe Hands**: Hand Tracking.
- **Vanilla JS**: No build tools required.
