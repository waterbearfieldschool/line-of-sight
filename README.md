# Line of Sight Analysis Tool

An interactive web-based tool for analyzing radio frequency line-of-sight between two points, taking into account terrain elevation and Fresnel zone clearance.

## Live Demo

🌐 **[Try it live](https://waterbearfieldschool.github.io/line-of-sight)** (replace with your actual GitHub username)

## Features

- **Interactive Map**: Click to place two points (A and B) on a topographic or satellite map
- **Elevation Profile**: Real-time elevation profile visualization from leftmost to rightmost point
- **Antenna Height Configuration**: Adjustable antenna heights with live updates
- **Line-of-Sight Analysis**: Automatic calculation considering 60% Fresnel zone clearance
- **Visual Feedback**: 
  - Green solid line = Clear path
  - Red dashed line = Blocked path
- **Terrain Markers**: Automatically identifies peaks and potential obstructions

## Versions

- **[Main Tool](index.html)** - Latest version with live updates and A→B notation
- **[v1.html](v1.html)** - Version with A/B labeled markers and left-to-right ordering
- **[v2.html](v2.html)** - Enhanced version with arrow notation and live antenna height updates

## Usage

1. Click two points on the map to set your transmission path
2. Adjust antenna heights for each point
3. Click "Analyze" to calculate line-of-sight
4. Drag markers to test different locations
5. Hover over the elevation profile to see detailed information

## Technology

- Leaflet.js for interactive mapping
- Plotly.js for elevation profile visualization
- Open-Elevation API for terrain data
- Pure HTML/CSS/JavaScript - no server required
