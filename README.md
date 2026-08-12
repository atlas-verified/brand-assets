# Atlas Verified — Brand Assets

Public brand kit for Atlas Verified logos, icons, and marketplace / MCP listing art.

**Org:** [atlas-verified](https://github.com/atlas-verified)  
**Site:** [atlasverified.ai](https://atlasverified.ai)

## Quick picks

| Use case | File |
|---|---|
| App / MCP icon (black square) | [`logos/icon/atlas-icon-square-black.png`](logos/icon/atlas-icon-square-black.png) |
| Icon mark only (transparent) | [`logos/icon/atlas-icon-mark.png`](logos/icon/atlas-icon-mark.png) |
| Favicon | [`logos/icon/favicon.ico`](logos/icon/favicon.ico) |
| Full lockup square (black) | [`logos/square/atlas-verified-logo-square-black.png`](logos/square/atlas-verified-logo-square-black.png) |
| Full lockup square SVG | [`logos/square/atlas-verified-logo-square-black.svg`](logos/square/atlas-verified-logo-square-black.svg) |
| Wide wordmark (light) | [`logos/wide/atlas-logo-wide-light.png`](logos/wide/atlas-logo-wide-light.png) |

## Structure

```text
brand-assets/
├── logos/                 # canonical “grab these” files
│   ├── icon/
│   ├── square/
│   └── wide/
├── exports/
│   ├── svg/               # source vectors
│   └── png/               # sized PNG packs
│       ├── icon/          # 16→1024, rounded app icons, favicon
│       ├── square/        # 256→2048 lockup
│       └── wide/          # 400→1600 wordmark
└── originals/             # uploaded source files (do not edit)
```

## Brand colors

| Token | Hex | Notes |
|---|---|---|
| Black | `#0A0A0A` | Primary background |
| Gold | `#AB8000` | ATLAS word + upper mark |
| White | `#FFFFFF` | VERIFIED word + lower mark |

## Variants

### Icon
- `atlas-icon-square-black` — diamond mark on black square (app icons, avatars, MCP)
- `atlas-icon-mark` — mark only, transparent background (overlays)
- `atlas-icon-app-rounded-*` — iOS / marketplace style rounded squares
- Sizes: 16, 32, 48, 64, 128, 180, 192, 256, 512, 1024

### Square lockup
- `atlas-verified-logo-square-black` — icon + ATLAS + VERIFIED on black
- SVG master + PNG 256 / 512 / 1024 / 1080 / 2048

### Wide
- `atlas-logo-wide-light` — gold mark + ATLAS on white (trimmed)
- PNG 400 / 800 / 1200 / 1600

## Usage notes

- Prefer **SVG** when the host accepts vectors (web, docs).
- Prefer **PNG 512 or 1024** for marketplace / MCP listings.
- Prefer **icon square black** for profile avatars and small UI chrome.
- Keep clear space around the mark roughly equal to the height of the gold triangle.
- Do not recolor the gold/white mark off-brand unless building an approved mono variant (not shipped yet).

## License

© Atlas Verified. These assets may be used to represent Atlas Verified in product integrations, documentation, and marketplace listings. Do not use the marks to imply partnership or endorsement without permission. All other rights reserved.
