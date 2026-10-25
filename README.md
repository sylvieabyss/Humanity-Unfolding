# Humanity Unfolding

**A civilization god game and simulator, from prehistoric societies toward the near future.**

Humanity Unfolding is an independent project by Sylvie Abyss. The Windows build currently retains the internal product name **Planetary** in its launcher and runtime. The project is in development and its gameplay and release status may change.

## Latest Windows preview

**Planetary 0.14.0 — Live World and Seasons preview**

The supplied build brings physical settlement parcels into the world, adds direct placement of supported buildings through God powers, displays recorded people and sailing craft, and shows seasonal landscape changes. These are previews of evolving systems, not evidence of a completed release.

**Stability warning:** The release notes report an unexplained spontaneous Windows restart during previous visible testing. The cause remains unresolved. No subsequent visible/GPU endurance test was performed for this build. This package is a feature preview on a stability hold and **is not certified safe for stress testing or long sessions**. Back up saves and exercise caution.

### Download and run

1. Download `Planetary-0.14.0-Live-World-Windows.zip` from the repository's **Releases** page after it has been uploaded there.
2. Extract the complete ZIP. Keep the `runtime` directory next to `Planetary.exe`.
3. Run the top-level `Planetary.exe`. Do not move just the executable out of the extracted folder.
4. Read the included `START-HERE.txt` and `LIVE-WORLD.txt` before playing.

This preview uses the separate `LocalAppData/PlanetaryCivilizationLiveWorld` Windows save profile. Older builds do not support some newer world metadata; retain your earlier builds and backup saves.

### Known limitations

- Continuous civilian walking and saved household addresses are not implemented.
- Roads, per-building inventories, fully independent port economies, aircraft, and naval combat remain unfinished.
- Visual/GPU performance, sustained high frame rates, and long-session stability remain unverified by the attached headless checks.
- The game currently ships as a Windows build; no source project is included in the provided release ZIP.

See [docs/RELEASE-0.14.0.md](docs/RELEASE-0.14.0.md) for more detail and the release artifact checksum.

## Source availability

The current GitHub upload package contains repository documentation, **not the editable Godot project or native extension source**. To make Humanity Unfolding truly source-available, the owner must additionally publish the original development source files, project configuration, assets they have the right to distribute, and required build instructions. The shipped `.pck`, `.exe`, and `.dll` do not substitute for those files.

## License and contributions

The project's **original materials** are intended to be offered under the custom [Humanity Unfolding Source-Available License](LICENSE): publicly inspectable, with private noncommercial experimentation allowed, but no independently distributed versions without permission. This is **not an open-source license**.

The supplied binary release contains Godot Engine and godot-cpp components with their own license notices. Those licenses remain in force and cannot be restricted by the game's proprietary terms. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Please review [CONTRIBUTING.md](CONTRIBUTING.md) before proposing substantial code or content. External material should not be merged before contributor rights are clearly agreed.

The repository previously included GPLv3 license text. Any permissions validly granted to earlier material under GPLv3 remain unaffected by the new licensing statement.
