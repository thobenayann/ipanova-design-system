# DESIGN.md — Ipanova Presentation System

> **How to use this file:** Drop it into any LLM context alongside a generation brief. It contains every token, rule, and rationale needed to produce on-brand Ipanova slides without guesswork. The file is self-contained — no need to read other files in this repo unless you want deeper reference.

**Brand essence:** Ipanova is a French SAP & digital consulting firm. Slides must feel expert yet human — structured, clean, and confident without being cold. The teal accent is the brand's heartbeat; it appears on every slide, on the words that matter most.

---

## Section 1 — Visual Theme & Atmosphere

**Tone:** Professional confidence with human warmth. Clean white surfaces, strong typographic hierarchy, controlled teal accents. Never clinical, never playful — always intentional.

**Density:** Medium. Each slide carries one clear message. Content is structured in scannable blocks (icon + label + description), never in dense paragraphs.

**Mood references:**
- Cover: cinematic stillness — large bold type on a photographic background
- Content slides: editorial clarity — generous whitespace, systematic grid
- Section dividers: bold and declarative — number + title, no clutter
- Closing: warm and personal — split panel with photo and contact info

**Signature visual moves:**
1. **Bicolor title** — Every main heading splits between `dark (#333333)` and `primary (#51bdcb)`. The key word(s) go teal. Always UPPERCASE.
2. **Hexagon icon frame** — Every icon lives in a teal hexagon. Never bare icons on white.
3. **Ghost number** — Large `200–280pt` Poppins Black numeral in the background at 8–12% opacity, behind step-based content.
4. **Teal italic tagline** — Each service block closes with a short italic sentence in teal. It's the promise.
5. **Section banner** — A `36pt` gray bar at the top of every content slide labels the current section.

---

## Section 2 — Color Palette & Roles

```css
/* Ipanova — Core Palette */
--color-primary:     #51bdcb;   /* Teal — the brand accent. Icons, highlighted words, taglines, arrows, dots */
--color-secondary:   #006688;   /* Deep blue — logo lettering, decorative diagonals, depth accents */
--color-dark:        #333333;   /* Near-black — all body text, titles (dark half), labels */
--color-light:       #FAFAFA;   /* Off-white — standard slide background */
--color-white:       #FFFFFF;   /* Pure white — text on dark backgrounds */
--color-banner:      #555555;   /* Mid-gray — section banner background */
--color-ghost:       #CCCCCC;   /* Very light gray — ghost numbers (+ 35% opacity) */
--color-light-teal:  #B8E8EE;   /* Pale teal — decorative diagonal shapes, subtle gradients */

/* Semantic roles */
--color-background:       var(--color-light);
--color-text-primary:     var(--color-dark);
--color-text-on-dark:     var(--color-white);
--color-accent:           var(--color-primary);
--color-accent-deep:      var(--color-secondary);
--color-surface-banner:   var(--color-banner);
--color-surface-icon:     var(--color-primary);
--color-decorative-ghost: var(--color-ghost);
```

