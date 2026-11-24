# Wallstudioo
WallStudio — Smart Wall Paint Visualizer: A web-based virtual room paint preview application built with Angular, SVG, and HTML5 Canvas. Upload room photos, manually select wall polygons, apply curated paint shades with adjustable opacity, compare Before &amp; After views, and export painted room previews as PNGs.
# WallStudio — Smart Wall Paint Visualizer

**WallStudio (Smart Wall Paint Visualizer)** is an interactive web application that lets users preview how different wall paint colours look on their actual room photographs before painting.

## Overview
Choosing the right wall paint colour using traditional shade cards often leads to mismatches due to real room lighting and space differences. WallStudio bridges this gap by allowing users to upload a room image, outline specific wall boundaries manually, apply paint shades with adjustable opacity, compare before-and-after results, and download the final preview.

## Key Features
- **Room Photo Upload:** Supports JPG and PNG room images (up to 10 MB) with file validation and live preview.
- **Manual Wall Selection (SVG Polygon Editor):** Place 3 or more boundary points around a wall with undo, clear, and lock-in selection controls.
- **Virtual Paint Application:** Curated paint colour palette with HEX codes and real-time opacity adjustment (10%–100%).
- **Before & After Comparison:** Interactive split slider to compare the original wall with the painted preview.
- **PNG Export:** Composites the original photo and painted wall overlay onto an HTML5 Canvas for instant PNG download.
- **Responsive Design:** Works smoothly across desktop, tablet, and mobile screens.

## Tech Stack
- **Frontend:** Angular (Standalone Components & Signals), TypeScript, HTML5 Canvas, SVG, CSS3
- **Architecture:** Designed for MEAN Stack integration (MongoDB, Express.js, Angular, Node.js)
- **Deployment:** Netlify / Site123 / GitHub

## How to Use
1. Open the **Visualizer** and upload a JPG or PNG photo of your room.
2. Click at least 3 points around the wall boundary and click **Finish Selection**.
3. Pick a paint shade from the palette and adjust the **Paint Opacity** slider.
4. Drag the **Before & After** slider to compare, or click **Download Painted Room PNG** to save your design.

## Disclaimer
The virtual preview is an approximation. Actual paint appearance may vary depending on room lighting, wall texture, finish, and screen calibration.
