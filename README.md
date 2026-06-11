# PlayerStack — HTML5 Radio &amp; Podcast Player

A themeable, whitelabel HTML5 player system for broadcasters. One player, two surfaces — a station-forward **launch overlay** and a persistent **64–72px bottom bar** — sharing a single visual system.

**▶ Live demo:** https://rpartalis404.github.io/playerstack/

## What's inside

- **Interactive prototype** — drive every state live (idle, loading, playing, paused, ad, error, offline) across both surfaces, both content modes, and desktop / mobile.
- **Full state grid** — every state × content mode × device × surface, laid out as labeled mockups.
- **Two content modes** — live radio (LIVE indicator, no scrubber) and on-demand podcast (scrubber, seek, chapters).
- **Video preroll** — non-skippable 16:9 ad stage with countdown + a companion 300×250; the audio stream is gated until it ends.
- **Native ad slots** — 728×90, 300×250, 300×600 rail, 320×50 bar. Every unit occupies reserved space, so ads read as part of the layout with **zero layout shift**.
- **Theming via CSS variables** — logo, `--primary`, `--bar-h`, light / dark, background. A live Tweaks panel demonstrates re-skinning.

## Tech

Single self-contained HTML file. React + Babel are inlined — no build step, no dependencies, works offline. Just open `index.html`.

## Theming tokens

| Token | Purpose |
|-------|---------|
| `--primary` | Brand / accent color |
| `--bar-h` | Bottom-bar height (64–72px) |
| `--font-display` | Display typeface |
| `.theme-dark` / `.theme-light` | Light & dark surfaces |

---

© 2026 — built as a design system reference.
