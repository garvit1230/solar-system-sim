# Interactive 3D Spacecraft Trajectory & Solar System Simulator

An interactive, scientifically rigorous 3D orbital simulation modeled in WebGL (Three.js). This simulator computes real-world planetary positions and lets you configure and launch spacecraft missions to any planet in our solar system—or the Moon—using actual launch date windows from September 2026 to December 2028.

## 🔭 Live Simulation Dashboard
https://garvit1230.github.io/solar-system-sim/

## ⚙️ Core Technical & Physics Features

* **Real Planetary Orbit Math (NASA JPL Data):** Planets do not move in perfect, simple circles. This engine uses authentic orbital data to place planets exactly where they will be on any selected calendar date, solving complex orbital ellipse geometry in real-time.
* **Launch Windows & Trajectories:** The spacecraft does not fly in a straight line—it uses a curved intercept path (a transfer orbit) to meet the target planet where it will be upon arrival, accounting for its motion. An optimal "Launch Window" indicator tracks planetary alignment.
* **Fuel & Mass Physics (Rocket Equation):** A live propulsion budget computes the spacecraft's fuel consumption based on its starting mass and the target destination, applying the Tsiolkovsky Rocket Equation for both high-thrust Chemical and high-efficiency Ion engines.
* **Orbital Insertion Burn:** Upon arrival, the spacecraft doesn't simply snap or drop into a circle. The simulation calculates the precise speed reduction (the "insertion burn") needed for the planet's gravity to capture the probe smoothly into a stable orbit.
* **Jupiter Gravity Assist:** Incorporates optional "slingshot" assist trajectory planning, utilizing Jupiter's massive gravity to gain velocity and save precious fuel when traveling to outer worlds.
