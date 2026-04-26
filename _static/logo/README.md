# CoarseAIR logo — v9 (current, circular badge)

**v9 pivot (2026-04-21):** the rectangular "comic panel" background of
v7/v8 was the reason the design kept reading as a *scene* instead of
a *mark*. v9 replaces it with a **circular badge** — the standard
container for software product marks (MATLAB, Ubuntu, PyTorch, …) —
and trims the interior to the minimum needed to signal "QCT on a
coloured PES":

- Thick navy ring around a sky-blue disc (keeps the user-approved
  coloured background, but in a round frame).
- Inside the badge: the coloured 3D PES (teal → deep blue → orange
  → red along the reaction coordinate), slightly rotated; a single
  golden trajectory with a subtle navy halo; and just two cartoon-
  sphere atoms (reactant blue, product red).
- Everything is clipped to the circle so nothing spills out.
- A bold **CoarseAIR** wordmark sits to the right (horizontal) or
  below (portrait).

If the circular frame still isn't "logo enough", possible v10
directions are documented at the bottom of this file.

---

# CoarseAIR logo — v8 (solver brand mark, rectangular panel)

**v8 change (2026-04-21):** v7 felt more like an illustrated reaction
diagram than a product mark. v8 strips the narrative elements and
recentres the design on the icon itself:

- **Dropped:** the N₂+N / N₃ / N+N+N tag labels, the chunky arrows
  between them, and the molecular-structure icons (diatomic +
  triangular + spread atoms).
- **Kept:** the sky-blue comic-panel background (user-approved),
  the coloured 3D rotated PES landscape (teal → deep blue → orange
  → red along the reaction coordinate), the chunky navy front-ridge
  outline with a lighter back-ridge for perspective, and the set
  of four depth ribs.
- **New hero element:** a single **golden trajectory** with a soft
  navy halo that flows across the surface (reactants → well →
  plateau); the trajectory alone carries the "QCT" reading without
  needing labels.
- **Three cartoon-sphere atoms** (blue, gold, red) positioned on the
  trajectory at the reactant, well, and plateau points — just
  enough to anchor the surface's three regions without turning into
  a diagram.

The end result reads as a software brand mark: distinctive icon,
clean composition, confident wordmark; still recognisably "PES + QCT"
to anyone in the field.

---

# CoarseAIR logo — v7 (cartoon, narrative-heavy)

**v7 change (2026-04-21):** kept v6's colour palette and the N₃
reaction-coordinate narrative, but pushed the visual language toward
a **cartoon / comic-panel** style per the user's preference:

- **Sky-blue rounded-rectangle background** brought back — the whole
  icon sits in a comic panel with a dashed "ground line" at the
  bottom.
- **Chunky bold outlines** (4.5–5 px) on the PES ridge, plus a
  lighter 2.5 px back profile for 3D depth.
- **Cartoon spherical atoms** with radial-gradient highlights
  (white-hot top-left → mid colour → dark base) and soft drop
  shadows, sized generously so each atom cluster reads as a
  character.
- **Chunky curved arrows** (stroke + triangular head) narrating the
  reaction flow: N₂ + N → descend into N₃ well → climb to 3 N
  plateau.
- **Tag-style labels** (white rounded pills with navy borders)
  beneath / above each atom cluster — **N₂ + N**, **N₃**,
  **N + N + N** — in the colour of the respective region of the PES.
- Colour coding along the reaction coordinate is unchanged: teal
  (reactants) → deep blue (N₃ well) → orange (climb) → red
  (plateau).

The square / portrait file mirrors the same composition stacked on
top of the wordmark, matching the aspect ratio of the user's
reference images.

---

# CoarseAIR logo — v6

**v6 change (2026-04-21):** adds three things the user asked for on
top of v5 —
(a) the PES is now slightly rotated (≈20° isometric tilt) via a back
    "ribbon" profile offset +30 px right / −22 px up from the front
    profile, filled between by a coloured gradient;
(b) the surface is coloured along the reaction coordinate, with a
    user-approved palette — teal (reactant valley) → deep blue
    (N₃ well) → amber (climbing flank) → red (3-atom plateau);
(c) the iconography now narrates the **N₃ dissociation pathway**:
    N₂ + N entering from the left, the bent N₃ complex at the deep-
    well bottom (middle), and N + N + N separated atoms on the
    upper-right plateau, each with a matching label.

A pale-cream trajectory traces the reaction path through the three
configurations, and the deep-blue wireframe mesh (front profile,
back profile, vertical ribs, one mid-surface stripe) keeps the
academic look.

