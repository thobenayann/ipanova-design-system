# Layout : Process Timeline (Processus horizontal)

**Référence visuelle :** slide 14 (Accompagnement bout en bout SAP EWM)

---

## Objectif
Représenter un processus séquentiel de 4 à 6 étapes avec flèches de progression.

---

## Structure visuelle

```
┌───────────────────────────────────────────────────────────────┐
│ [BANDEAU SECTION GRIS]                           [logo]       │
│                                                               │
│    TITRE PROCESSUS EN GRAS  MOTS CLÉS EN TEAL                │
│                                                               │
│   ·                                                           │
│  [hexa]  ──►  [hexa]  ──►  [hexa   [hexa]  ──►  [GO LIVE]   │
│                            fork ►] [hexa]                     │
│                                                               │
│  ÉTAPE 1    ÉTAPE 2       ÉTAPE 3  ÉTAPE 4    ÉTAPE 5        │
│  Titre      Titre         Titre    Titre       Titre          │
│  · detail   · detail      · detail · detail    · detail       │
│  · detail   · detail      · detail · detail    · detail       │
└───────────────────────────────────────────────────────────────┘
```

---

## Spécifications

### Bandeau de section
- Pleine largeur, fond `banner (#555555)`
- Label uppercase white centré
- Pas de numéro de page sur cette slide (slide plein contenu)

### Logo
- Top-right, standard

### Titre
- Style `h1-slide`, **centré**, mots clés en teal
- Peut prendre 2 lignes si nécessaire

### Flèches de processus
- Flèches larges `primary (#51bdcb)` et `secondary (#006688)` en alternance
- Hauteur des flèches : ~60pt
- Direction : gauche → droite
- Peuvent se bifurquer (flèche centrale se divisant en 2) pour des processus parallèles

### Icônes de processus
- Hexagone fond `primary (#51bdcb)`, icône line-art blanche
- Taille : ~80-100pt
- Position : au-dessus des flèches

### Labels d'étape
- Label principal : Poppins Black 700, 16-18pt, UPPERCASE, dark
- Sous-label gras : Poppins Bold, 13-14pt, dark
- Détails : Poppins Regular, 12-13pt, dark (max 3 lignes)
- Mots clés en **gras** dans les détails

### Marqueur GO/LIVE
- Badge rond "GO" : fond `dark`, texte white, ~30pt
- Point "LIVE" : dot `primary`, connexion verticale en pointillés
- Ligne pointillée verticale après le marqueur (séparation phase maintenance)

### Point décoratif
- 1 dot `primary` à gauche du premier hexagone

---

## Règles de séquence

- **Minimum 3 étapes**, **maximum 6 étapes**
- Si > 5 étapes : réduire la taille des labels ou scinder en 2 slides
- Les étapes de la 2ème ligne (maintenance, support) peuvent être en retrait visuel

---

## Ce qu'on ne fait PAS

- ❌ Flèches fines (elles doivent être larges et visuellement fortes)
- ❌ Icônes sans hexagone
- ❌ Plus de 3 lignes de détail par étape
- ❌ Couleurs autres que primary/secondary pour les flèches
