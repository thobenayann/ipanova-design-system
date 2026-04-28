# Layout : Cover (Slide de couverture)

**Référence visuelle :** slide 1 (présentation générale)

---

## Objectif
Slide d'ouverture. Pose l'identité visuelle, le titre du deck et la date de révision.

---

## Structure visuelle

```
┌─────────────────────────────────────────────────┐
│  [Photo de fond plein format — filtrée neutre]  │
│                                                 │
│  ┌─────────────────────────────────────────┐    │
│  │  [Cadre blanc semi-transparent]         │    │
│  │                                         │    │
│  │         TITRE DU DECK                   │    │
│  │                                         │    │
│  │         ipanova  ·                      │    │
│  │                                         │    │
│  │                   dernière révision :   │    │
│  │                   JJ-MM-AAAA            │    │
│  └─────────────────────────────────────────┘    │
└─────────────────────────────────────────────────┘
```

---

## Spécifications

### Fond
- Photo plein format (bleed complet)
- Filtre : luminosité réduite à ~80%, légère désaturation
- Thème photo : contexte professionnel neutre (réunion, collaboration, bureau)

### Cadre central
- Rectangle blanc, opacité **85%**
- Bordure : `primary (#51bdcb)`, épaisseur **3pt**
- Marges du cadre par rapport au bord slide : **80pt** gauche/droite, **100pt** haut/bas
- Pas de shadow

### Titre
- Style : `cover-title` (Poppins Black 900, 72-96pt, UPPERCASE)
- Couleur : `dark (#333333)`
- Alignement : **centré**
- Position : haut-milieu du cadre
- Le titre ne contient PAS d'accent teal sur la cover (exception à la règle H1)

### Logo ipanova
- Taille : ~100pt de hauteur
- Couleur : `secondary (#006688)`
- Alignement : **centré**
- Position : milieu du cadre, sous le titre
- Les deux points caractéristiques sont en `primary (#51bdcb)`

### Date de révision
- Style : Poppins Bold, 14pt
- Format : `dernière révision : JJ-MM-AAAA`
- Position : bas-droite **à l'intérieur** du cadre
- Couleur : `dark (#333333)`

---

## Règles d'adaptation

- Le titre change selon le deck (ex. "PRÉSENTATION IPANOVA", "OFFRE IA", "PROPOSITION SAP EWM")
- La photo de fond peut être remplacée selon le contexte (tech, aéronautique, manufacturing...)
- La date de révision est **toujours présente** sur la cover
- Ne pas ajouter d'autres éléments sur la cover

---

## Ce qu'on ne fait PAS

- ❌ Titre en teal sur la cover
- ❌ Logo agrandi ou décentré
- ❌ Photo trop sombre (texte illisible)
- ❌ Fond uni à la place de la photo
- ❌ Ajout d'un sous-titre ou d'un slogan
