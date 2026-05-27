# Spiral Knights Mobile - Guide Update

**IMPORTANT:** All previous installation methods for Spiral Knights on mobile — including the original PojavLauncher guides and KnightLauncher — are now outdated and no longer maintained.

The current recommended solution is **SKapsule**, a dedicated Android app built from scratch by [Noxwell](https://github.com/beebono).

## Introducing SKapsule

SKapsule is a purpose-built Android (arm64) port of Spiral Knights. Unlike previous methods, it is not based on PojavLauncher or any Minecraft launcher fork. It ships its own custom JRE and native libraries, boots the game's actual Java VM on-device, and pulls game files directly from Grey Havens' official servers at first launch via getdown — the same pipeline used by the desktop client.

**Key Features:**

- **Full Client Experience:** Downloads and patches the game from the official servers at first launch.
- **Account Support:** Web and Steam login both supported.
- **Gamepad-First Controls:** Designed for Bluetooth/USB controllers, with touch for menu navigation.

**Where to find it:**

[SKapsule Repository](https://github.com/SKonstruct/SKapsule)

## History

| Method | Status |
|---|---|
| PojavLauncher (iOS via Trollstore / Android manual setup) | Broken — game update broke compatibility |
| KnightLauncher-Android (Amethyst-based APK) | Discontinued — superseded by SKapsule |
| **SKapsule** | **Current — actively maintained** |
