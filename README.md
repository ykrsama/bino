# A fork of Bino optimized for macOS with VR glasses

Starting with bino version 2.2, optimized for macOS with 32:9 VR glasses e.g. Rayneo Air 3, Xreal one etc.

- Using old OpenGL version 2.1 for compatibility with macOS 10.13 and later

- Feat:
   - trackpad support
 
- Bug fixes:
   - distorted / glitching video 
   - wrong fov
   - playlist loading

## Build from source

- Build Qt (homebrew qt has problems with video playback, so we want to build it from source)
 
   ```bash
   ```

- Build QVR

   ```bash
   ```

- Build Bino

   ```bash
   ```
  
# Bino: a 3D video player

Bino is a video player with a focus on 3D and Virtual Reality:

- Support for 3D videos in various formats

- Support for 360° and 180° videos, with and without 3D

- Support for 3D displays with various modes

- Support for Virtual Reality environments, including SteamVR, CAVEs,
  powerwalls, and other multi-display / multi-GPU / multi-host systems

Bino is based on [Qt](https://www.qt.io/). The optional Virtual Reality
and multi-GPU support is based on [QVR](https://marlam.de/qvr/). No other
libraries are required.

See [bino3d.org](https://bino3d.org/) and the [manual](https://bino3d.org/bino-manual.html).
