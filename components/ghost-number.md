# Composant : Ghost Number (Chiffre fantôme)

---

## Description
Grand chiffre en arrière-plan, très peu opaque, utilisé comme repère visuel décoratif pour les slides à étapes numérotées. Crée une hiérarchie spatiale et renforce la narration séquentielle sans alourdir la slide.

---

## Structure

```
  ┌─────────────────────────────────┐
  │                                 │
  │  "0 1"  ← ghost, fond, opaque  │
  │  [contenu actif par-dessus]     │
  │                                 │
  └─────────────────────────────────┘
```

---

## Spécifications

| Propriété | Valeur |
|---|---|
| Police | Poppins Black 900 |
| Taille | 180-240pt |
| Couleur | `primary (#51bdcb)` |
| Opacité | 8-12% |
| Contenu | Chiffre arabe (01, 02, 03…) ou numéro simple |
| Alignement | Aligné sur le bord droit ou gauche selon layout |
| Z-index | Toujours derrière tout le contenu |

---

## Positionnement

| Layout | Position du ghost number |
|---|---|
| numbered-steps | Derrière le titre de l'étape, décalé en bas à droite |
| process-timeline | Optionnel, sous le titre de chaque colonne d'étape |
| section-divider | Grand chiffre de section, centré ou à droite |

---

## Règles d'usage

- Un seul ghost number par slide (ou un par colonne d'étape si layout multi-colonnes)
- Le ghost number ne doit jamais distraire : opacité max 12%
- Le contenu actif (texte, hexagone, icône) doit être clairement lisible par-dessus
- Préférer le format "01" (deux chiffres) au "1" pour l'alignement visuel

---

## Ce qu'on ne fait PAS

- ❌ Ghost number à plus de 15% d'opacité (trop présent)
- ❌ Ghost number en dark (`#333333`) sur fond blanc — masque le contenu
- ❌ Chiffre en Poppins Regular — doit impérativement être Black 900
- ❌ Ghost number centré en plein milieu de la slide (interfère avec la lecture)
- ❌ Utiliser des lettres au lieu de chiffres dans ce composant
