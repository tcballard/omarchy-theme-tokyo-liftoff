# Validation — Tokyo Liftoff

Checked against Omarchy Quattro commit `077ac1da939de00d061c1035e1a1d00587a119b8` on 10 October 2026.

## Passed

- colors.toml is byte-for-byte identical to upstream Tokyo Night: 26 assignments, explicit dark mode, all required semantic colours.
- The upstream `omarchy-theme-color` parser resolves all 56 palette values and aliases.
- All 19 upstream template files have resolvable simple colour tokens.
- Actual upstream theme staging and template rendering ran in a private fixture. Only references to HOME in the two staging scripts were redirected to the fixture; staging and rendering logic were unchanged. A .git-marked theme exercised the installed-theme path.
- Twenty themed configuration outputs generated, with no unresolved template tokens.
- Headless theme selection cycled Starship Ascent → Golden Liftoff → Liftoff Sunset → Starship Ascent.
- All three final PNGs fully decode; their dimensions, opaque RGB channels, SHA-256 hashes, embedded profiles and decoded-pixel hashes match the media manifest.
- Recompression preserves every decoded pixel and embedded profile from the approved masters.
- Each wallpaper is below 50 MiB. Combined wallpaper bytes: 74,776,700 (71.31 MiB).
- No symlinks, theme install hook, executable payload or forbidden terminal/editor overrides are shipped.

## Contrast

| Pair | Ratio |
| --- | --- |
| Foreground / background | 8.10:1 |
| Foreground / selection | 6.36:1 |
| Accent / background | 6.79:1 |
| Muted / background | 1.91:1 |
| Dark foreground / background | 2.76:1 |

The primary text and accent pairs meet the selected 4.5:1 and 3:1 targets. Muted and dark foreground preserve upstream Tokyo Night's subdued treatment; they do not meet 4.5:1. The complete palette was retained unchanged.

## Outstanding

Live Omarchy desktop, wallpaper-picker interaction and application retinting have not been observed. The gallery is artwork only, not a desktop screenshot.

The skill's Rust scaffold/check helper could not run because Cargo is unavailable. Equivalent local structure, palette, contrast and image checks were performed with Node, plus the upstream parser and headless staging scripts.

Published to the user-provided tcballard/omarchy-theme-tokyo-liftoff repository. No marketplace listing or live desktop acceptance is claimed. Image-specific rights remain as documented in CREDITS.md; configuration MIT does not license underlying photographs.
