# Architecture

`colors.toml` is the source semantic palette. Omarchy derives supported application configuration from it; do not edit generated current-theme output.

The starter includes no shell overrides, install hooks, Lua, wallpapers or preview. Add licensed media under backgrounds and record its provenance in CREDITS.md. Add section-specific shell overrides only after verifying the target Omarchy contract.

The portable validator accepts flat quoted hex colours and checks text contrast. It is not a complete TOML parser or registry validator.
