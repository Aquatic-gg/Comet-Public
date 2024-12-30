# Comet-Public
Public repository for Comet containing wiki and issues.

# TODO:
- Folders for effects (better file organization)
- Emitter max lifetime component
- "Once" or "Instant" rate component or dictionary/map based rate component to simplify customizing particle spawning rates
- Random sprite component (technically possible with javascript but could be made easier)
- Default components
- Snowstorm file conversion
- Better color input method
- Standardize vector inputs (either "x" "y" "z" fields or arrays)
- More informative formatting errors
- Cross-file macros
- Local/global emitter movement options
- Fully fledged variables system with triggers such as on_emitter_spawn, on_emitter_tick, on_particle_spawn, etc
- Actions system which can be triggered by events (kill particle, kill emitter, change variable, etc)
- Removal of teleportation packet usage (will reduce RX by up to ~50% and allow for smooth movement in versions before teleportation duration (like 1.19.4))
- Configuration for how often particle should be updated (how often an update packet is sent). Would allow for massive decrease in RX for effects with slow-moving/changing particles (like smoke)
- Support for vanilla particle spawning
- Javascript optimization with caching (massive CPU-usage optimization)
- Particle data lookahead (for proper interpolation)
