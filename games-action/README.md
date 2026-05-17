# Games-Action Photo Library

**Purpose:** Raw photographs of Barcelona Games games being played on Platja del Fòrum. These are the source assets for:
1. New marketing posts (IG, ads, stories) — each photo stands on its own as a feed image
2. Higgsfield video generation — each photo becomes a 3–5 s animated clip; clips combine into montage videos

**These are RAW photos (no text overlay).** If you want a poster version with title baked in, see `../games/`.

---

## Naming convention

```
{game-slug}_{variant}.png
```

- `game-slug` — matches `/public/games/` (e.g. `water-balloon-volleyball`, `seated-beach-tug-of-war`)
- `variant` — `a` / `b` (each game has 2 variants for visual variety)

Example: `water-balloon-volleyball_a.png`, `water-balloon-volleyball_b.png`

---

## Target library (20 photos)

| Slug | Variant a | Variant b |
|---|---|---|
| `water-balloon-volleyball` | Wide team mid-toss, balloon airborne | Close-up catchers in towel, sand spraying |
| `seated-beach-tug-of-war` | Wide both teams pulling, rope taut | Low-angle anchor man straining, face strained |
| `bucket-brigade-splash-relay` | Wide chain of 6, water arcing between | Final bucket dump moment, water exploding |
| `human-carry-obstacle-course` | Stretcher-carry under obstacle | Hand-off moment between teams |
| `blindfold-beach-maze` | Centered blindfolded runner, teammates shouting | Maze overhead view |
| `back-to-back-ball-bounce` | Two pairs racing, balls between backs | Single pair leaning into each other |
| `clothes-peg-relay` | Faceoff close-up, pegs on lips | Wide relay line |
| `cone-to-cone-catch-relay` | Mid-throw, ball airborne | Diving catch on sand |
| `pass-the-cup` | Two players blowing balloons against cup | Group reaction laughing |
| `tunnel-ball` | Wide tunnel of legs, ball rolling | Final player about to grab ball |

Total: **20 photos** when complete.

---

## How to fill this folder

For each empty slot:

1. Open the prompt library: `/marketing/photo-gen-prompts.md`
2. Find the matching prompt for the game + variant
3. Paste into ChatGPT image gen (or Midjourney / DALL-E / Higgsfield Image)
4. Generate 2–3 takes, pick the best one
5. Save here with the correct filename
6. Tell me "added water-balloon-volleyball_a" and I'll catalogue it in the marketing campaign

---

## Status

Track the build in `_status.md` (created automatically once the first photo lands).
