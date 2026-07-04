# FREDDY SHORTS — VIDEO PRODUCTION SPEC v1.2
Consumes: `FREDDY_BRAND_KIT.md` v1.2 + `FREDDY_EPISODES.json` v1.2.
v1.2: The Sigh cold-open, Peg VO layer, recliner set continuity. Format lock otherwise carries from v1.1 (9:16, 18–28s, Social Cut only, ≤10 words/caption, no exclamation points on deadpan).

---

## 1. THE 4-BEAT STRUCTURE v1.2 (maps 1:1 to `voice_247.beats`)

| Beat | Time | Content | Source |
|---|---|---|---|
| **The Sigh** | 0–5s | Freddy already exhausted by the premise. Cold-open grumble IS the hook | `beats[0]` (+`video_hook` as text overlay) |
| **The Bit** | 5–12s | Punchline caption lands. 1.5s hold minimum after | `beats[1]`, `punchline` |
| **Grumble-then-comply** | 12–21s | Freddy does the habit WHILE complaining. Optional Peg beat lands here | `beats[2]`, `peg_beat` |
| **End card** | 21–27s | Reminder → "24/7 club. Check first. 🤙" + tags + Foot Guide logo | `reminder` + Template C |

## 2. PEG VO LAYER (new)
- Peg is AUDIO ONLY + optional doorway silhouette. Never fully on camera — running gag, production-cheap, protects continuity
- Her line: 2–6 words, slightly off-mic, from another room. Rendered on screen in her own caption style: `tiedye-purple` pill, ALL CAPS
- Rhythm is law: **Peg line → Freddy deadpan to camera → cut.** Three beats. Never four. Freddy's response ≤8 words
- Not every episode needs the Peg beat in the VIDEO cut — use when it's the strongest 5 seconds (ep04, ep05, ep09 mandatory; others optional)

## 3. SET CONTINUITY
- **The recliner is the franchise set.** `sunset-coral` body, `denim-fade` cushions, duct-tape patch always on the LEFT arm. Identical render every appearance
- Recliner appears in ≥50% of Season 1 videos (ep04 is the flagship recliner episode). Audiences should recognize the chair before they read a word
- The dog appears near/on the chair whenever Freddy leaves it. Never acknowledged in dialogue after ep05 — pure background gag

## 4. AUDIO
- Bed: classic-rock-adjacent royalty-free, drops OUT for The Sigh (silence sells exhaustion), returns on The Bit
- Freddy VO: gravelly, dry, put-upon warmth. The sigh itself is an audio asset — record once, reuse as the show's sonic logo
- NO laugh track in shipped cuts (reads fake on social). The "studio audience" lives on the landing page only

## 5. CLAUDE DESIGN HANDOFF PROMPT v1.2 (paste-ready)

```
You are designing for the Freddy the Foot brand (OpenDiabetic / Swarm & Bee AI).

CONTEXT FILES (attached, read first, they are law):
1. FREDDY_BRAND_KIT.md v1.3 — CHARACTER CANON (§2.0 is law), age markers (§2.1),
   grump persona, GRUMP CEILING (§2.3), disclosure doctrine (§2.7),
   Peg co-lead rules, recliner set spec, IP hygiene (§11 is law)
2. FREDDY_EPISODES.json v1.3 — 10 episodes with peg_beat + set + character_canon

CANON: Freddy is a middle-aged man (early 50s) LIVING WITH TYPE 2 DIABETES —
a member of the 24/7 club, not a mascot outside it. Age is pinned in geometry:
salt-and-pepper brows, graying outer toe-crown, sturdier settled build, reading
glasses, laugh lines, NO blush. If a render could pass for a children's-brand
mascot, it FAILS. Target: beloved sitcom lead, not cereal box.
His diabetes is matter-of-fact — never the punchline, never explained.

PERSONA: the lovable grump. Freddy complains the entire time — and does it
anyway. Every bit opens with The Sigh (already exhausted by the premise).
Grumble targets the ROUTINE, never the diagnosis, never Peg, never the club.
Default expression: one brow up, mouth flat. Smiles are earned, not default.

PEG: off-screen voice / doorway silhouette ONLY. Never fully shown.
Her captions: tiedye-purple pill, ALL CAPS, 2–6 words.
Rhythm: Peg line → Freddy deadpan to camera → cut. Three beats.

THE RECLINER: sunset-coral body, denim-fade cushions, duct-tape patch on
LEFT arm. Identical in every appearance. This is the franchise set.

TASK — build for episode {epNN}:
1. Four-beat static (Sigh / Bit / Grumble-then-comply / End card) — 4:5
2. Tip card — 1:1
3. Video storyboard — 4 frames per FREDDY_VIDEO_SPEC.md v1.2 §1 — 9:16
4. Video end card — 9:16

HARD CONSTRAINTS:
- Copy from voice_247 fields VERBATIM. No exclamation points on deadpan lines
- Punchline first, reminder only on the end card
- IP HYGIENE: archetype only. Zero references to real sitcoms, characters,
  actors, catchphrases, or recognizable sets. If it reads as a specific show
  rather than "classic sitcom energy," it fails
- Sign-off every asset: "24/7 club. Check first. 🤙" + Foot Guide lockup
- All v1.1 bans carry (banned words, no fear-red, no real injury photos)

OUTPUT: files per Brand Kit naming (ep{NN}_247_4beat.png, etc.)

Start with ep04 (Nightly Address) — the flagship recliner episode and the
thesis line: "I love my recliner. Why? My feet do."
Then ep05 (3AM), then ep02 (dad shoes).
```

## 6. LAUNCH ORDER CHANGE (v1.2)
**ep04 leads now, not ep05.** Reasons: it plants the franchise set (the recliner), carries the thesis line, and establishes the Peg rhythm in its purest form ("I HEARD THE RECLINER. DID YOU CHECK?" / "...I was already checking."). ep05 follows as the viral swing, ep02 third. The chair is the brand — build it first.

*"I love my recliner. Why? My feet do."* — 24/7 club. Check first. 🤙
