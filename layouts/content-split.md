# Layout : Content Split (2 colonnes photo/contenu)

**Référence visuelle :** slide 5 (Partenaire de proximité)

---

## Objectif
Présenter une identité, un profil, une offre synthétique. Le panneau photo ancre visuellement, la colonne droite délivre le contenu.

---

## Structure visuelle

```
┌──────────────────┬──────────────────────────────────────────┐
│ [BANDEAU SECTION]│                                          │
│                  │  [logo top-right]                        │
│  [Photo plein    │                                          │
│   panneau]       │  TITRE ACCROCHEUR EN TEAL                │
│                  │  ET EN NOIR                              │
│  ❝ citation      │                                          │
│    italique ❞    │  🔷 Label gras                           │
│                  │     Texte descriptif                     │
│  📍 AGENCES      │                                          │
│  Toulouse        │  🔷 Label gras                           │
│  Nantes          │     Texte descriptif                     │
│  Paris           │                                          │
│                  │  🔷 Label gras                           │
│  [logo SAP       │     Texte descriptif                     │
│   partner]       │                                  [n°]   │
└──────────────────┴──────────────────────────────────────────┘
```

---

## Spécifications

### Bandeau de section (haut gauche)
- Voir composant `section-banner.md`
- S'étend **uniquement sur la colonne gauche** OU sur toute la largeur selon variante

### Colonne gauche (35%)
- Photo plein bleed, overlay sombre `rgba(0,0,0,0.55)` sur la partie basse
- Contenu possible en overlay blanc :
  - Citation en italique gras blanc (avec guillemets décoratifs "❝❞" en teal)
  - Localisation : label "AGENCES" (Poppins Bold, uppercase, white) + liste villes (Regular, white)
  - Logos partenaires (SAP Partner badge)
- Pas de fond uni coloré dans la colonne gauche

### Colonne droite (65%)
- Fond blanc `#FFFFFF`
- Logo ipanova : top-right
- Titre : style `h1-slide` avec accents teal
- Liste d'items : format `icon-block` (voir composant)
  - 4-6 items maximum
  - Icône teal outline ~48pt
  - Label gras + description courte
- Numéro de page : bas-droite, style `page-number`

---

## Règle de densité

- Colonne droite : **max 5 items** icon-block
- Si 6 items ou plus → utiliser le layout `content-icon-list` à la place
- La colonne droite ne doit pas déborder visuellement

---

## Ce qu'on ne fait PAS

- ❌ Fond coloré uni dans la colonne gauche
- ❌ Photo dans la colonne droite
- ❌ Plus de 6 icon-blocks
- ❌ Titre dans la colonne gauche (sauf exception citation)
