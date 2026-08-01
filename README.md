# abiyyu2301.github.io

Personal portfolio — [abiyyu2301.github.io](https://abiyyu2301.github.io)

Static, single file. No build step, no dependencies. Open `index.html` in a browser
to work on it; push to `main` and GitHub Pages redeploys.

```
index.html                  the whole site — markup, CSS, and the reveal observer
assets/abi-crop.jpg         hero portrait
assets/abi_image.jpg        the uncropped original, kept as the source
assets/screenshots/         project thumbnails
```

Fonts (Archivo, JetBrains Mono) load from Google Fonts, so editing offline
falls back to system sans and mono.

## Palette

| Token | Value | |
|---|---|---|
| `--base` | `#131210` | warm near-black |
| `--paper` | `#EDE9DF` | bone |
| `--acid` | `#C7F135` | the one accent |
| `--muted` | `#837C6E` | warm grey |
| `--line` | `#2C2924` | hairlines |

## Gotcha

`.wrap` sets `padding-left`/`padding-right` separately on purpose. The shorthand
`padding: 0 32px` is a class-level rule that out-specifies `section { padding: 104px 0 }`
and silently collapses every section's vertical rhythm to zero.