**Why these roles exist:**
- `primary` does all the visual work of "this matters" — it should never appear on more than 20–25% of a slide's surface
- `secondary` is reserved for structural brand elements (logo, large diagonal shapes) — not for text
- `dark` is not pure black (#000) because pure black feels harsh in projection; #333 reads as authoritative without aggression
- `banner` (#555555) creates a clear reading zone at the top without competing with content

**Color combinations that work:**
| Foreground | Background | Usage |
|---|---|---|
| `white` | `dark` | Closing left panel, section banner text |
| `white` | `primary` | Icon in hexagon, badge GO LIVE |
| `primary` | `white` | Tagline text, accent words in title |
| `dark` | `light` | Standard body text |
| `dark` | `light-teal` (5–8%) | Info box backgrounds, step headers |

---

## Section 3 — Typography Rules

**Single font family:** `Poppins` (Google Fonts). No other typeface. The logo uses a custom variant — never recreate it with Poppins.

```
Font import: https://fonts.google.com/specimen/Poppins
Weights used: 400 (Regular), 600 (SemiBold), 700 (Bold), 800 (ExtraBold), 900 (Black)
```

### Type Scale

| Role | Weight | Size | Case | Color | Notes |
|---|---|---|---|---|---|
| Cover title | Black 900 | 72–96pt | UPPERCASE | `dark` | First word or phrase in `primary` |
| Section divider H1 | Black 900 | 56–72pt | UPPERCASE | `dark` + `primary` | Number prefix at 15% opacity |
| Slide H1 | ExtraBold 800 | 36–48pt | UPPERCASE | `dark` + `primary` | Key word(s) always in `primary` |
| Slide subtitle | SemiBold 600 | 16–20pt | Sentence | `dark` | 1–2 lines max, under H1 |
| Section banner label | Bold 700 | 12–14pt | UPPERCASE | `white` | Letter-spacing 3–4px |
| Icon block label | Bold 700 | 16–18pt | Sentence | `dark` | |
| Body text | Regular 400 | 13–15pt | Sentence | `dark` | Line-height 1.5, max 3 lines |
| Body bold (inline) | Bold 700 | 13–15pt | Sentence | `dark` | Key terms only, 1–3 per block |
| Tagline italic | Bold Italic 700 | 13–15pt | Sentence | `primary` | Closing promise per block |
| Ghost number | Black 900 | 200–280pt | — | `ghost` at 8–12% | Behind content |
| Page number | Bold 700 | 13–14pt | — | `white` on `dark` square | 28×28pt badge |
| Caption / date | Regular 400 | 11–12pt | Sentence | `dark` | Metadata only |

### Title Construction Rule

Every H1 on a content slide follows this exact pattern:
```
[FIRST PART IN DARK]  [KEY WORD(S) IN TEAL]
```
Examples:
- "MAXIMISEZ VOTRE **PERFORMANCE**" → MAXIMISEZ VOTRE in dark, PERFORMANCE in teal
- "**PARTENAIRE** DE PROXIMITÉ" → PARTENAIRE in teal, rest in dark
- "LES **LIVRABLES** DU CADRAGE" → LIVRABLES in teal

**Rule:** The teal word is always the strategic noun — the thing the slide is about. Never teal the verb.

---

## Section 4 — Component Stylings

### Section Banner
```
Height:         36pt
Background:     #555555 (banner)
Text:           Poppins Bold 700, 12–14pt, UPPERCASE, white, letter-spacing 3px
Padding left:   60pt
Position:       Top of slide, full width
Page badge:     28×28pt dark square, right-flush, page number in white Bold 14pt
Appears on:     All content slides — NOT on cover, sommaire, section-divider, closing
```

### Hexagon Icon Frame
```
Shape:          Regular hexagon (pointy-top or flat-top)
Background:     #51bdcb (primary)
Size standard:  64pt
Size compact:   48pt (dense layouts)
Icon inside:    Outline white, 28–32pt, centered
Style rule:     NEVER filled icons — always line-art outline
Use:            Every icon-block in every layout
```

### Icon Block
```
Structure:      [Hexagon] + [Label bold] + [Body text] + [Tagline italic teal]
Label:          Poppins Bold 700, 16–18pt, dark
Body:           Poppins Regular 400, 13–14pt, dark, max 3 lines
Tagline:        Poppins Bold Italic, 13–14pt, primary (#51bdcb), max 8 words
Gap hex→label: 16pt
Gap label→body: 6pt
Max per slide:  6 (content-split) or 4 (content-icon-list standard)
```

### Quote Block
```
Background:     #333333 (dark)
Text:           Poppins SemiBold Italic 600, 14–16pt, white
Border left:    4pt solid primary (#51bdcb)
Padding:        20–24pt
Width:          60–100% of available zone
Usage:          Closing statement on numbered-steps, deliverables, section conclusions
```

### Left-Border Item (Deliverables list)
```
Border left:    4pt solid primary (#51bdcb)
Padding left:   16pt
Label:          Poppins Bold 700, 14–15pt, dark
Body:           Poppins Regular 400, 12pt, dark
Gap between:    20pt
```

### Chevron Accent (Decorative)
```
Shape:          Right-pointing angular chevron (>)
Color:          primary (#51bdcb), full or at 12–15% opacity
Size standard:  60×80pt (between process steps)
Size decorative: 200–400pt (corner crop, 12% opacity)
Usage:          Process separators, corner decoration bottom-right
```

### Ghost Number
```
Font:           Poppins Black 900
Size:           120–280pt (context-dependent)
Color:          primary (#51bdcb) at 8–12% opacity — OR ghost (#CCCCCC) at 35% for sommaire
Position:       Behind title, slight offset top-left
Rule:           One per cell or zone, never more than 4 per slide
```

### Teal Dots
```
Diameter:       10–18pt individual dots
Color:          primary (#51bdcb)
Opacity:        20–35% as group
Arrangement:    Strict orthogonal grid only (never scattered randomly)
Max:            One zone of dots per slide (typically 3×3 to 5×5)
Usage:          Corner accent, usually top-right or bottom-right
```

### Logo Ipanova
```
Variants:       Color (teal + dark blue) | Black mono | White mono
Cover:          Color, top-left, 120–160pt wide, margin 40pt/32pt
Content slides: Color, top-right, 72–88pt wide, margin 40pt/20pt
Closing:        Color or white, center or center-top
Clear space:    Height of "i" on all sides — nothing enters this zone
```

---

## Section 5 — Layout Principles

### Slide Canvas
```
Format:         16:9
Dimensions:     1280 × 720pt
Safe margins:   Top 48pt | Bottom 40pt | Left 60pt | Right 60pt
```

### Layout Catalog

| Layout name | When to use | Key structure |
|---|---|---|
| `cover` | First slide only | Photo bg + centered frame + title + logo |
| `sommaire` | Agenda slide | Ghost numbers grid (2–3 cols), no banner |
| `section-divider` | Between sections | Large number + title left, hexagon photos right |
| `content-split` | Photo + content | 35% photo left / 65% content right |
| `content-icon-list` | Service overview | 2×2 icon-block grid, optional photo strip |
| `content-map` | Geographic presence | Full-width map image + bottom expertise block |
| `process-timeline` | Step-by-step flow | 4 columns + chevron arrows + top/bottom context |
| `numbered-steps` | 4-step methodology | 2×2 grid, ghost numbers, info boxes |
| `deliverables` | Output listing | Infographic left + left-border list right + quote |
| `closing` | Last slide | 50/50 split — dark panel left + photo right + contact |

### Grid System
```
Column count:   12-column conceptual grid
Gutter:         24pt between columns of content
Icon-block gap: 24–28pt between blocks
Process step:   ~22% width each (4-step layout)
Split ratio:    35/65 for photo/content (never 50/50 on content slides)
```

### Spacing Scale
```
xs:   8pt   — gap between icon and label
sm:   16pt  — gap between label and body, padding left-border
md:   24pt  — gap between icon blocks, section gutter
lg:   40pt  — margin bottom slide, margin right logo
xl:   60pt  — margin left content, section banner padding
2xl:  80pt  — margin top content area (under banner)
```

---

## Section 6 — Depth & Elevation

Ipanova slides are intentionally **flat** — no drop shadows, no 3D effects. Depth is created through:

### Layering Hierarchy (back to front)
```
Layer 0 (deepest):  Photo background (cover, split panels)
Layer 1:            Decorative elements (teal dots, chevrons, diagonal shapes)
Layer 2:            Ghost numbers (8–12% opacity)
Layer 3:            Background surfaces (info boxes, column headers at 5–8% teal)
Layer 4:            Main content (text, icon blocks)
Layer 5 (front):    Accent elements (hexagon frames, quote blocks, badges)
```

### Surface Tokens
```
slide-bg:         #FAFAFA — primary slide surface
info-box-bg:      #51bdcb at 6–8% opacity — subtle teal tint for callout boxes
step-header-bg:   #51bdcb at 12–15% opacity — column headers in process slides
quote-bg:         #333333 — opaque dark for high-contrast quote blocks
split-dark-panel: #333333 — closing slide left panel
banner-bg:        #555555 — section banner bar
```

### What replaces shadows
- **Color contrast** between zones (dark panel vs. white content)
- **Teal border-left** (4pt) on list items to create visual hierarchy
- **Full-bleed photo** in split layouts creates natural depth separation
- **Ghost number opacity** gives spatial depth without visual noise

---

## Section 7 — Do's and Don'ts

### Typography
| ✅ DO | ❌ DON'T |
|---|---|
| UPPERCASE for all H1 titles | Sentence case titles |
| Split title: dark word + teal key word | Full title in one color |
| Teal on the strategic noun | Teal on verbs, prepositions, articles |
| 1 tagline italic per icon block | Multiple taglines, or non-italic taglines |
| Max 3 lines of body per block | 4+ lines or dense paragraphs |
| Poppins only | Any other typeface |

### Color
| ✅ DO | ❌ DON'T |
|---|---|
| Teal icon hexagons | Dark or white hexagons |
| White text on dark backgrounds | Dark text on dark backgrounds |
| Primary (#51bdcb) for taglines | Secondary (#006688) for taglines |
| Info boxes at 6–8% teal opacity | Solid teal info box backgrounds |
| One accent color per slide zone | Multiple accent colors competing |

### Layout & Composition
| ✅ DO | ❌ DON'T |
|---|---|
| Section banner on all content slides | Banner on cover, sommaire, section-divider, closing |
| Logo top-right on content slides | Logo centered on content slides |
| 4–6 icon-blocks max per slide | 7+ blocks on one slide |
| Ghost number behind content (z-index low) | Ghost number on top of content |
| One decorative dot zone per slide | Dots scattered all over the slide |
| Hexagon for icons | Bare icons without container |
| Photo in split left panel (~35%) | Photo taking more than 40% of slide width |

### Tone (from editorial guidelines)
| ✅ DO | ❌ DON'T |
|---|---|
| Active verbs: Maximisez, Accélérez, Construisons | Passive: "Il est possible de..." |
| Concrete metrics: "6,5M€", "100 consultants", "+20%/an" | Vague claims: "beaucoup", "très performant" |
| Short taglines: 6–8 words max | Long taglines spanning multiple lines |
| Client-centric: "votre", "vos projets" | Self-centered: "nous sommes les meilleurs" |
| Bicolor titles with strategic word in teal | All-teal titles, all-dark titles |

---

## Section 8 — Slide Density & Format Behavior

> Note: This section replaces "Responsive Behavior" from web design systems. Ipanova slides are fixed at 1280×720pt — there is no responsive breakpoint. Instead, this section governs density adaptation.

### Density Rules by Layout

| Layout | Max items | If more items needed |
|---|---|---|
| `content-icon-list` | 4 icon-blocks (2×2) | Use 2 slides, or reduce to compact 48pt hexagons |
| `content-split` | 6 icon-blocks | Beyond 6: split into 2 slides |
| `process-timeline` | 4 phases | 5 phases: reduce font to 11pt and remove taglines |
| `numbered-steps` | 4 steps (2×2) | 6 steps: use 3×2 grid, remove ghost numbers |
| `deliverables` | 4–5 items | 6+ items: split into 2 slides |
| `sommaire` | 5–6 sections | 7+: use 2-column list layout instead of ghost-number grid |

### Text Adaptation
```
Standard body:    13–15pt
Compact body:     11–12pt (dense slides only)
Minimum body:     11pt — never go below this for projection readability
Title standard:   36–48pt
Title compact:    32pt minimum
Taglines:         Can be omitted when space is critical (icon-block label + body only)
```

### Photo Usage
```
Cover:            Full-slide bleed photo with frame overlay
Content-split:    Left panel, 35% width, full height
Section-divider:  Hexagon-framed photos, right side, 3 photos max
Closing:          Right panel, 50% width, full height
Other layouts:    Decorative strip only (max 25% width, right side)
```

---

## Section 9 — Agent Prompt Guide

These are reusable prompts to give an LLM when generating Ipanova slides. Include this section alongside your brief.

### System context to always inject
```
You are generating slides for Ipanova, a French SAP and digital consulting firm.
Use this DESIGN.md as the authoritative source for all visual decisions.
The slide format is PowerPoint 16:9, 1280×720pt.
Font: Poppins only (Google Fonts).
Never deviate from the bicolor title rule: UPPERCASE, strategic noun in #51bdcb, rest in #333333.
```

### Prompt templates

**Generate a single slide:**
```
Generate a [LAYOUT_NAME] slide for Ipanova using DESIGN.md.
Topic: [TOPIC]
Key points: [BULLET LIST]
Section: [SECTION NAME FOR BANNER]
Page number: [N]
Output format: python-pptx code
```

**Generate a full deck:**
```
Generate an Ipanova presentation deck using DESIGN.md.
Deck title: [TITLE]
Sections: [LIST]
For each section include: 1 section-divider + 2–3 content slides.
Always start with cover + sommaire. Always end with closing.
Output: python-pptx code, one function per slide.
```

**Check compliance:**
```
Review this slide description against the Ipanova DESIGN.md.
Flag any deviations from: bicolor title rule, hexagon icon frames, section banner presence, font usage, color roles.
[SLIDE DESCRIPTION]
```

**Adapt an existing deck:**
```
Reformat the following content into Ipanova design system (DESIGN.md).
Choose the most appropriate layout for each slide from the layout catalog.
Maintain all factual content, only change structure and styling.
[CONTENT]
```

### Icon selection guide
Available icons in `images/icons/` — reference by filename:
- **People/org:** `user.png`, `team.png`, `org-chart.png`, `team-cycle.png`, `team-victory.png`, `graduate.png`
- **Values/relation:** `hand-heart.png`, `star-hand.png`, `high-five.png`, `chat.png`, `hands.png`
- **Technical/digital:** `gear-check.png`, `speedometer.png`, `puzzle.png`, `iot.png`, `innovation-cycle.png`
- **Logistics/sector:** `warehouse.png`, `clock.png`, `globe.png`
- **Research/goals:** `eye.png`, `search.png`, `target.png`

Always place icons inside a `64pt teal hexagon (#51bdcb)` with a `white outline` icon inside.

### Photo selection guide
Team photos available in `images/team-photos/` — use `INDEX.md` for context.
- **Cover/closing:** `portrait-arnaud-neon.jpg`, `detail-business-card-hands.jpg`
- **Content-split left panel:** `team-meeting-3people-laptop.jpg`, `consultant-headset-logo-wall.jpg`, `team-women-laptop-collaboration.jpg`
- **Developer/tech context:** `developer-woman-coding-screen.jpg`, `developer-woman-pointing-code.jpg`
- **Client references:** `client-mission-airbus-india-team.jpg`

---

## Quick Reference Card

```
Slide size:      1280 × 720pt (16:9)
Font:            Poppins only
Title rule:      UPPERCASE | dark #333333 + primary #51bdcb (key noun)
Primary:         #51bdcb  — icons, accent words, taglines, arrows, dots
Secondary:       #006688  — logo, decorative diagonals
Dark:            #333333  — all text, panel backgrounds
Banner:          #555555  — section bar (36pt height)
Icon container:  Hexagon, fill #51bdcb, icon white outline
Ghost number:    Poppins Black, 200–280pt, primary at 8–12%
Tagline:         Poppins Bold Italic, teal, ≤ 8 words, 1 per block
Max icon-blocks: 4 per standard slide, 6 per split slide
Section banner:  On ALL content slides, NEVER on cover/sommaire/divider/closing
```
