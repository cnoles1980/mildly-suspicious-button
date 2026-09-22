# The Mildly Suspicious Button

A silly website with little to no purpose. Press the button. Something might be happening somewhere. It will never be explained.

Live deploy: push this folder to GitHub → Settings → Pages → Deploy from branch → `/root` (or set Pages root to `mildly-suspicious-button/`).

Analytics: this site uses its own Google Analytics 4 property and web stream. The measurement tag is in `index.html`; it is intentionally separate from the Bureau of Minor Grievances and AI Matrix Map properties.

## What's inside

- `index.html` — the entire site. Vanilla HTML/CSS/JS, no build, no deps.
- 1000 press responses (IDs 1–1000, stable — do not renumber), 7 escalation acts with rare early "leaks" woven throughout.
- 19 achievements, escalation director (3px nudge, `please stop` title, supervisor saga, expunged click, flips, shakes, spins, flashes, warps, hides, shape-morphs, rainbow, jitter, footer log). The button goes feral after 200 and hatches at 1000.
- Global counter via `countapi.mileshilliard.com` with silent fictional fallback (always pretends global, seed 8,392,114).

## Growing to 1000

Messages live in the `MESSAGES v1` block in `index.html`. Append `{id:201, act:N, rare:0|1, text:"..."}` — engine, shuffle-bag, and achievements need no code changes.

Swap the counter backend by editing the two `CONFIG` values at the top of the script.
