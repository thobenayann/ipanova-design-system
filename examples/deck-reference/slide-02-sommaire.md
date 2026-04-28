# Slide 02 — Sommaire

**Layout :** `sommaire`  
**Fichier source :** `../2.png`

---

## Aperçu visuel

```
┌──────────────────────────────────────────────────────────────┐
│ SOMMAIRE                           [•] [chevrons coin dr]   │
│ ─────                                                        │
│                                                              │
│   01          02          03                                 │
│   Présentation Notre offre Notre partenariat SAP             │
│   IPANOVA                                                    │
│                                                              │
│              04                  05                          │
│              Empreinte Aéro      Nos clients                 │
│              IPANOVA                                         │
│                                                              │
│ [chevrons coin bg]                                           │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Titre | "SOMMAIRE" — Poppins Black 900, ~56pt, dark `#333333`, UPPERCASE |
| Trait sous titre | Ligne horizontale `primary (#51bdcb)`, 3pt, ~120pt de long |
| Ghost numbers | "01" à "05" — Poppins Black 900, ~180pt, gris clair `#CCCCCC` ou `#DDDDDD`, opacité ~30% |
| Labels sections | Poppins Bold 700, ~22pt, dark `#333333` |
| Disposition | Grille 3 colonnes haut + 2 colonnes décalées bas (quinconce) |
| Teal dots | 2 points teal visibles en haut centre-droit |
| Chevrons déco | Grands chevrons dark/teal en coins bas-gauche et haut-droit |

---

## Tokens appliqués

- Ghost numbers : `colors.dark` très atténué ou `#CCCCCC`
- Trait accent : `colors.primary` (`#51bdcb`)
- Labels : `typography.weights.bold` = 700

---

## Points de vigilance

- Les ghost numbers **sont derrière** les labels (z-index bas)
- La grille n'est pas parfaitement régulière : 3 en haut, 2 en bas décalés vers le centre-droit
- Les chevrons décoratifs débordent légèrement hors de la slide (crop volontaire)
- Pas de section banner sur cette slide
