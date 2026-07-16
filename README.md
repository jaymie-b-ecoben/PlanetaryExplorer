# Planetary Explorer

An interactive 3D Solar System built with **Three.js** that makes exploring space engaging and educational. Travel between planets, discover real NASA data, compare worlds side by side, and see what you'd weigh across the Solar System—all from a **single HTML file** with no build tools or texture assets.

**Live Demo:** https://jaymie-b-ecoben.github.io/PlanetaryExplorer/
**Portfolio:** https://jaymie-ecoben.site

---

## Overview

Planetary Explorer is a browser-based visualization of our Solar System that combines real planetary data with procedural graphics and smooth interactive controls. Every planet is generated at runtime using code, creating a lightweight experience that requires no downloaded textures or installation.

The project was built to showcase modern web graphics while making astronomy more accessible and enjoyable to explore.

---

## Features

### Interactive Solar System

- Explore all eight planets orbiting the Sun
- Smooth fly-to camera transitions when selecting planets
- Realistic orbital inclinations and animations
- Saturn's rings with the Cassini Division
- Earth's Moon and an asteroid belt between Mars and Jupiter
- Layered starfield with twinkling stars and a Milky Way backdrop

### NASA Planetary Data

Every planet includes:

- Diameter
- Mass
- Gravity
- Length of day
- Length of year
- Distance from the Sun
- Sunlight travel time
- Number of moons
- Average temperature
- Curated facts and field notes

### You on Another Planet

Enter your:

- Weight
- Age

Instantly discover:

- Your weight on every planet
- Your age in planetary years

### Compare Planets

Compare any two planets with:

- True relative diameter visualization
- Side-by-side statistics
- Automatic highlighting of the larger value for each category

### Procedural Planet Generation

Every planet is generated entirely at runtime.

No texture images are downloaded.

Each world includes unique procedural details, including:

- Earth with continents, oceans, clouds, and biomes
- Jupiter with cloud bands and the Great Red Spot
- Mars with Valles Marineris and polar caps
- Mercury covered in crater fields
- Neptune's Great Dark Spot
- Saturn's ring system

### Extra Touches

- PNG screenshot capture
- Random planet explorer
- Cinematic startup animation
- Keyboard shortcuts
- Adaptive simulation speed while following planets
- Welcome screen
- Zero build process
- Single-file deployment

---

## Built With

| Technology                | Purpose                       |
| ------------------------- | ----------------------------- |
| Three.js (r128)           | 3D rendering                  |
| HTML5                     | Structure                     |
| CSS3                      | Styling                       |
| Vanilla JavaScript        | Application logic             |
| Canvas API                | Procedural texture generation |
| NASA Planetary Fact Sheet | Planetary data                |

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/yourusername/planetary-explorer.git
```

Or simply download the project and open:

```text
planetary-explorer.html
```

For the best experience, serve it locally:

```bash
npx serve .
```

or

```bash
python3 -m http.server 8000
```

Then visit:

```
http://localhost:8000/planetary-explorer.html
```

The only external dependency is the Three.js CDN.

---

## Controls

| Action                 | Input               |
| ---------------------- | ------------------- |
| Orbit camera           | Drag / Swipe        |
| Zoom                   | Mouse wheel / Pinch |
| Select a planet        | Click / Tap         |
| Return to overview     | Click the Sun       |
| Previous / Next planet | ← →                 |
| Pause simulation       | Space               |
| Open comparison        | C                   |
| Close panels           | Esc                 |
| Save screenshot        | Snap                |
| Visit a random planet  | Surprise            |

Use the **Time** slider to control simulation speed and toggle orbit paths whenever you'd like.

---

## Mobile Support

Planetary Explorer is fully optimized for mobile devices.

Features include:

- Touch-friendly controls
- Pinch-to-zoom
- Smooth camera momentum
- Bottom-sheet information panels
- Optimized geometry and procedural textures
- Reduced-motion support for accessibility

---

## Project Structure

Everything lives inside a single file:

```
planetary-explorer.html
```

Internally, the project is organized into six main sections:

1. Planet data
2. Procedural texture generation
3. Scene construction
4. Camera system
5. User interface
6. Animation loop

---

## Data Sources

Planetary statistics are based on the **NASA Planetary Fact Sheet (NSSDCA)**.

Planet appearances are procedurally generated artistic interpretations rather than photographic textures. Planet sizes and orbital distances are intentionally scaled for readability and a better interactive experience.

---

## Why This Project?

Planetary Explorer started as a challenge to build an immersive educational experience using only browser technologies.

The project demonstrates how modern web development can combine:

- Real-time 3D graphics
- Procedural generation
- Interactive data visualization
- Astronomy
- Responsive UI design

—all without frameworks, build tools, or external assets.

---

## Developer

**Jaymie Ecoben**

Software Developer • Data & Analytics • Quality Assurance

Portfolio: https://jaymie-ecoben.site

---

If you enjoyed this project, consider giving the repository a ⭐ on GitHub.
