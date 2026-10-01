# Prisma — Status

**As of:** 2026-10-01  
**Checkout:** `personal/Stonehenge/Color/Prisma`  
**Was:** Gamma. GitHub rename to `ledoit/Prisma` follows the account move.

## Shipped

- Harmonic palette generator (14 patterns, circle-of-fifths ring, hex copy)
- Cold load always renders defaults — never a blank page
- `localStorage` restores last palette settings on return (MT-26)
- Live at [prisma.koalasalmon.com](https://prisma.koalasalmon.com)

## In review

- MT-215 — Full-bleed gallery wall + Newsreader/Figtree type. Named color rectangles occupy the viewport; hue ring and patterns sit in a thin rail. Branched from MT-207 so the swatch rectangles stay. No `*.vercel.app` bounce.
  - PR: https://github.com/ledoit/Prisma/pull/4
  - Preview: https://prisma.koalasalmon.com

## Note on Linear backlog

Issues MT-25–MT-30 describe a **resume builder** pivot that was not shipped. This repo is the **palette product** (see stonehenge tagline). Resume-related backlog items should be canceled or moved to a future repo.

See [TODO.md](./TODO.md).
