<p align="center">
  <img src="fiqzlauncher-logo.svg" alt="FiqzLauncher" width="520">
</p>

FiqzLauncher is a Minecraft launcher with a fast offline mode. Start playing in seconds, without logging in, and keep every game version and modpack in its own instance.

It is a fork of [Prism Launcher](https://github.com/PrismLauncher/PrismLauncher) and is not endorsed by the Prism Launcher team.

## Features

- Fast offline mode: launch straight into the game with no login
- Multiple instances: keep different Minecraft versions and modpacks separate
- Everything Prism Launcher already does, including mod loader support

## Build from source

```bash
git clone --recursive https://github.com/afiqf5973-ops/FiqzLauncher.git
cd FiqzLauncher
cmake --preset linux
cmake --build --preset linux
```

Use the preset that matches your system (for example `windows_mingw`). You need CMake, Ninja, a C++ compiler, Qt 6 and a JDK installed. See the upstream build guide for the full list.

## Contributing

Issues and pull requests are welcome. Please open an issue first for big changes.

## License

FiqzLauncher is free software under the GNU General Public License v3.0, the same license as Prism Launcher. See [LICENSE](LICENSE).

Based on Prism Launcher. Copyright belongs to the Prism Launcher contributors and the original MultiMC authors.
