# Composant : Hexagon Frame (Cadre hexagonal)

---

## Description
Conteneur hexagonal utilisé pour encadrer les icônes dans les layouts process-timeline, numbered-steps et deliverables. Donne une cohérence visuelle forte et un caractère distinctif aux blocs d'icônes.

---

## Structure

```
      ╱‾‾‾‾‾╲
     ╱         ╲
    │    icon    │
     ╲         ╱
      ╲_____╱
```

---

## Spécifications

### Hexagone
| Propriété | Valeur |
|---|---|
| Forme | Hexagone régulier (flat-top ou pointy-top selon contexte) |
| Fond | `primary (#51bdcb)` |
| Taille standard | 64×64pt |
| Taille compact | 48×48pt (layouts denses) |
| Bordure | Aucune |
| Ombre | Aucune |

### Icône intérieure
| Propriété | Valeur |
|---|---|
| Style | Line-art outline, épaisseur 1.5-2pt |
| Couleur | `white (#FFFFFF)` |
| Taille | 28-32pt (dans hexagone 64pt) |
| Taille compact | 20-24pt (dans hexagone 48pt) |
| Alignement | Centré horizontal + vertical |

---

## Variantes

| Variante | Usage | Taille |
|---|---|---|
| Standard | process-timeline, numbered-steps | 64pt |
| Compact | deliverables, content-icon-list dense | 48pt |
| Outline | Accent décoratif sans icône (rare) | 32pt, fond transparent, contour teal 2pt |

---

## Règles d'usage

- L'hexagone est **toujours teal** (`#51bdcb`) — jamais dark ou white comme fond principal
- Une seule icône par hexagone
- Ne pas superposer du texte sur l'hexagone
- En layout numbered-steps, le numéro d'étape remplace l'icône (voir ghost-number pour les chiffres décoratifs de fond)

---

## Ce qu'on ne fait PAS

- ❌ Hexagone avec fond `dark (#333333)` ou `secondary (#006688)`
- ❌ Icône filled (pleine) — toujours outline
- ❌ Hexagone sans icône ni numéro à l'intérieur
- ❌ Mélanger hexagone et carré arrondi sur la même slide
