# Spek-X Flatpak

📦 Flatpak Package of Spek-X for Linux

Spek-X is an acoustic spectrum analyser written in C and C++. It uses FFmpeg
libraries for audio decoding and wxWidgets for the GUI.

This fork uses [Spek-X](https://github.com/MikeWang000000/spek-X) by MikeWang000000.

You can install it from my personal flatpak repo (remove the --user argument to install system-wide)
``` bash
flatpak remote-add --user roddy-flatpak https://kichirouhoshino.github.io/roddy-flatpaks/index.flatpakrepo
flatpak install roddy-flatpak com.github.MikeWang000000.spek-X
```
Do note that the original Spek flatpak is now on [Flathub](https://flathub.org/apps/cc.spek.Spek). Spek-X is more updated and supports newer ffmpeg versions.
