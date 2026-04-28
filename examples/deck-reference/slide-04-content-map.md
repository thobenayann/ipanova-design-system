# Slide 04 — Content Map (Présence mondiale)

**Layout :** `content-map`  
**Fichier source :** `../4.png`

---

## Aperçu visuel

```
┌─ NOTRE PRÉSENCE MONDIALE ────────────────────────────────────┐
│                                                              │
│   UNE OFFRE GÉOGRAPHIQUE ÉTENDUE                            │
│                                                              │
│  ┌────────────────────────────────────────────────────────┐ │
│  │                  [carte monde]                          │ │
│  │  ipanova USA •                   • ipanova France       │ │
│  │  Mobile                            Toulouse/Nantes/Paris│ │
│  └────────────────────────────────────────────────────────┘ │
│                                                              │
│  [icône]  Une expertise & des valeurs reconnues             │
│           Texte descriptif avec mots-clés en teal/rouge     │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Section banner | "NOTRE PRÉSENCE MONDIALE" — bandeau gris en haut |
| Titre | "UNE OFFRE GÉOGRAPHIQUE" dark + "ÉTENDUE" teal, UPPERCASE |
| Carte | Image de carte monde, ~70% de la hauteur slide, centrée |
| Pins localisation | Points teal avec labels "ipanova [lieu]" en Poppins Bold 10pt |
| Bloc bas | Fond légèrement différencié (blanc ou très léger gris) |
| Icône bloc | Hexagone teal avec icône outline blanche |
| Texte bas | Poppins Regular 13pt, mots-clés en teal et rose/rouge (accent) |

---

## Tokens appliqués

- Titre split : `colors.dark` + `colors.primary`
- Pins carte : `colors.primary` (`#51bdcb`)
- Mots-clés teal dans texte : `colors.primary`
- Mots-clés accentués (rose) : couleur d'accentuation secondaire (non documentée comme token principal)

---

## Points de vigilance

- La carte occupe une large portion — le texte bas doit rester lisible sans se battre avec la carte
- Pas de numéro de page badge sur ce slide (section banner sans badge)
- Le bloc d'expertise en bas n'est pas un icon-block standard : il est en mode "inline" (icône + texte sur même ligne)
