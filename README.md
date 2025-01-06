# Spek-X Flatpak

📦 Flatpak Package of Spek-X for Linux

Spek-X is an acoustic spectrum analyser written in C and C++. It uses FFmpeg
libraries for audio decoding and wxWidgets for the GUI.

This fork uses [Spek-X](https://github.com/MikeWang000000/spek-X) by MikeWang000000.

## Building

```bash
flatpak-builder --install-deps-from=flathub --force-clean build-dir com.github.MikeWang000000.Spek-X.yml
```

## Update shared-modules

```bash
git submodule update --remote --merge
```
