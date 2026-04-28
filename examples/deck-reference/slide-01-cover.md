# Slide 01 — Cover

**Layout :** `cover`  
**Fichier source :** `../1.png`

---

## Aperçu visuel

```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│         ┌──────────────────────────────────┐                │
│         │  PRÉSENTATION                    │  [photo bg]    │
│         │                                  │                │
│         │  ipanova                         │                │
│         │                         dernière révision : date  │
│         └──────────────────────────────────┘                │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Fond | Photo pleine slide (réunion/mains/tablette), filtre léger |
| Cadre central | Rectangle blanc semi-transparent avec **bordure teal** (`#51bdcb`) 2-3pt |
| Titre | "PRÉSENTATION" — Poppins Black, ~48pt, dark `#333333`, UPPERCASE |
| Sous-titre | "ipanova" — logo ou typo Poppins, ~52pt, teal `#51bdcb`, minuscule stylisée |
| Date | "dernière révision : JJ-MM-AAAA" — Poppins Regular, ~11pt, dark, aligné bas-droit du cadre |

---

## Tokens appliqués

- Couleur titre : `colors.dark` (`#333333`)
- Couleur sous-titre/logo : `colors.primary` (`#51bdcb`)
- Police : `typography.families.primary` = Poppins
- Graisse titre : `typography.weights.black` = 900

---

## Points de vigilance

- Le cadre central n'est **pas pleine largeur** — il laisse la photo visible sur les bords
- La photo de fond doit rester reconnaissable (pas de filtre trop opaque)
- Pas de section banner sur cette slide
- Pas de logo séparé — "ipanova" EST le titre/logo ici
