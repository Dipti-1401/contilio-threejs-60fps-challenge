````markdown
# Contilio Three.js Code Challenge

## Overview

This project optimizes the rendering of 27,000 cubes in a Three.js scene to run at 60fps. The original implementation ran at about 10fps, and this solution uses `THREE.InstancedMesh` to improve performance.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Dipti-1401/contilio-threejs-60fps-challenge.git
   cd contilio-threejs-challenge
   ```
````

2. Serve the project:

   ```bash
   npm install -g serve
   serve -l 1234
   ```

3. Open `http://localhost:1234` in your web browser.

## Notes

- The solution is optimized for performance with `THREE.InstancedMesh`.
