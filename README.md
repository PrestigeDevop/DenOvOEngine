# a cross platform Game engine based on Veldrid renderer.
This is an example of simple 3D video game built with .NET Core. It supports Windows, OSX, and Linux. It is built on top of a custom game engine, the sources of which can be found here: https://github.com/mellinoe/ge.

This repository contains the game-specific assets and code files for Crazy Core. It has a submodule which includes the engine as a dependency.
![image](https://github.com/PrestigeDevop/DenvoEngine/assets/85388342/37e461b0-b308-41b5-a537-6933287f5dbc)

![Level4](https://i.imgur.com/IgyuUyRh.jpg)

![Level7](https://i.imgur.com/b5ic6x5h.jpg)

![Level8](https://i.imgur.com/ZHo1RLAh.jpg)

# a cross platform Game engine based on Veldrid renderer.

# Features
Graphics

    Full 3D rendering system, with support for Direct3D 11 and OpenGL backends
    Forward-rendered pipeline with support for real-time directional shadows, particle systems, transparent objects, and a simple immediate-mode GUI.
    Uses Veldrid (v1) and ImGui.NET

Physics

    Real-time 3D physics via BEPU Physics
    Various configurable physics shapes
    Customizable

Audio

    Positional audio
    Supports XAudio2 and OpenAL backends

Editor

    Cross-platform editor application
    3D scene view with editing widgets
    Asset management and serialization
    Live component value editing

Misc

    Unity Engine-like component system
    Plugin system
    Builds self-contained executable packages for publication per-platform
