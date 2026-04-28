# Composant : Teal Dots (Motif de points teal)

---

## Description
Motif décoratif composé de petits cercles teal en grille régulière. Élément de texture visuelle utilisé en fond ou en accent sur certains layouts pour rompre l'homogénéité du blanc et apporter de la profondeur sans alourdir.

---

## Structure

```
  •  •  •  •  •
  •  •  •  •  •
  •  •  •  •  •
  •  •  •  •  •
```

---

## Spécifications

### Dot individuel
| Propriété | Valeur |
|---|---|
| Forme | Cercle parfait |
| Diamètre | 4-6pt |
| Couleur | `primary (#51bdcb)` |
| Espacement entre dots | 12-16pt (centre à centre) |

### Groupe de dots
| Propriété | Valeur |
|---|---|
| Disposition | Grille orthogonale (alignement strict) |
| Opacité du groupe | 20-35% |
| Zone couverte | Coin ou bande latérale (jamais toute la slide) |
| Position typique | Coin bas-droit, coin haut-gauche, bord droit |

---

## Variantes d'usage

| Variante | Position | Opacité | Nb de dots |
|---|---|---|---|
| Accent de coin | Coin bas-droit | 25% | 4×4 à 5×5 |
| Bande latérale | Bord droit, hauteur partielle | 20% | 3 cols × 8-10 rows |
| Fond section | Derrière un bloc de texte | 15% | 6×6 |

---

## Règles d'usage

- Les dots sont **toujours en fond** (z-index bas) — jamais par-dessus du texte ou des icônes
- Limité à **une zone de dots par slide**
- Ne pas rendre les dots trop opaques : ils doivent rester discrets
- Sur fond coloré (section-divider), utiliser les dots en blanc (#FFFFFF) à 15% opacité

---

## Ce qu'on ne fait PAS

- ❌ Dots dark (`#333333`) ou secondary (`#006688`)
- ❌ Dots aléatoirement dispersés (la grille est stricte)
- ❌ Dots couvrant plus de 30% de la surface de la slide
- ❌ Dots en avant-plan sur du contenu
- ❌ Dots de taille variée sur le même groupe
