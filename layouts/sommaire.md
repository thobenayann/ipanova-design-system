# Layout : Sommaire

**Référence visuelle :** slide 2

---

## Objectif
Présenter la structure du deck avec des numéros de sections lisibles et mémorisables.

---

## Structure visuelle

```
┌───────────────────────────────────────────────────────────┐
│ ▬  SOMMAIRE                         ·  [diag top-right]   │
│                                   ·                       │
│                                                           │
│    [01]  Titre section 1   [02]  Titre section 2   [03]  │
│    Texte label             Texte label              Titre │
│                                                           │
│                                                           │
│                    [04]  Titre section 4   [05]  Titre   │
│                          Texte label                      │
│ [diag bottom-left]                                        │
└───────────────────────────────────────────────────────────┘
```

---

## Spécifications

### Fond
- Blanc `#FFFFFF`
- Pas de bandeau de section

### Titre "SOMMAIRE"
- Style : `h1-section-divider` (Poppins Black 900, 56pt, UPPERCASE)
- Couleur : `dark (#333333)`
- Position : **haut-gauche**, avec une ligne horizontale fine (`dark`, 2pt) à sa gauche
- Alignement : gauche

### Ghost numbers (01, 02, 03...)
- Poppins Black 900, ~220pt
- Couleur : `ghost (#CCCCCC)`, opacité **35%**
- Position : le numéro est en arrière-plan, le texte label vient **se superposer par-dessus**
- Un ghost number par section

### Labels de section
- Style : Poppins Bold 700, 20-24pt
- Couleur : `dark (#333333)`
- Position : centré sur le ghost number correspondant, légèrement en bas
- Max 3 mots par label (ex. "Présentation IPANOVA", "Notre offre")
- Pas de numéro répété dans le texte (le ghost number suffit)

### Disposition des sections
- **3 sections max sur la ligne du haut**, **2-3 sur la ligne du bas**
- Distribution aérée — les items ne se touchent pas
- L'alignement est libre (pas de grille stricte) pour créer du mouvement

### Éléments décoratifs
- **Diagonales coin haut-droit** : 2-3 barres obliques en `primary` et `secondary`, épaisseur ~10pt
- **Diagonales coin bas-gauche** : même traitement, reflet diagonal
- **2 teal dots** : positionnés librement dans la zone haute

---

## Ce qu'on ne fait PAS

- ❌ Numérotation textuelle répétée ("Section 01")
- ❌ Bullets ou tirets dans les labels
- ❌ Fond coloré
- ❌ Icônes dans le sommaire
- ❌ Plus de 6 sections
