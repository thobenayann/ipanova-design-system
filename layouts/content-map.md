# Layout : Content Map (Visuel central + texte bas)

**Référence visuelle :** slide 4 (Notre présence mondiale)

---

## Objectif
Présenter un visuel fort (carte, schéma, graphique) accompagné d'une analyse textuelle en bas de slide.

---

## Structure visuelle

```
┌──────────────────────────────────────────────────────────────┐
│ ██████ LABEL SECTION ██████████████████████████████████████  │
│                                                              │
│         TITRE PRINCIPAL EN GRAS  AVEC ACCENT TEAL           │
│                                                              │
│  ┌──────────────────────────────────────────────────────┐   │
│  │                                                      │   │
│  │              [VISUEL CENTRAL]                        │   │
│  │        (carte, diagramme, schéma)                    │   │
│  │                                                      │   │
│  └──────────────────────────────────────────────────────┘   │
│                                                              │
│  [icône]  Titre insight                                      │
│           Texte avec mots en **gras** et en  teal           │
│           Deuxième paragraphe si nécessaire.                 │
│                                                       [n°]  │
└──────────────────────────────────────────────────────────────┘
```

---

## Spécifications

### Bandeau de section
- Fond `banner (#555555)`, pleine largeur
- Label uppercase, white, letterspacing 3px
- Pas de logo top-right dans ce layout (le label bandeau suffit)

### Titre
- Style `h1-slide`, centré, UPPERCASE
- Mots clés en teal
- Position : immédiatement sous le bandeau

### Zone visuelle centrale
- Occupe ~55% de la hauteur de slide
- Fond blanc ou légèrement gris (`#F5F5F5`)
- Le visuel peut être : carte SVG/PNG, diagramme, infographie
- Annotations sur le visuel : logo ipanova small + texte bold + dash pointillé vers pin 📍
- Pins de localisation : couleur `primary (#51bdcb)`
- Lignes de connexion entre pins : dash `primary`, opacité 60%

### Zone texte bas
- Max 2 paragraphes
- **Icône** : ~48pt, style goal/target, couleur `primary`
- **Titre insight** : Poppins Bold, 18-20pt, dark
- **Corps** : Poppins Regular, 14pt, dark
  - Certains mots en gras **dark** pour les concepts clés
  - Certains mots en **primary teal** pour les bénéfices/valeurs
- Numéro de page : bas-droite

---

## Règles de lisibilité

- Ne pas surcharger le visuel central avec du texte
- Max 2 annotations sur la carte/visuel
- La zone texte bas ne doit pas dépasser 4 lignes totales

---

## Ce qu'on ne fait PAS

- ❌ Visuel qui déborde hors de sa zone
- ❌ Plus de 2 paragraphes en bas
- ❌ Annotations textuelles trop longues sur le visuel
- ❌ Logo top-right en compétition avec le bandeau de section