---

# CoarseAIR logo — v5

**v5 change (2026-04-21):** guided by the user's `CoarseAIR_V1_Logo.png`
and `CoarseAIR_V2.png` references (a mountain-range PES with orbital
trajectories winding through it and coloured atoms riding on the
paths), v5 keeps the same *structural* concept — 3D PES + reactive
trajectory + coloured atoms — but renders it in a clean academic
style instead of the references' fantasy / cosmic aesthetic:

- **No glow, no sparkles, no radial gradients, no cosmic background.**
- Pure solid-colour wireframe for the PES (5 W-shaped isometric
  slices + 5 vertical ribs), in HERMES deep blue with opacity
  increasing front-to-back.
- Single amber-red trajectory curve threading the saddle; three
  atoms — reactant (amber-red), transition state (amber-gold),
  product (deep blue) — mark the key points.
- Clean Helvetica-Neue wordmark (no italic / script); the
  "Quasi-Classical Trajectory Solver" tagline from the references
  was dropped on request — "CoarseAIR" alone carries the wordmark
  and the wordmark size was bumped up to fill the saved space.

The portrait / square layout file mirrors the reference images' own
stacked composition (icon on top, wordmark beneath); the horizontal
layout works for doc-site headers where the space budget is tight.

---

# CoarseAIR logo — v1 (notes retained for reference)

Two SVG files, hand-written and immediately usable in a browser,
Sphinx docs, or a LaTeX `\includegraphics` (via the `svg` package).

- **`coarseair_logo_horizontal.svg`** (620 × 160) — wide wordmark
  with a triatomic molecule + QCT trajectory arc on the left.
  Use in website headers and doc banners.
- **`coarseair_logo_square.svg`** (120 × 120) — square badge with
  rounded-square deep-blue background and white molecule + arc
  inside. Use as favicon, GitHub repo avatar, or the corner mark on
  slides / posters.

## Design rationale (and how it differs from the dmsAIR logo)

Both HERMES codes share the same colour palette and the same bent
triatomic-molecule icon so they read as a family; the differentiator
is the *dynamical* element drawn on top of the molecule:

| Logo | Extra icon element | Represents |
|---|---|---|
| **dmsAIR** | Three amber velocity streaks entering from the left | The DSMC collision event — kinetic-theory sampling of incoming particles. |
| **CoarseAIR** | A single amber arc looping over and past the molecule, with an arrowhead | A quasi-classical trajectory being integrated on the PES — the core computation CoarseAIR performs. |

Common palette:

| Element | Colour | Notes |
|---|---|---|
| "Coarse" / "dms" | `#1f3b5a` | HERMES Aerospace deep blue. |
| "AIR" | `#c92a2a` | Hypersonic heating / shock-layer red. |
| Side atoms | `#1f3b5a` | Matches the deep-blue half of the wordmark. |
| Central atom | `#c92a2a` | Matches the amber-red half of the wordmark. |
| Trajectory arc | `#c92a2a` | Visual link between the icon motion and the "AIR" wordmark. |

## Previewing

- **Any browser** — open the SVG file directly.
- **Sphinx** — in `docs/online-documentation/conf.py`:

  ```python
  html_logo    = "_static/logo/coarseair_logo_horizontal.svg"
  html_favicon = "_static/logo/coarseair_logo_square.svg"
  ```

  The horizontal logo appears in the Read the Docs sidebar; the square
  version becomes the browser-tab favicon. No further file copying
  needed.

- **Raster export** — one-liner via ImageMagick or Inkscape:

  ```bash
  convert -density 300 coarseair_logo_horizontal.svg coarseair_logo.png
  inkscape --export-type=png --export-dpi=300 coarseair_logo_horizontal.svg
  ```

## Variations to ask for

If you want alternates, common directions include:

1. **Monochrome** — pure white-on-blue or black-on-white, for journal
   figures and stickers.
2. **Coarse-grained-level variant** — a ladder of horizontal lines
   beside the molecule (hinting at the "coarse-graining" of the
   rovibrational ladder) instead of a trajectory arc.
3. **Narrower aspect ratio** — banner-strip version for document
   headers (e.g. 1000 × 160).
4. **Typography match** to the University of Glasgow / UCI brand
   guidelines if you have them.
5. **Side-by-side pair logo** — CoarseAIR and dmsAIR together, for
   the shared HERMES landing page.

Tell me which direction to refine and I'll produce a v2.
