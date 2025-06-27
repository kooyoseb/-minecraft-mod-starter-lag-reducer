# -minecraft-mod-starter-lag-reducer
This fabric mod will slightly reduce the initial lag caused by map loading when you first connect to a Minecraft world.

    A lightweight Fabric mod for Minecraft 1.21.6 that reduces initial lag when joining a world.
    It temporarily lowers the render distance and preloads block renderers in a background thread to smooth out the startup experience. After a few seconds, the original render distance is automatically restored.

Features:

    Detects when the player joins a world

    Temporarily reduces render distance to reduce rendering load

    Preloads block textures in the background

    Automatically restores original settings after a short delay

Perfect for:
Players who experience stutters or frame drops when first entering a world, especially on low-end systems or heavily modded setups.
