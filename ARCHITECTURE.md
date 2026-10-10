# Architecture

`colors.toml` is the complete upstream Tokyo Night semantic palette. Omarchy generates shell, terminal and supported app configuration from it. The theme supplies three approved full-frame 8K PNGs directly under `backgrounds/`.

No shell overrides, Lua, install hooks or terminal/editor configuration overrides are included. Documentation, previews and provenance live under `docs/`; the gallery is not a desktop screenshot. The native installer derives directory `theme-tokyo-liftoff` from the repository name.

The retained starter checks validate palette syntax, contrast, identity, README links and pinned CI actions. Headless staging and full image verification are recorded in docs/validation.md. Portable checks do not establish live acceptance.
