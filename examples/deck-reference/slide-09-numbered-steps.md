# Slide 09 — Numbered Steps (Étude de cadrage)

**Layout :** `numbered-steps`  
**Fichier source :** `../15.png`

---

## Aperçu visuel

```
┌──────────────────────────────────────────── [logo] ──────────┐
│                                                              │
│  ÉTUDE DE CADRAGE DE                                        │
│  L'ENTREPÔT                                                 │
│  Une démarche structurée pour sécuriser votre trajectoire   │
│                                                              │
│  ┌─────────────────────────────┐  ┌─────────────────────┐  │
│  │  "01" [ghost]               │  │  "02" [ghost]       │  │
│  │  [⬡] Analyse de l'existant  │  │  [⬡] Principes...  │  │
│  │      (AS-IS)                │  │                     │  │
│  │  • bullet 1                 │  │  • bullet 1         │  │
│  │  • bullet 2                 │  │  • bullet 2         │  │
│  │  💡 info box teal           │  │  💡 info box teal   │  │
│  └─────────────────────────────┘  └─────────────────────┘  │
│  ┌─────────────────────────────┐  ┌─────────────────────┐  │
│  │  "03" [ghost]               │  │  "04" [ghost]       │  │
│  │  [⬡] Analyse des écarts     │  │  [⬡] Dimension-    │  │
│  │  • bullet 1                 │  │      nement         │  │
│  │  💡 info box                │  │  💡 info box        │  │
│  └─────────────────────────────┘  └─────────────────────┘  │
│                              [quote box bas-droit]          │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Pas de section banner | Slide sans bandeau (cohérent avec intro de séquence) |
| Logo | Ipanova couleur, haut-droit |
| Titre | "ÉTUDE DE CADRAGE DE" dark → "L'ENTREPÔT" teal, UPPERCASE, 2 lignes |
| Sous-titre | Poppins Regular ~13pt, dark, 1 ligne |
| Grille | 2 colonnes × 2 lignes = 4 étapes numérotées |
| Ghost numbers | "01" à "04" — Poppins Black 900, ~120pt, teal `#51bdcb` opacité ~10% |
| Hexagone | Teal 48pt avec icône outline blanche, haut-gauche de chaque cellule |
| Label étape | Poppins Bold 700, ~16pt, dark |
| Bullets | Poppins Regular 12pt, dark, 3-4 par étape |
| Mots gras | Termes clés en Poppins Bold dans les bullets |
| Info box | Fond teal très pâle (`#e8f7f9`), bord gauche teal 3pt, texte Poppins Regular 11pt |
| Quote box | Bas-droit, fond dark `#333333`, texte white, italic, ~180pt large |

---

## Tokens appliqués

- Ghost numbers : `colors.primary` à 10% opacité
- Info box fond : `colors.primary` à ~8% opacité
- Info box bordure : `colors.primary`
- Quote box fond : `colors.dark`

---

## Points de vigilance

- Le ghost number est **teal** (pas dark comme sur le sommaire) — cohérence avec les étapes
- L'info box en bas de chaque cellule est une **note contextuelle** (coût, contrainte, validation)
- La quote box est optionnelle — utilisée pour une synthèse ou citation forte
- 4 étapes = format idéal pour ce layout 2×2
