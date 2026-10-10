# Engine Cluster — Tokyo Night enhancement

Added on 10 October 2026. Source: supplied 1536 × 1024 JPEG, preserved byte for byte. One authorized full-scene Tokyo Night restyle followed by two contextual crop passes. Final PNG: **8192 × 5461**, embedded sRGB, opaque 8-bit RGB, 22,427,396 bytes.

## Accepted detail and retained regions

pass 1: 2 of 9 accepted; pass 2: 4 of 4 accepted. Seven first-pass crops reached the conservative alignment bounds and were excluded. The same policy applies to second-pass exclusions. Accepted patches use bounded global similarity registration, a local correspondence confidence mask, a smooth low-frequency colour-offset field, 20% interior-border feathering and normalized overlap. No local geometric deformation is used. Softer prior detail remains in excluded or low-confidence areas.

Pass 1 assembles at 3072 × 2048 before proportional 8K export. Pass 2 refines upper engines, left bells, right bells and exhaust ribbons on that preceding master. Engine hardware receives stricter confidence thresholds. All native accepted and rejected attempts are retained in the separate processing archive, together with original source, context, exact targets/prompts, masks, transforms, algorithm helpers and visual review evidence.

## Verification

Complete decode, source-hash preservation, PNG signature and every chunk CRC, exact IEND/file length, dimensions and lossless-export pixel identity passed. Full images and actual 100% hardware/exhaust overlap crops were inspected after both passes. No conspicuous seams, doubled bell edges or abrupt colour transitions were observed in the inspected hardware and exhaust overlap crops. Soft prior detail remains outside the accepted confidence masks; clipped engine highlights stay smooth.

- Source SHA-256: 3ccbd300ab2ceeda5df7c51cefb4bf3510c8001195bf137474b8ff425557492f
- Final SHA-256: f00948eeac36083128533548f61a78ff66e9ab6cb613f953b4e67e89bfa1f319
- Decoded RGB SHA-256: e8bc691ea6a05927034147ae05b6308bbe0aad683786578bc492fae4e95fd184

The 8K dimensions are an assembled export, not a native generation. Fine detail is AI reconstructed. Photographic fidelity of invented fine texture cannot be certified.

## Native edit dimensions

| Edit | Native dimensions | Decision |
| --- | --- | --- |
| Full-scene style | 1536 × 1024 | Accepted |
| p1-r1c1 | 1536 × 1024 | rejected |
| p1-r1c2 | 1659 × 948 | rejected |
| p1-r1c3 | 1536 × 1024 | rejected |
| p1-r2c1 | 1421 × 1107 | accepted |
| p1-r2c2 | 1534 × 1025 | rejected |
| p1-r2c3 | 1421 × 1107 | rejected |
| p1-r3c1 | 1536 × 1024 | rejected |
| p1-r3c2 | 1660 × 948 | accepted |
| p1-r3c3 | 1536 × 1024 | rejected |
| p2-upper-engines | 1723 × 913 | accepted |
| p2-left-bells | 1288 × 1221 | accepted |
| p2-right-bells | 1229 × 1280 | accepted |
| p2-exhaust-ribbons | 1693 × 929 | accepted |

[Exact prompts, coordinates, hashes, settings and decisions](engine-cluster-enhancement.json). Built-in image_gen was used; model identifier and numeric generation-size parameters were not exposed. No generation retries or third pass were made.
