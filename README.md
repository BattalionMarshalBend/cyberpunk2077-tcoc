# cyberpunk2077-tcoc
True camera-oriented third-person movement mod for Cyberpunk 2077 — V turns to face your actual direction of travel. Add-on for Immersive Third Person.
# cyberpunk2077-tcoc — ITP: True Camera-Oriented Controls

**True camera-oriented third-person movement mod for Cyberpunk 2077.** V turns to face your actual direction of travel instead of strafing or backpedaling — smooth 360° locomotion across walk, jog and sprint, built as an add-on for [Immersive Third Person](https://www.nexusmods.com/cyberpunk2077/mods/32203).

!\[Cyberpunk 2077](https://img.shields.io/badge/Cyberpunk%202077-Mod-fcee0a?style=for-the-badge\&logo=cyberpunk\&logoColor=black)
!\[Version](https://img.shields.io/badge/version-1.1.0-blue?style=for-the-badge)
!\[Nexus Mods](https://img.shields.io/badge/Nexus%20Mods-Download-d98f40?style=for-the-badge)
!\[Status](https://img.shields.io/badge/status-active-brightgreen?style=for-the-badge)

📥 [**Download on Nexus Mods**](https://www.nexusmods.com/cyberpunk2077/mods/33789) · 📦 [Latest Release](../../releases/latest) · 🎥 [Video Preview](https://www.youtube.com/embed/hwRbqBHt5Dk)

!\[Preview](https://staticdelivery.nexusmods.com/mods/3333/images/33789/33789-1789174620-327197712.gif)

\---

## What is TCOC?

Most third-person mods for Cyberpunk 2077 keep V locked into forward-facing strafe/backpedal animations, which looks stiff compared to modern third-person action games. **TCOC (True Camera-Oriented Controls)** fixes that: V naturally turns toward the direction you're actually moving, relative to the camera — the same feel you'd get in games like *Death Stranding*.

This is a **locomotion overhaul**, not a replacement for ITP. It builds directly on top of [Immersive Third Person](https://www.nexusmods.com/cyberpunk2077/mods/32203) and changes only how V responds to directional input.

## Features

* ✅ True camera-oriented 360° movement, including diagonals
* ✅ Smooth transitions across walking, jogging and sprinting
* ✅ Optional gamepad sprint steering — camera follows V as you steer while sprinting (v1.1.0+)
* ✅ Configurable radial deadzone for gamepad input via CET overlay
* ✅ Camera-oriented head/eye tracking and spatial audio in third person
* ✅ Keeps the core Immersive Third Person feel intact — this only touches movement

## Requirements

* [Immersive Third Person (ITP)](https://www.nexusmods.com/cyberpunk2077/mods/32203) — required, install this first
* All requirements of ITP itself (Cyber Engine Tweaks, RED4ext, etc. — see ITP's page)

## Installation

**Mod manager (recommended):** install normally through Vortex or your manager of choice.

**Manual install:** extract the archive directly into your Cyberpunk 2077 installation folder.

> ⚠️ Don't rename the `.archive` files — the naming controls load order so TCOC correctly overrides ITP.

## Uninstallation

Mod manager: uninstall normally.

Manual: remove

```
archive/pc/mod/ITP-TCOC.archive
bin/x64/plugins/cyber\_engine\_tweaks/mods/ITP-TCOC/
r6/scripts/ITP-TCOC/
```

No save-game changes are made — removing TCOC won't affect your save.

## Compatibility

TCOC modifies ITP's player locomotion behavior and animation graph. It should be compatible with most mods that don't touch the same resources. Watch out for conflicts with mods that modify:

* `player\_locomotion.animgraph`
* Third-person locomotion animations
* Player movement animation blending
* ITP's locomotion behavior itself

Since TCOC builds directly on ITP's locomotion graph, major ITP updates may require a matching TCOC update.

> Known issue: some users report conflicts when running ITP alongside IFP. If that's you, uninstall IFP first before troubleshooting TCOC.

## FAQ

**Does this work without ITP?**
No — TCOC is an add-on for Immersive Third Person and requires it to function.

**Will this break my save?**
No, it's purely a locomotion/animation change with no save-game data.

**Is there a compatibility patch for \[some other FPP mod]?**
Only for [Immersive Third Person - True First Person Camera - Compatibility Fix](https://www.nexusmods.com/cyberpunk2077/mods/33471), which the author made for personal use. No plans for other FPP mods at this time.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md) for the full version history, or check [Releases](../../releases) for downloadable builds.

**Latest — v1.1.0:** Added optional gamepad sprint steering, with adjustable steering speed in the CET overlay.

## Credits

Huge thanks to [CybrDrake](https://www.nexusmods.com/cyberpunk2077/users/53164046), author of [Immersive Third Person](https://www.nexusmods.com/cyberpunk2077/mods/32203), for the third-person framework this mod builds on. Thanks to meanero for controller-focused tuning that shaped several movement improvements.

## Links

* 🔗 [Nexus Mods page](https://www.nexusmods.com/cyberpunk2077/mods/33789)
* 🐛 [Report a bug](../../issues)
* 💬 [Discussions / support](https://www.nexusmods.com/cyberpunk2077/mods/33789?tab=posts)

\---

*Cyberpunk 2077 and all related trademarks are property of CD PROJEKT RED. 
