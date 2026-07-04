# Freddy the Foot 🦶🤙

**[freddythefoot.com](https://freddythefoot.com)** — the front door to the **24/7 Club**.

Freddy is our Al Bundy: a middle-aged man (early 50s) living with type 2 diabetes,
king of the recliner, lovable grump. He complains the entire time — and does it
anyway. The grumble is the relatability; the compliance is the quiet punchline.

> "I love my recliner. Why? My feet do."

Freddy is the **member-facing** face of the ecosystem. The deep clinical content
lives at **[OpenDiabetic](https://opendiabetic.org)** — Freddy just gets people
through the front door with a smile that leaves a real reminder:
**one clinical risk → one habit → one adventure.**

## Repo layout

| Path | What |
|---|---|
| `index.html` | The landing page — single self-contained file (CSS Freddy + WebGL upgrade). Served at the site root. |
| `brand/FREDDY_BRAND_KIT.md` | Character bible + brand law (v1.3). **Feed this to any generator before producing a Freddy asset — if an asset contradicts the doc, the doc wins.** |
| `brand/FREDDY_EPISODES.json` | Season 1 — "The 24/7 Club" — 10 episodes (machine-readable). |
| `brand/FREDDY_VIDEO_SPEC.md` | Per-episode short/video production spec. |

## Deploy — Cloudflare Pages

Static site. No build step.

- **Framework preset:** None
- **Build command:** *(none)*
- **Build output directory:** `/` (repo root — `index.html` is at root)
- **Production branch:** `main`
- **Custom domain:** `freddythefoot.com` (added in the Pages project → Custom domains)

Every push to `main` auto-deploys. External deps (Google Fonts, three.js CDN)
load at runtime from their CDNs — nothing to bundle.

---
_A Swarm & Bee / OpenDiabetic production · #SmartFeet #247Club · 🤙_
