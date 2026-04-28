# Slide 11 — Closing (Merci)

**Layout :** `closing`  
**Fichier source :** `../17.png`

---

## Aperçu visuel

```
┌──────────────────────────────────────────────────────────────┐
│                          │                  ipanova   2026   │
│  ○ ○ ○ ○  Merci          │                                   │
│                          │           [photo mug ipanova]    │
│  pour l'opportunité de   │                                   │
│  présenter notre         │  ┌──────────────────────────────┐│
│  expertise.              │  │  ARNAUD GOULLEY              ││
│  Nous sommes pleinement  │  │  +33 (0)6.61.45.71.32  📞   ││
│  engagés à répondre…     │  │  https://www.ipanova.com  🌐 ││
│                          │  │  2 impasse Louis Pueyo   📍  ││
│  [fond dark #333333]     │  │  31700 BLAGNAC            ││
│                          │  └──────────────────────────────┘│
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Split vertical | 50/50 — gauche dark, droite photo |
| Panneau gauche fond | `dark (#333333)` |
| Dots décoratifs | 4 cercles blancs (○ ○ ○ ○) en haut-gauche du panneau dark |
| Titre "Merci" | Poppins Bold 700, ~44pt, white, à droite des dots |
| Texte corps | Poppins Regular 400, ~13pt, white, 4-5 lignes |
| Panneau droit fond | Photo produit/ambiance (mug Ipanova sur table) |
| Logo + année | Ipanova blanc mono + année en haut-droit du panneau photo |
| Flèche déco | Flèche blanche vers le bas, côté droit du panneau photo |
| Bloc contact | Fond blanc/semi-transparent, bas-droit, Poppins Regular 12pt |
| Contact nom | Poppins Bold 700, ~15pt, dark |
| Contact détails | Poppins Regular 12pt, dark, avec icônes téléphone/web/localisation |

---

## Tokens appliqués

- Panneau gauche : `colors.dark` (`#333333`)
- Texte panneau gauche : `colors.white` (`#FFFFFF`)
- Logo panneau droit : variante blanche
- Contact nom : `typography.weights.bold`

---

## Points de vigilance

- Le split est strictement **50/50** (pas de photo partielle comme sur content-split)
- Les 4 dots décoratifs sont un motif signature de la closing — à conserver systématiquement
- L'année figure explicitement sur cette slide (en haut à côté du logo)
- La flèche vers le bas suggère une ouverture/invitation à la discussion
- Pas de section banner sur cette slide
