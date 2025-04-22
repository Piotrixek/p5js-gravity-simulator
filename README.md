# p5.js Gravity Simulator

An interactive N-body gravity simulation built with p5.js. Visualize planetary orbits, adjust parameters like gravity and time step, drag bodies, and observe energy conservation.

## Features

* **N-Body Simulation:** Simulates gravitational interactions between multiple bodies using Newton's Law of Universal Gravitation.
* **Verlet Integration:** Uses the Velocity Verlet integration method for numerical stability.
* **Interactive Controls:**
    * Adjust Gravitational Constant (G)
    * Adjust Time Step (dt)
    * Adjust Trail Length
    * Pause/Resume Simulation
    * Reset Simulation
    * Add Random Planets
    * Toggle Trails Visibility
    * Toggle Velocity Vector Display
    * Toggle Acceleration Vector Display
    * Toggle Center of Mass (CoM) Marker
* **View Controls:**
    * Zoom using Mouse Wheel
    * Pan by dragging the background
* **Body Interaction:**
    * Click to Select a body (displays info)
    * Drag selected bodies to reposition (pauses simulation during drag)
    * Remove selected body
* **Physics Display:**
    * Real-time calculation and display of Kinetic Energy (KE), Potential Energy (PE), and Total Mechanical Energy (E = KE + PE).
    * Calculation and display of the system's Center of Mass (CoM).
* **Visualizations:**
    * Celestial bodies with radius scaled by `mass^(1/3)`.
    * Fading orbital trails.
    * Optional velocity and acceleration vectors.
    * Static starfield background.

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* [p5.js](https://p5js.org/) library for canvas drawing, vector math, and interaction.

## Controls Summary

* **Mouse Wheel:** Zoom In/Out
* **Click & Drag Background:** Pan View
* **Click Body:** Select Body
* **Click & Drag Selected Body:** Reposition Body
* **UI Panel:** Use sliders, buttons, and checkboxes for simulation parameters and features.

## Future Ideas / Potential Improvements

* Collision detection and response (merging or bouncing).
* Focus view on a selected body or Center of Mass.
* Preset simulation scenarios (e.g., Solar System, Lagrange points).
* Ability to edit selected body properties (mass, velocity).
* Performance optimization for large numbers of bodies (e.g., Quadtree).
* More sophisticated trail coloring (e.g., based on speed).
* Save/Load simulation state.

## License

This project is licensed under the MIT License
