# ArtX iOS Design System — Design Tokens

Two pages from the Figma design system「🌏 ArtX iOS Design System」:

- `/` — **design tokens**: colours, spacing, radii, blur, typography, elevation
  and gradients, each next to its Figma name and value.
- `/components/` — **component guideline**: 19 components and the icon library,
  every variant, size and state drawn at real dimensions.

Published with GitHub Pages.

## The contents are encrypted

Both pages carry their content as an `AES-256-GCM` blob. The key is derived
from a password with `PBKDF2-SHA256` at 250,000 iterations, so the page is
unreadable — in the browser or in this repository — without it.

This repository is public only because GitHub Pages requires it on the free
plan. Nothing legible is exposed by that: the ciphertext is what is public, and
the password is shared separately.

## Regenerating

Both pages are generated from the design system source. Ask for a fresh export
rather than editing the HTML by hand.
