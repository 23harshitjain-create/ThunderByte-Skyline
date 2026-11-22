# SKYLINE — Neon Airlift

A browser-based 3D drone delivery game. Fly through a colourful open city, recover the shipment, defend yourself from a small hostile squad, and deliver it at the landing pad. The city includes connected roads, building collisions, plaza details, trees, and lamp posts.

## Run it

Open `index.html` in a modern browser with WebGL enabled. Three.js is bundled locally in `assets/`, so the game does not need a build step or internet access to load its 3D engine.

## Controls

- **W / A / S / D** or **arrow keys** — smoothly fly relative to the camera; the drone turns with the camera's viewing direction
- **Q / E** — lower / raise altitude
- **Drag the mouse** — orbit the camera; **mouse wheel** — zoom
- **J** or **click** — fire
- **Space** — pick up cargo or deliver at the landing pad
- **Shift** — boost

You have 90 seconds. Enemy hits remove 20% health. The boost battery drains while boosting; when empty, the drone lands and stays put while recharging. Wait until it reaches 25%, then press Space to lift off. If health reaches zero while carrying cargo, it drops at that location and the drone respawns at base. Recover the shipment and complete the delivery.

## Files

- `index.html` — game interface, controls, missions, and 3D scene
- `assets/three.min.js` — bundled Three.js runtime
- `assets/THREE-LICENSE.txt` — Three.js license
