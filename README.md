# AeroLab – 2D Airfoil Wind Tunnel

Real-time 2D airfoil CFD in the browser (no dependencies). Subsonic flow uses a pressure-projection solver; Mach ≳ 0.55 switches to a compressible Euler solver that shows bow shocks and oblique shocks.

**Live demo:** https://bhargavd1501.github.io/Airfoil-tunnel/

- Pick an airfoil (NACA 0012 / 2412 / 4412, diamond, biconvex, flat plate, custom NACA 4-digit)
- Drag the airfoil (or use the slider) to change angle of attack, −20° … +30°
- Mach slider 0.05 … 3.0, overlays for pressure (Cp), velocity, vorticity and Schlieren
- Smoke lines, particle pathlines, streamlines and velocity vectors
- Live HUD: α, Mach, CL, CD, L/D, ΔP, Cp min, with theoretical CL/CD for comparison
- Auto quality mode holds about 60 FPS on phones and high-DPI screens
- Installable as a Progressive Web App (works offline after the first visit)

## Controls
Drag the airfoil to rotate · ↑ / ↓ change α · Space pauses · ↺ resets the flow · ⛶ fullscreen

## Files
`index.html` (the app) · `manifest.json` · `sw.js` · `icon-192.png` · `icon-512.png`

## Install
Open the GitHub Pages link in Chrome → ⋮ menu → **Install app** (or **Add to Home screen**).

## Note
Educational and visual tool, not a validated CFD solver. Forces, shock positions and stall behaviour are approximate.
