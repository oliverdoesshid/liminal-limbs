# Liminal Limbs — Quest 3

Download the latest standalone Quest 3 build from the **Releases** page.

## Download

- Latest release: **v1.0.1**
- APK: `LiminalLimbs-Quest3-v1.0.1.apk`
- SHA-256: `b51c8d3b0970bd98f2450b6a267f1ff5ec297d480454fae749692e51fb35ae2f`
- Package: `com.effectcraft.liminallimbs`
- Architecture: ARM64
- Minimum Android SDK: 29
- Target Android SDK: 34

## Install

Install with SideQuest, or with ADB:

```bash
adb install -r LiminalLimbs-Quest3-v1.0.1.apk
```

This is a debug-signed test build. It is not a store submission.

## Online compatibility

Online play requires the same build on every headset. v1.0.1 enforces this with a
connection handshake:

- A v1.0.1 host rejects clients running any other build, including v1.0.0.
- A v1.0.1 client checks the host's build and leaves if the host is older.
- Solo/offline play does not perform this check and still works on any build.

All players must update to v1.0.1 before joining an online session. The old
v1.0.0 APK remains available for solo play, but it cannot connect to v1.0.1
hosts.

## Source code

The game source is proprietary and is intentionally not included in this repository.
This repository is used only to distribute the compiled release.

A downloadable APK can still be inspected or reverse-engineered; withholding the source
does not make the binary impossible to copy or analyze.

## Third-party software

The build includes an adapted Gorilla Tag locomotion controller based on Another Axiom's
MIT-licensed GorillaLocomotion project. The required notice is in
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Copyright

Copyright © 2026 EffectCraft. All rights reserved. No permission is granted to copy,
modify, redistribute, or reuse the proprietary game source or assets.
