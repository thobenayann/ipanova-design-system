# Layout : Numbered Steps (Étapes numérotées avec pills)

**Référence visuelle :** slide 15 (Étude de cadrage de l'entrepôt)

---

## Objectif
Détailler 3 à 4 étapes d'une méthodologie ou d'un processus avec bullets par étape.

---

## Structure visuelle

```
┌──────────────────────────────────────────────────────────────┐
│                                              [logo]          │
│                                                              │
│   [image ronde]   TITRE PRINCIPAL                            │
│   [coin haut-g]   EN GRAS AVEC TEAL  ·                      │
│                                                              │
│   ─────────────────────────────────────────── (ligne points)│
│                [sous-titre accroche centré]                  │
│   ─────────────────────────────────────────── (ligne points)│
│                                                              │
│   [PILL ÉTAPE 1] [01] [hexaIcon] • bullet 1                 │
│                                  • bullet 2                 │
│                          ✦ Conclusion italique teal          │
│                                                              │
│   [PILL ÉTAPE 2] [02] [hexaIcon] • bullet 1                 │
│                                  • bullet 2                 │
│                          ✦ Conclusion italique teal          │
│                                                              │
│   [PILL ÉTAPE 3] [03] [hexaIcon] • bullet 1          [›]   │
│                                                              │
│   [PILL ÉTAPE 4] [04] [hexaIcon] • bullet 1                 │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

## Spécifications

### Logo
- Top-right standard

### Image ronde (haut-gauche)
- Cercle ~120pt de diamètre
- Bordure `primary (#51bdcb)`, 3pt
- Image : contexte pertinent pour le sujet

### Titre
- Style `h1-slide`, gauche-aligné, mots en teal
- Peut prendre 2-3 lignes pour ce layout (titre long admis)

### Ligne séparatrice
- Pointillés fins `primary (#51bdcb)`, pleine largeur
- 1 ligne au-dessus du sous-titre, 1 ligne en-dessous

### Sous-titre accroche
- Poppins SemiBold, 15-16pt, centré, dark
- Max 12 mots, phrase nominale

### Lignes d'étapes (chaque row)

#### Pill (label de catégorie)
- Fond `primary (#51bdcb)`, texte blanc, arrondi 6-8px
- Poppins SemiBold, 13pt
- Largeur : ~200pt, hauteur ~28pt
- Texte : nom de l'étape en gras (ex. "Analyse de l'existant")

#### Numéro
- Poppins Black, 36-42pt, couleur `ghost (#CCCCCC)` opacité 60%
- Centré dans sa zone

#### Icône hexagonale
- Hexagone fond `primary`, icône blanche
- Taille ~56pt

#### Bullets
- Poppins Regular 13pt, dark
- **Mots clés en gras** dans les bullets
- Max 3 bullets par étape
- Alignement : à droite de l'icône

#### Ligne de conclusion
- Style `tagline-italic` : Poppins Bold Italic, 13pt, `primary (#51bdcb)`
- En retrait sous les bullets
- Max 1 ligne

### Chevron
- Droite, milieu
- Standard

---

## Ce qu'on ne fait PAS

- ❌ Plus de 4 étapes (trop dense)
- ❌ Pills de largeurs différentes
- ❌ Bullets sans au moins 1 mot en gras
- ❌ Conclusion italic sans être en teal
