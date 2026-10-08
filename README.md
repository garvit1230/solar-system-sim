# 3D Spacecraft Orbit & Solar System Simulator

Hi! This is an interactive 3D simulation of our Solar System, made entirely in JavaScript and WebGL. It allows you to select a real date (from 2026 to 2028), pick a planet, and launch a satellite from Earth to go and orbit that planet!

## 🚀 Play with it here:
https://garvit1230.github.io/solar-system-sim/

## 🧠 How it works (The Physics)
* **Real Planet Positions:** Instead of running on simple loops, the planets are exactly where NASA says they will be on any date between 2026 and 2028 based on Keplerian Orbit Equations.
* **Real Rocket Science:** The satellite burns "fuel" and loses weight as it travels, calculated using the Tsiolkovsky Rocket Equation.
* **Real Flight Paths:** It calculates a curved journey (called a Hohmann transfer) to intercept the target planet while it moves, rather than aiming at where it was at launch.
* **Real Orbital Insertion:** When the ship arrives, it doesn't just stop or snap to a path; it fires its brakes to be captured by the planet's gravity.
