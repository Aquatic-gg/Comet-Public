# Comet-Public
Public repository for Comet containing wiki and issues.

# TODO:
- Folders for effects (better file organization)
- Emitter max lifetime component
- "Once" or "Instant" rate component or dictionary/map based rate component to simplify customizing particle spawning rates
- Random sprite component (technically possible with javascript but could be made easier)
- Snowstorm file conversion
- Better color input method
- More informative formatting errors
- Cross-file macros
- Local/global emitter movement options
- Fully fledged variables system with triggers such as on_emitter_spawn, on_emitter_tick, on_particle_spawn, etc
- Actions system which can be triggered by events (kill particle, kill emitter, change variable, etc)
- Removal of teleportation packet usage (allow for smooth movement in versions before teleportation duration (like 1.19.4))
- Support for vanilla particle spawning
- Javascript optimization with caching (massive CPU-usage optimization)
- Particle data lookahead (for proper interpolation)
- Spawn back particles in once player is back in view.

## Features needed for full-ish Snowstorm integration:
- maximum particle amount for spawn rate components
- sphere, box, disc spawn shape
- events system
- variables system
