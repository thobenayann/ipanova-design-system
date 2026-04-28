# Slide 03 — Section Divider (Présentation Ipanova)

**Layout :** `section-divider`  
**Fichier source :** `../3.png`

---

## Aperçu visuel

```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│  01                    ┌──────┐  ┌──────┐                   │
│  PRÉSENTATION          │photo │  │photo │  ← hexagones      │
│  ipanova               └──────┘  └──────┘                   │
│                              ┌──────┐                        │
│                              │photo │                        │
│                              └──────┘                        │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Ghost number | "01" — Poppins Black 900, ~180pt, dark `#333333` opacité ~15%, haut-gauche |
| Titre ligne 1 | "PRÉSENTATION" — Poppins Black 900, ~52pt, dark `#333333`, UPPERCASE |
| Titre ligne 2 | "ipanova" — Poppins ou logo, ~48pt, teal `#51bdcb` |
| Photos | 3 photos dans des **hexagon-frames** (contour teal `#51bdcb`, pas de fond coloré) |
| Disposition photos | 2 hexagones en haut-droit décalés + 1 en bas, arrangement en triangle |
| Fond slide | Blanc pur |

---

## Tokens appliqués

- Titre section : `colors.dark` (`#333333`)
- Titre couleur : `colors.primary` (`#51bdcb`)
- Hexagon frames : contour `colors.primary`, fond = photo

---

## Points de vigilance

- Sur cette slide, l'hexagone sert de **cadre photo** (pas d'icône) — usage exceptionnel
- Le ghost number "01" est en dark, pas en teal — cohérent avec la numérotation de section
- Pas de section banner (c'est un divider de section)
- La composition est asymétrique : texte à gauche, photos empilées à droite
