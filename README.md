# N-Body Astrodynamics & Spacecraft Trajectory Engine

An interactive, computationally rigorous 3D orbital simulation modeled in WebGL (Three.js). This engine computes multi-body planetary positions and executes interplanetary spacecraft transfers using authentic NASA JPL Keplerian elements for the 2026–2028 epoch.

## 🔭 Live Simulation Dashboard
https://garvit1230.github.io/solar-system-sim/

## ⚙️ Mathematical & Physical Architecture

* **J2000 Ephemeris Propagation:** Calculates true elliptical orbits using Kepler's transcendental equations rather than fixed circular approximations, ensuring planetary spatial coordinates match real-world NASA JPL data.
* **Tsiolkovsky Propulsion Dynamics:** Simulates active mass depletion and continuous fuel expenditure based on specific impulse parameters for both Chemical and Ion thrusters.
* **Patched-Conic Trajectories:** Executes dynamic Hohmann transfer orbits to intercept the target's future coordinates, incorporating variable atmospheric drag modeling during the launch ascent.
* **Tangential Orbital Capture:** Calculates a seamless state-vector transition at the destination's sphere of influence (SOI), executing a precise retrograde insertion burn to achieve a stable parking orbit without spatial clipping.
