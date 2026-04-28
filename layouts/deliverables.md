# Layout : Deliverables (Livrables avec bordures colorées)

**Référence visuelle :** slide 16 (Les livrables du cadrage)

---

## Objectif
Lister des livrables, outputs ou catégories avec contenu structuré en sous-bullets.

---

## Structure visuelle

```
┌──────────────────────────────────────────────────────────────┐
│                                              [logo]          │
│                                                              │
│   [image ronde]   LES LIVRABLES DU CADRAGE                  │
│   [coin haut-g]                              · ·            │
│                                                              │
│                  [sous-titre accroche centré]                │
│                                                              │
│  ┌─────────┐  ┌─────────────────────────────────────────┐   │
│  │ Visuel  │  │ OPTIONNEL │ Titre livrable 1             │   │
│  │ géomét. │  │           │ • bullet sous-item           │   │
│  │ (triang)│  │           │ • bullet sous-item           │   │
│  │ avec    │  ├───────────┴──────────────────────────────┤   │
│  │ icônes  │  │ ████ Titre livrable 2                    │   │
│  │         │  │      • bullet                            │   │
│  │         │  │      • bullet                            │   │
│  │         │  ├──────────────────────────────────────────┤   │
│  │         │  │ ████ Titre livrable 3                    │   │
│  │         │  ├──────────────────────────────────────────┤   │
│  └─────────┘  │ ████ Titre livrable 4                    │   │
│               └──────────────────────────────────────────┘   │
│                                                              │
│  ❝ Citation de clôture en italique              [›]         │
└──────────────────────────────────────────────────────────────┘
```

---

## Spécifications

### Logo
- Top-right standard

### Image ronde + visuel géométrique (gauche)
- Cercle image haut-gauche : ~100pt, bordure `primary`, 3pt
- Visuel géométrique : triangle ou forme abstraite en dégradé `primary` / `secondary` / dark
- Icônes blanches à l'intérieur du visuel
- Largeur totale zone gauche : ~30%

### Titre
- Style `h1-slide`, aligné gauche-centre
- Mots clés en teal
- Taille réduite à 36-40pt (slide dense)

### Sous-titre accroche
- Poppins SemiBold, 15pt, centré sous le titre
- Max 12 mots

### Colonne droite : liste livrables
- Zone blanche avec léger fond `#F5F5F5` (optionnel)
- Chaque item :

#### Barre de bordure gauche
- Largeur : 4pt
- Couleur selon hiérarchie :
  - Optionnel / secondaire : `ghost (#CCCCCC)`
  - Principal : `primary (#51bdcb)`
  - Critique : `secondary (#006688)`
  - Conclusion : `dark (#333333)`
- Padding gauche : 16pt après la bordure

#### Label "OPTIONNEL"
- Texte vertical ou horizontal, style caption, uppercase
- Uniquement sur les items marqués comme optionnels

#### Titre du livrable
- Poppins Bold 700, 15-16pt, dark

#### Bullets
- Poppins Regular Italic, 13pt, dark
- *Italique pour les bullets dans ce layout*
- Max 3 bullets par livrable

### Quote block de clôture
- Voir composant `quote-block.md`
- Position : bas-gauche ou bas-centré
- Max 2 lignes

---

## Ce qu'on ne fait PAS

- ❌ Plus de 4 livrables
- ❌ Toutes les bordures de même couleur
- ❌ Bullets non-italiques dans ce layout
- ❌ Visuel géométrique omis (il ancre visuellement la colonne gauche)
