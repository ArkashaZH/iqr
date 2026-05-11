# iQR

> Creator-initiated commerce. Every visible product, a verified digital identity.

iQR is a three-sided platform where **creators** tag products with verifiable QR identities, **brands** run measurable campaigns, and **buyers** scan the world to acquire what they see.

This repository contains the early demos used to validate the visual identity and the vision before MVP build.

---

## Demos

### `index.html` — Studio

A single-file QR studio. Type a creator handle, product, destination URL, and an accent color. Get a live QR code and a live landing page preview side-by-side. Real shareable URL via base64-encoded state — no backend.

**Open**: [index.html](./index.html)

### `scanner.html` — Scanner Mode

An interactive cyberpunk scene with six discoverable product QRs. Move your cursor across the city — tagged objects lock on with a HUD reticle. Click to open a real scannable QR + product card. The pitch demo for the long-term vision.

**Open**: [scanner.html](./scanner.html)

Both files are self-contained. No build step. Open them in a browser.

---

## Status

- **Stage**: pre-product
- **30-day priority**: validate visual identity with creators
- **90-day priority**: ship MVP with auth, real creator dashboard, scan attribution

---

## What's deliberately NOT here yet

- Auth / accounts / persistence
- Real scan attribution (the demos use client-only state)
- Brand-side tools, campaign management
- AR / camera-based scanner (Vision-only roadmap)
- Mobile app

These come after creator signal validates the wedge.

---

## Hosting (optional)

Either demo can be hosted on any static host (Cloudflare Pages, Vercel, GitHub Pages, Netlify) with zero configuration.

For GitHub Pages: enable Pages on this repo's main branch, root folder. The Studio demo will serve from `/`, Scanner Mode from `/scanner.html`.

---

## Project knowledge

Operating manual for AI work: [`CLAUDE.md`](./CLAUDE.md)

Strategy, decisions, roadmap, and glossary live in Notion (private workspace).

Tasks tracked in Linear under the `iqr` label.

---

## License

TBD. All rights reserved until we decide.
