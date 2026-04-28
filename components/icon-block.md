# Composant : Icon Block

---

## Description
Unité visuelle de base pour présenter un service, une fonctionnalité ou un bénéfice.

---

## Structure

```
[🔷] Label en gras
     Texte descriptif court, 2-3 lignes maximum, Poppins Regular.
     ✦ Tagline italique en teal (optionnel)
```

---

## Spécifications

### Icône
| Propriété | Valeur |
|---|---|
| Forme | Carré arrondi (border-radius 8pt) OU cercle OU hexagone |
| Fond | `primary (#51bdcb)` |
| Icône | Line-art blanche, style cohérent (outline, pas filled) |
| Taille | 48-64pt |

### Label
| Propriété | Valeur |
|---|---|
| Police | Poppins Bold 700 |
| Taille | 16-18pt |
| Couleur | `dark (#333333)` |

### Description
| Propriété | Valeur |
|---|---|
| Police | Poppins Regular 400 |
| Taille | 13-14pt |
| Couleur | `dark (#333333)` |
| Largeur max | ~450pt |
| Lignes max | 3 |

**Mots en gras dans la description :** Utiliser `Poppins Bold 700` pour les concepts clés (1 à 3 mots par ligne max).

### Tagline italique (optionnel)
| Propriété | Valeur |
|---|---|
| Police | Poppins Bold Italic 700 |
| Taille | 13-14pt |
| Couleur | `primary (#51bdcb)` |
| Format | Phrase courte, ~8 mots max |

---

## Variantes d'icône selon layout

| Layout | Forme icône |
|---|---|
| content-icon-list | Carré arrondi teal |
| content-split | Carré arrondi teal (outline style) |
| process-timeline | Hexagone teal |
| numbered-steps | Hexagone teal |
| deliverables | Hexagone teal (plus petit) |

---

## Ce qu'on ne fait PAS

- ❌ Icône sans fond coloré (pas d'icône teal sur fond blanc sans conteneur)
- ❌ Plus de 3 lignes de description
- ❌ Tagline non-italique
- ❌ Deux taglines par bloc
