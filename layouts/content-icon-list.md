# Layout : Content Icon List (Liste de services avec icônes et taglines)

**Référence visuelle :** slide 7 (Notre offre) et slide 12 (EWM Supply Chain)

---

## Objectif
Présenter 3 à 4 services, fonctionnalités ou bénéfices avec icônes, description et phrase d'accroche distinctive.

---

## Structure visuelle

```
┌────────────────────────────────────────────────────────────┐
│ [BANDEAU SECTION] [n°]                      [logo]        │
│                                                            │
│        TITRE EN GRAS AVEC MOT EN  TEAL                    │
│                                                            │
│  [hexagones  │  🔷 Label service                          │
│   photos     │     Texte de description normale.           │
│   gauche]    │     Deuxième ligne si nécessaire.            │
│              │     ✦ Tagline italique teal.                │
│              │                                            │
│              │  🔷 Label service                          │
│              │     Description.                           │
│              │     ✦ Tagline italique teal.                │
│              │                                            │
│              │  🔷 Label service                          │
│              │     Description.                    [›]    │
│              │     ✦ Tagline italique teal.                │
└────────────────────────────────────────────────────────────┘
```

---

## Spécifications

### Bandeau de section
- Voir composant `section-banner.md`
- Pleine largeur ou left-anchored selon variante

### Logo
- Top-right, version `secondary (#006688)`

### Titre
- Style `h1-slide`, centré, avec mots en teal
- Position : juste sous le bandeau, centré horizontalement

### Colonne gauche : hexagones photos
- 3 hexagones imbriqués en cascade verticale
- Bordure `primary`, 3pt
- Photos : contexte pertinent pour le service
- Largeur colonne : ~30%

### Colonne droite : liste d'items
- 3 à 4 items maximum
- Chaque item :
  - **Icône** : carré arrondi teal (~48pt), icône line-art blanche à l'intérieur
  - **Label** : Poppins Bold 700, 16-18pt, dark
  - **Description** : Poppins Regular, 13-14pt, dark, max 2-3 lignes
  - **Tagline** : Poppins Bold Italic, 13-14pt, `primary (#51bdcb)`
- Séparation entre items : espacement vertical ~24pt
- Largeur colonne : ~65%

### Chevron décoratif
- Position : droite, milieu-bas
- Couleur `primary (#51bdcb)`
- Taille ~70x80pt

### Points décoratifs
- 2 dots `primary`, positions libres (haut-droite zone)

---

## Variante sans tagline
Pour des slides plus sobres (ex. fonctionnalités techniques) :
- Supprimer la tagline italique
- Augmenter légèrement la description (+1 ligne)

---

## Ce qu'on ne fait PAS

- ❌ 5 items ou plus (passer à deux slides ou réduire)
- ❌ Tagline sans italique
- ❌ Icône sans fond teal (même si l'icône est teal)
- ❌ Description > 40 mots par item
