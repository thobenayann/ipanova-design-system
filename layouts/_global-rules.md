# Règles globales de composition — Ipanova Slides

## Principe fondateur

> Une slide = un message. Si tu ne peux pas résumer la slide en 6 mots, c'est trop chargé.

---

## Règles de titre (H1)

Tous les titres de slides de contenu suivent la même structure :

```
PARTIE NOIRE EN GRAS  PARTIE TEAL EN GRAS
```

- **Jamais tout en noir** → au moins un mot ou groupe de mots en `primary (#51bdcb)`
- **Jamais tout en teal** → le noir ancre, le teal accentue
- Maximum 2 lignes. Si 3 lignes, réduire la taille ou couper le titre.
- Les titres H1 de contenu sont en UPPERCASE ExtraBold.
- La partie teal porte le mot **le plus fort sémantiquement** du titre.

**Exemples corrects :**
- `MAXIMISEZ VOTRE` **`PERFORMANCE`** `AVEC DES OUTILS` **`DIGITAUX ADAPTÉS`**
- `POURQUOI EWM TRANSFORME LA` **`SUPPLY CHAIN`**
- `DE LA` **`CONCEPTION INITIALE`** `AU` **`SUPPORT OPÉRATIONNEL`**

---

## Logo

- Toujours **en haut à droite** sur les slides de contenu
- Jamais centré, jamais en bas
- Sur fond sombre (closing, split dark) : version blanche
- Sur fond clair : version `secondary (#006688)`
- Le logo comporte deux points caractéristiques (un teal au-dessus du 'i', un teal en dessous du 'a')

---

## Fond de slide

| Type de slide | Fond |
|---|---|
| Cover | Photo plein format + overlay blanc semi-transparent |
| Sommaire | Blanc `#FFFFFF` |
| Section divider | Blanc `#FFFFFF` |
| Contenu standard | Blanc `#FFFFFF` ou `#FAFAFA` |
| Split panel gauche | Photo avec overlay sombre `rgba(0,0,0,0.55)` |
| Closing | Photo plein format, split 50/50 |

---

## Hiérarchie de couleur

1. `dark (#333333)` → texte, titres
2. `primary (#51bdcb)` → accent, 1 mot dans le titre, icônes, bordures
3. `secondary (#006688)` → logo, profondeur, variante sombre
4. `white (#FFFFFF)` → texte sur fond sombre uniquement
5. `ghost (#CCCCCC à 35%)` → éléments décoratifs en arrière-plan

**Règle des 3 :** Jamais plus de 3 couleurs actives par slide (hors décoratifs).

---

## Éléments décoratifs — règles d'usage

### Teal dots
- Max **3 dots** par slide
- Tailles variées (ne pas mettre 3 dots identiques)
- Ne pas placer sur du texte

### Chevron (>)
- **1 seul** par slide
- Position : droite (milieu-bas ou centre)
- Couleur : `primary (#51bdcb)`
- Usage : slides de contenu à liste (icon-list, numbered-steps, deliverables)

### Diagonales décoratives
- Uniquement sur slide **Sommaire** (coins)
- Couleur : alternance `primary` et `secondary`
- Jamais sur les slides de contenu

### Ghost numbers (01, 02...)
- Uniquement sur **Sommaire** et **Section Divider**
- Poids : Black 900, taille 200-280pt, opacité 35%
- Le titre texte se superpose volontairement

---

## Densité de contenu

| Zone | Limite |
|---|---|
| Titre H1 | Max 10 mots |
| Sous-titre accroche | Max 12 mots |
| Label icon-block | Max 5 mots |
| Description icon-block | Max 2-3 lignes (40 mots max) |
| Tagline italic | Max 8 mots |
| Bullet point | Max 1 ligne (15 mots) |
| Quote block | Max 2 lignes (25 mots) |

---

## Interdit absolu

- ❌ Bullets dans un titre
- ❌ Plus de 4 items dans une liste icon-block (3 est idéal)
- ❌ Deux éléments identiques de même couleur en teal côte à côte
- ❌ Fond coloré plein (hors photo) sur une slide de contenu
- ❌ Texte en rouge, orange ou vert (hors icônes partenaires SAP)
- ❌ Bordures ou ombres sur les text boxes
- ❌ Gradient artificiel sur le texte
- ❌ Alignement aléatoire — tout est soit left-aligned soit center-aligned, jamais mixé sur une même slide
