3D Jet Engine Thruster Simulation
An interactive, web-based 3D CAD simulation of a modular jet engine thruster built with Three.js and Anime.js.

Overview
This project renders a stylized 3D procedural jet engine assembly featuring dark metallic shading, wireframe edge outlines, and warm directional rim lighting. Users can inspect the 3D geometry from any angle, scrub through an exploded-view timeline, and simulate turbine rotation and exhaust thrust.

Features
3D Orbit Inspection: Full camera rotation, panning, and zooming around the 3D assembly.

Timeline Scrubber: Custom bottom-right tick-mark scrubber linked to an Anime.js timeline for smooth control over the exploded view and camera orientation.

Modular Assembly: Nine distinct engine sub-assemblies that separate and rotate independently.

Thruster Simulation: Adjustable RPM and afterburner controls that drive internal gear rotation and exhaust plume effects.

Technical Callouts: Toggleable 3D spatial labels identifying individual engine sections.

Tech Stack
HTML5 / CSS3: Layout, HUD styling, and custom scrubber interface.

Three.js: 3D geometry generation, lighting, materials, edge rendering, and camera controls.

Anime.js: Timeline management, spring/elastic transitions, and property interpolation.

Controls
Left Click + Drag: Orbit camera around the model.

Right Click + Drag: Pan camera.

Scroll Wheel: Zoom in and out (or scrub the timeline when hovering over the bottom-right scrubber).

Bottom-Right Scrubber: Click and drag horizontally to manually scrub the exploded assembly state.

Setup and Usage
No build tools or local server dependencies are required.

Clone or download the repository.

Open index.html directly in any modern web browser with WebGL support.
