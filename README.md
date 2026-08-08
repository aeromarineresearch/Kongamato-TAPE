# KongamatoTape

**Unified speed / height situational display — concept demonstrator.**

An interactive, glass-cockpit *synthetic-vision* energy tape that presents airspeed and
height above ground on a single stacked track, with:

- an **expanding MSL altitude bar** (steady over changing terrain) and a **fixed-width airspeed window**
- **PFD-style scrolling tapes** (white ticks + numbers) and a persistent vertical-speed (V/S) readout
- a **look-ahead terrain heatmap** (yellow → orange → red) driven by the terrain *ahead*
- an **armable terrain-following autopilot** (climb-only, fixed 800 ft AGL hard deck)
- a live **flight-envelope (energy) risk field** and a **terrain vertical-situation** view
- a synthetic-vision terrain backdrop with translucent instrument bars

**Live demo:** https://aeromarineresearch.github.io/Kongamato-TAPE/

The metric behind it is *specific energy height* (`hₑ = h + V²/2g`), the basis of energy–maneuverability theory.

## Disclaimer

Concept demonstrator and visual **simulation only**. Provided "as is", without warranty of any
kind. This is **not** a navigation or flight instrument and must **not** be used for real-world
flight, navigation, or any operational decision. To the maximum extent permitted by law, the
creator disclaims all liability for any loss, injury, damage, or death arising from use of, misuse
of, or reliance on this software.

## License

© 2026 Kongamato — David Farquharson. **All rights reserved.** Proprietary — **not open source.**
No license is granted to use, copy, modify, or distribute this work. See [LICENSE](LICENSE).
