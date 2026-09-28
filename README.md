# Daily Plugins organization profile

This repository contains the public organization profile and shared brand assets for [Daily Plugins](https://github.com/daily-plugins).

## Brand assets

<img src="assets/daily-plugins.png" width="128" height="128" alt="Daily Plugins icon" />

| File | Size | Format |
| --- | --- | --- |
| [daily-plugins.svg](assets/daily-plugins.svg) | 754 bytes | Editable 512 × 512 vector, transparent background |
| [daily-plugins.png](assets/daily-plugins.png) | 4,397 bytes | 256 × 256 RGBA PNG, transparent background |
| [daily-plugins-400.png](assets/daily-plugins-400.png) | 7,173 bytes | 400 × 400 RGBA PNG, transparent background |

Every asset is smaller than 10,000 bytes. The simple mark uses a cyan cable (`#68CBE8`) and a lavender plug (`#AA8AF5`), with a transparent slot. There are no gradients, shadows, background tiles, or baked-in checkerboards.

The user-provided plug-and-cable image was used as a visual reference. The SVG is a new, flat vector construction; the PNGs are rendered from that same source with `@resvg/resvg-js`. No third-party app icon paths are included.

## Organization profile

GitHub displays [profile/README.md](profile/README.md) on the public organization overview. Its image uses an absolute raw-content URL so it resolves from the organization page.

The account avatar is a separate setting and is not changed by this repository. This update applies the mark to the profile README only, as requested.

Reference: [GitHub organization profile documentation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

[한국어 문서](notes/ko/README.md)
