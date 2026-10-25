# Planetary 0.14.0 — Live World and Seasons preview

Release type: **Windows feature preview; stability hold**

Source of these notes: `START-HERE.txt` and `LIVE-WORLD.txt` bundled in the supplied Windows ZIP. This is a summary of the package's self-reported features and checks; it is not an independent gameplay or hardware validation.

## Key changes

- Physical homes, farms, workshops, forts, and other supported settlement facilities have stable world locations and footprint checks.
- Automatic development and manual God-mode placement affect the same world.
- Residents and crews on screen are linked to simulated recorded identities rather than invented population sprites.
- Seasonal appearance changes terrain, foliage, roof, snow, and crop presentation across appropriate geographic conditions.
- Distant settlement rendering uses spatial district aggregation.
- New construction may write schema-eleven metadata. Legacy aggregate settlements may show derived approximate plots.

## Current limitations

Civilian walking and pathfinding, permanent household addresses, roads, independent port logistics, per-building inventory, aircraft, naval combat, and future infrastructure remain unfinished. Existing historic building placements were not stored at plot-level precision and cannot be reconstructed exactly.

## Validation and caution

The bundled notes report 360 source checks, 360 packaged-PCK checks, and 87 interface/camera/startup checks. These are headless or non-graphical checks, not a verified user-playthrough. GPU rendering, actual device performance, 240 FPS at 2560×1440, and long-session stability were **not certified**.

**Important:** A previous spontaneous Windows restart during visible testing remains unexplained. The build was not subjected to a new visible/GPU endurance test. Use caution, avoid stress testing, keep older builds, and back up saves.

## How to install

Download the release ZIP, extract the entire folder, and run `Planetary.exe` with `runtime/` adjacent to it. Read the bundled `START-HERE.txt`, `LIVE-WORLD.txt`, and `WEATHER.md` for details.

## Release artifact

- Filename: `Planetary-0.14.0-Live-World-Windows.zip`
- SHA-256: `55fef5164402632f127fa0f0b94e180b81019204b619c2da1b414c5ee53ee810`
- This archive belongs in **GitHub Releases**, not the Git source tree.
- The archive is a compiled preview, **not source code**.
