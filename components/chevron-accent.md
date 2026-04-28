# Composant : Chevron Accent

---

## Description
Forme décorative en chevron (>) utilisée comme séparateur visuel ou indicateur de flux entre étapes. Renforce la directionnalité et le dynamisme des layouts process.

---

## Structure

```
    ╱|
   ╱ |
  ╱  |
 ╱   |    →  direction de lecture (gauche → droite)
  ╲  |
   ╲ |
    ╲|
```

---

## Spécifications

### Chevron de séparation (process-timeline)
| Propriété | Valeur |
|---|---|
| Forme | Triangle isocèle pointant à droite |
| Largeur | 18-24pt |
| Hauteur | 48-64pt (calquée sur la hauteur des blocs étapes) |
| Couleur | `primary (#51bdcb)` |
| Opacité | 100% |
| Fond | Transparent |

### Chevron décoratif de fond (cover, section-divider)
| Propriété | Valeur |
|---|---|
| Forme | Grand chevron partiel (hors-cadre) |
| Couleur | `primary (#51bdcb)` opacité 10-15% |
| Position | Débordant sur le bord droit ou gauche de la slide |
| Taille | 200-400pt |

---

## Variantes

| Variante | Couleur | Usage |
|---|---|---|
| Séparateur actif | `#51bdcb` plein | Entre étapes de process-timeline |
| Décoratif fond | `#51bdcb` 12% opacité | Fond cover ou section-divider |
| Micro-accent | `#51bdcb` plein, 10pt | Avant un label de liste (alt. au bullet) |

---

## Règles de positionnement

- Entre deux blocs d'étapes : centré verticalement, espacement 8-12pt de chaque côté
- Le chevron décoratif ne doit jamais masquer du texte
- Maximum 1 chevron décoratif de fond par slide

---

## Ce qu'on ne fait PAS

- ❌ Chevron dark sur fond dark
- ❌ Chevrons multiples comme séparateurs sur un même slide (max 4 entre 5 étapes)
- ❌ Chevron pointant vers le haut ou le bas (orientation exclusive : gauche→droite)
- ❌ Remplir le chevron décoratif à 100% d'opacité (trop lourd visuellement)
