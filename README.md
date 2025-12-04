# 3D Periodic Table Data Visualization – Kasatria Assessment

## Overview
This is an interactive 3D data visualization web application built using **Three.js** and **CSS3DRenderer**. The app fetches data from a Google Sheet, displays it in a 3D "periodic table" format, and requires Google login for access.

---

## Features

- **Google Login** via OAuth 2.0 (Google Identity Services)
- **Dynamic Data** fetched from Google Sheet (Name, Photo, Details, Net Worth)
- **Conditional Tile Coloring** based on Net Worth:
  - Red: < $100K
  - Orange: $100K – $200K
  - Green: > $200K
- **4 Layouts**: 
  - Table (20x10)
  - Sphere
  - Double Helix
  - Grid (5x4x10)
- Responsive and interactive 3D elements with hover effects

---

## Setup Instructions

1. Create a Google Sheet and import the provided CSV data..
2. Create a Google Cloud Project and configure OAuth 2.0 credentials.
3. Set your webpage’s origin in the Google Cloud console.
4. Open `index.html` locally or host via GitHub Pages for web access.
5. Ensure your Google Sheet URL is correctly linked in the script.

---

## Technology Stack

- **Three.js** – 3D graphics rendering
- **CSS3DRenderer** – Render 3D DOM elements
- **TWEEN.js** – Smooth animations and transitions
- **HTML, CSS, JavaScript** – Core web technologies

---

## Live Demo

(https://arhamsyafiq01.github.io/threejs-periodic-table/)

---

## Author

**[Arham Syafiq]**

