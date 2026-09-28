# Daily Plugins organization profile

Daily Plugins is a collection of plugin repositories. Currently, the only available project is the [Vault plugin MCP server](https://github.com/daily-plugins/Vault).
This `.github` repository contains the public organization profile and shared brand assets. Server source lives in `Vault`.

## Brand assets

<img src="assets/daily-plugins.png" width="200" height="200" alt="Daily Plugins original 3D plug and S-shaped cable" />

| File | Bytes | Purpose |
| --- | --- | --- |
| [daily-plugins.png](assets/daily-plugins.png) | 1,452,787 | Exact user-supplied original, including dark background; used in the organization profile |
| [daily-plugins-transparent.png](assets/daily-plugins-transparent.png) | 446,766 | Background-removal edit preserving the 3D shape and colors; not pixel-identical to the original |
| [daily-plugins-compact.png](assets/daily-plugins-compact.png) | 6,215 | 192 × 192 transparent PNG, under 10,000 bytes |
| [daily-plugins.svg](assets/daily-plugins.svg) | 8,519 | Self-contained SVG with the compact PNG embedded, under 10,000 bytes |

The original image is preserved byte-for-byte. The transparent derivative was made with the built-in image-generation tool using background-only extraction instructions: retain the silhouette, S bends, plug, extrusion, shading, and cyan-blue-lavender colors. Small edge differences can occur in that derivative. Compact export uses palette compression.

The SVG is a raster container, **not an editable path-based vector**. This preserves the supplied artwork rather than replacing it with a simplified drawing. The full-resolution PNGs are not subject to the compact 10 KB limit.

## Organization profile

[profile/README.md](profile/README.md) displays the original artwork on the organization overview. The account avatar is unchanged.

Local working layout:

```text
daily-plugins/
├── .github/   Organization profile and brand assets
└── vault/     Vault plugin MCP server
```

[한국어 문서](notes/ko/README.md)
