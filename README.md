# Chladni Resonance Visualizer
Interactive Physics Project - Waves & Vibrations

**What is this?** This simulates a Chladni Plate. When a rigid square plate vibrates at specific frequencies, it creates standing waves.

**How it works:** The vibration causes areas of maximum movement (antinodes) and areas of zero movement (nodes). Sand particles bounce off vibrating areas and naturally collect in the nodes, forming geometric patterns.

**Math:** The amplitude is calculated using the formula:
`z = cos(N*π*x) * cos(M*π*y) - cos(M*π*x) * cos(N*π*y)`

**An interactive 2D physics simulation built purely in Vanilla JavaScript and HTML5 Canvas.**

## What is it?
This visualizer simulates the patterns formed on a Chladni Plate. When a rigid square plate is vibrated at specific frequencies, standing waves are created. Sand particles naturally bounce away from the vibrating areas (antinodes) and collect in the areas of zero movement (nodes).

## Technical Details
- **Math Engine:** Calculates the amplitude at any given point using the exact trigonometric equation for a square Chladni plate: `z = cos(N*π*x) * cos(M*π*y) - cos(M*π*x) * cos(N*π*y)`
- **Performance:** Handles 12,000 individual particles simultaneously.
- **Optimization:** Uses `Float32Array` for coordinate storage to optimize memory allocation and maintain high frame rates.

## How to use
Adjust the Harmonic N and Harmonic M values and watch the sand re-organize into complex geometric patterns.
