# Credits

## Theme configuration

Tokyo Liftoff assembled for Tom Ballard, 10 October 2026. Its complete palette is the upstream Omarchy Tokyo Night palette at commit `077ac1da939de00d061c1035e1a1d00587a119b8`, palette blob `58e6785259b83a72a5921e2cfec4c66192860b7e`. Upstream copyright David Heinemeier Hansson; MIT permission notice retained in LICENSE.

The gallery and documentation were prepared for this release. The gallery is a contact sheet of included artwork, not a running-desktop screenshot.

## backgrounds/02-starship-ascent.png

Tokyo Night reinterpretation of the Starship ascent photograph supplied by Tom Ballard on 10 October 2026. The original photographer, source URL and image-specific licence were not supplied. No public-domain or Creative Commons status is asserted, and this theme's MIT licence does not grant rights over the photograph.

Approved navy, blue, lavender and pink variant; exported at 8192 × 4667 with embedded sRGB profile. Two contextual enhancement passes: three of nine first-pass grid edits accepted, then all four focal edits accepted. Prior source-derived pixels remain where correspondence was uncertain. Fine detail is AI reconstructed.

## backgrounds/03-golden-liftoff.png

Tokyo Night painterly restyle of the night launch image supplied by Tom Ballard on 9 October 2026: starfield, violet smoke, warm golden exhaust and coastal reflections. Original photographer, source URL and image-specific licence were not supplied; no public-domain or Creative Commons claim is made. MIT does not grant rights over this supplied image.

Approved export at 8192 × 4053. One full-scene style edit followed by two contextual enhancement passes. Eight of nine grid edits and five of seven focal edits accepted; uncertain rocket and tower areas retain prior pixels. Fine detail is AI reconstructed.

## backgrounds/01-liftoff-sunset.png

The approved painterly sunset Liftoff illustration, exported at 8192 × 4608, also proposed for upstream Tokyo Night in [PR #14755](https://github.com/omacom/omarchy/pull/14755). It reinterprets the original Liftoff launchpad photograph using a sunset landscape supplied by Tom as a style reference. The style-reference image is not redistributed here.

Original photograph credit: SpaceX. Source supplied by Tom: https://x.com/SpaceX/status/2104654998034690329

Tom confirmed on 30 September 2026 that SpaceX published the source photograph and released it into the public domain. This is the repository author's confirmation; independent image-specific licence verification was unavailable. No specific Creative Commons licence is asserted.

The sunset illustration received two contextual crop-enhancement passes, with uncertain reconstructed regions retaining prior pixels. Fine detail is AI reconstructed. Source rights and processing attribution are inherited from [Liftoff CREDITS.md](https://github.com/tcballard/omarchy-theme-liftoff/blob/main/CREDITS.md).

## backgrounds/04-engine-cluster.png

Tokyo Night restyle of the engine-cluster photograph supplied by Tom Ballard on 10 October 2026. The original photographer, source URL and image-specific licence were not supplied. No public-domain or Creative Commons status is asserted; configuration MIT does not grant rights over this photograph.

The full-scene colour edit follows the existing Starship Ascent wallpaper: navy sky, lavender/pink smoke and white-gold engine glow. Its native size is 1536 × 1024. Two contextual enhancement passes (pass 1: 2 of 9 accepted; pass 2: 4 of 4 accepted) use the complete styled context for every target. Rejected crops reached conservative registration bounds; prior pixels are retained. Accepted regions are globally aligned, broadly colour matched and blended through local confidence masks, with stricter checks around engine hardware.

Final export: 8192 × 5461, opaque 8-bit RGB PNG with embedded sRGB profile. Original 3:2 proportions are rounded to the nearest output pixel. The dimensions describe an assembled 8K export; detail is AI reconstructed, not recovered photographic information. [Prompts, native dimensions and processing](docs/engine-cluster-enhancement.md).

## Distribution

The first three PNGs were recompressed losslessly for distribution. Decoded pixels and embedded profiles match their approved masters exactly; hashes and dimensions are recorded in docs/wallpapers.json. The 8K dimensions describe assembled exports, not native 8K generations.

MIT covers configuration and documentation only. This is an unofficial community theme, with no SpaceX affiliation or endorsement.


## Repository scaffold

Initialized from [tcballard/omarchy-theme-template](https://github.com/tcballard/omarchy-theme-template), initial repository commit aabbbaff245aa747274b5df17b1f692937045c44, using Build Omarchy Themes guidance. Original template files are retained in .template/blueprint. MIT.

## XPS wallpaper evidence

[User-supplied XPS screenshot](docs/wallpaper-on-xps.jpg), provided by Tom Ballard on 10 October 2026 and preserved byte for byte. It shows Liftoff Sunset displayed on his desktop. The active theme and installed commit are unverified; this does not establish full theme acceptance.

## Author confirmation for marketplace submission — 10 October 2026

Tom Ballard confirmed that `preview.png` shows Tokyo Liftoff applied on his XPS and that he has permission to distribute the included images. He explicitly authorised submission to the official Omarchy theme store. This confirmation covers listing the theme and distributing all four included wallpapers. It does not assign a new licence to the underlying photographs or change the existing source credits. The preview is the supplied screenshot preserved byte for byte.
