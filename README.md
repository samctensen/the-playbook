# The Playbook

A digital football playbook builder built with C++ and Qt, with screens for creating, studying, and testing plays.

Originally developed as a spring 2022 final project, approximately April–May. Uploaded to GitHub in September 2022.

## Build

Open `The_Playbook.pro` in Qt Creator with a compatible Qt Widgets kit and C++11 compiler.

The original upload is missing the `Box2D/` source tree referenced by the project and `box.h`. Restore that dependency from the original course project before attempting a complete build. This cleanup preserves the application code and documents that existing gap.

## Project

- `.cpp`, `.h`, and `.ui` files — application logic and Qt Designer screens.
- `assets/` — field, formation, and player artwork.
- `Resources.qrc` — resource aliases preserving the original `:/Images/...` paths.
- [Demo video](Demo.mp4).
