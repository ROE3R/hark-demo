# hark-demo

Static build of the Hark design-system demo (v2).

- `index.html`, `styles.css`, `app.js`, `wordmark.png` — the whole site, no build step on the server.
- Tokens come from `hark.com-DESIGN.md`. Mark drawn with Canvas UI `ParticleObject` (WebGL).
- Serve over http(s): the particle mark loads a texture, which `file://` blocks.
