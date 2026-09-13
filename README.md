# Echoes of Aetheria

Astronomical survival prototype with a living, deterministic biosphere.

## Biosphere leap
The ecosystem now models:

- Individual genomes, inherited traits, phenotypes, and rare mutation drift.
- Predator perception, memory, stalking, hunting, pack coordination, and retreat/territorial response.
- Herbivore/flock behavior, food pressure, population recovery, reproduction, and offspring generation.
- Resource/season migration pressure and territorial dominance conflicts.
- Mutualism, parasitism, host/symbiote bonds, and ecological state changes.
- Seeded environmental events including Aether Blooms, Aether Storms, and Void Disturbances.
- Apex Beasts with expanded territory, alpha behavior, and procedural physical expression.
- Astral Titans with world-scale presence and celestial-signature recognition.

Simulation remains independent of Three.js. Rendering consumes ecological state and turns genome/tier data into visible bodies and a compact HUD telemetry strip.

## Run

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Test

```bash
npm test
```

The suite covers the original astrology/evolution systems plus the biosphere leap.
