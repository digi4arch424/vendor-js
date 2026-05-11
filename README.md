# vendor-js

Self-hosted frontend JavaScript dependencies for projects by [@digi4arch424](https://github.com/digi4arch424).

Served via GitHub Pages — no CDN tracking, no external dependencies.

## Usage

```html
<script src="https://digi4arch424.github.io/vendor-js/peerjs.min.js"></script>
```

## Libraries

| File | Library | Version | Used In |
|---|---|---|---|
| `peerjs.min.js` | PeerJS | 1.5.5 | construction-cam (M1) |
| `three.min.js` | Three.js | r128 | construction-cam (M4) |
| `ar.min.js` | AR.js | 3.4.5 | construction-cam (M3) |

> Three.js and AR.js not yet added — placeholders for future milestones.

## Adding a New Library

1. Download the minified file
2. Upload to this repo root
3. Update the table above
4. Reference via `https://digi4arch424.github.io/vendor-js/filename.min.js`

## Projects Using This Repo

- [site-eye-webRTC](https://github.com/digi4arch424/site-eye-webRTC) — Construction Camera System
