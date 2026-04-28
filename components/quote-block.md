# Composant : Quote Block (Bloc citation)

---

## Description
Citation d'expert, conclusion forte ou phrase-signature en bas de slide.

---

## Structure

```
❝❝ ────────────────
│  Texte de la citation en italique
│  sur une ou deux lignes maximum.
```

---

## Spécifications

### Guillemets décoratifs "66"
| Propriété | Valeur |
|---|---|
| Caractère | `"` (double quote stylisée) ou `❝` |
| Taille | 36-42pt |
| Couleur | `primary (#51bdcb)` |
| Position | Avant le texte, même ligne ou légèrement au-dessus |

### Ligne horizontale
| Propriété | Valeur |
|---|---|
| Style | Ligne fine 1-2pt |
| Couleur | `dark (#333333)` opacité 60% |
| Largeur | ~40pt |
| Position | À droite des guillemets, alignée au tiers haut du texte |

### Texte de citation
| Propriété | Valeur |
|---|---|
| Police | Poppins SemiBold Italic 600 |
| Taille | 14-16pt |
| Couleur | `dark (#333333)` |
| Lignes max | 2 |
| Mots max | 25 |

---

## Positionnement

- En bas de slide (bas-gauche ou bas-centré)
- Toujours en dehors de la liste de contenu principale
- Margin bottom : ~20pt
- Ne doit jamais être la seule information sur une slide

---

## Usage

- Slides `deliverables`, `numbered-steps`, `content-split` (bas)
- Contenu : synthèse de valeur, engagement, bénéfice client
- Le texte doit sonner comme une **promesse**, pas comme une description

**Exemple correct :**
> ❝ *Un cadrage structuré pour réduire les risques et objectiver la décision projet*

**Exemple incorrect :**
> ❝ *Nous proposons des livrables de cadrage*
