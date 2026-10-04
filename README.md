# AeroLab – 2D Airfoil Wind Tunnel

Real-time 2D airfoil CFD in the browser (no dependencies). Subsonic flow uses a pressure-projection solver; Mach ≳ 0.55 switches to a compressible Euler solver that shows bow shocks and oblique shocks.

- Pick an airfoil (NACA 0012 / 2412 / 4412, diamond, biconvex, flat plate, custom NACA 4-digit)
- Drag the airfoil (or use the slider) to change angle of attack, −20° … +30°
- Mach slider 0.05 … 3.0, overlays for pressure, velocity, vorticity and Schlieren
- Installable as a Progressive Web App (works offline after the first visit)

## Files
`index.html` (the app) · `manifest.json` · `sw.js` · `icon-192.png` · `icon-512.png`

## Install
Open the GitHub Pages link in Chrome → ⋮ menu → **Install app** (or **Add to Home screen**).
