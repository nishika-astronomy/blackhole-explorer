Black Hole Explorer — General Relativity & Accretion Simulator

An interactive, premium browser-based educational simulator built to demonstrate the physical mechanics surrounding a static, spherically symmetric black hole under Schwarzschild geometry parameters. Designed like a modern digital science museum exhibit, this tool lets you visualize Einstein's spacetime transformations in real time.

🌐 Live Demo:
https://nishika-astronomy.github.io/blackhole-explorer/

🌌 High-Fidelity Physics Features

Accretion Doppler Beaming (Brightness Asymmetry):
Directly simulates relativistic Doppler boosting. Gas particles rotating towards the observer on the right side are rendered significantly brighter, while the receding left side fades into a dimmer, redshifted glow.

Upgraded Schwarzschild Radius & Shadow:
Features a 30% larger, perfectly black shadow centered as a major focal point, providing a much higher physical sense of scale.

Thin Bright Photon Ring ($r = 1.5\ R_s$):
A razor-thin, electric-blue glowing boundary demonstrating where gravity is so dense that light photons are forced into circular orbits. Flashes with temporal high-bloom bloom whenever probes collide.

Interactive Spacetimes & Geodesic Drops:
Launches warning-orange telemetry probes from outer bounds ($14.5\ R_s$). Dropped objects accelerate, visually shrink/redshift, and spiral inward on natural geodesic curves.

Dilation Clocks:
Compares flat space time ($t$) and local dilated observer time ($\tau$) side-by-side using mechanical sweep second hands.

📐 Relativistic Formulations Mapped

The simulator computes real-world spacetime coordinates using:

Schwarzschild Radius ($R_s$):


$$R_s = \frac{2 \cdot G \cdot M}{c^2} \approx 2.9532 \times \text{Mass } (M_{\odot}) \text{ km}$$

Gravitational Time Dilation ($\tau$):


$$\tau = t \cdot \sqrt{1 - \frac{R_s}{r}}$$

Radial Escape Velocity ($v_{esc}$):


$$v_{esc} = c \cdot \sqrt{\frac{R_s}{r}}$$

Circular Orbit Speed ($v_{orb}$):


$$v_{orb} = c \cdot \sqrt{\frac{R_s}{2 \cdot r}}$$

📂 File Architecture

Optimized into a lightweight, portable single HTML bundle:

├── index.html        # Unified simulator containing UI layouts, styling, & simulation mechanics
└── README.md         # Educational user manual & physical formulations


🛠️ Usage Instructions

No setups or local servers are required:

Double-click the saved index.html file to open it in any modern browser.

Interact with parameters or drop a Research Probe to explore spacetime warp parameters.
