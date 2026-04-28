# Slide 07 — Content Split (EWM Supply Chain)

**Layout :** `content-split`  
**Fichier source :** `../12.png`

---

## Aperçu visuel

```
┌──────────────────────────────────────────── [logo] ──────────┐
│                                                              │
│ ┌──────────────┐  POURQUOI EWM TRANSFORME LA                │
│ │              │  SUPPLY CHAIN                              │
│ │   [photo]    │                                            │
│ │   ouvrier    │  Un outil stratégique pour optimiser vos   │
│ │   entrepôt   │  entrepôts et sécuriser vos opérations     │
│ │              │                                            │
│ │   [SAP EWM]  │  [⬡] Optimisation logistique              │
│ │    badge     │      Maîtrise des processus de réception…  │
│ │              │  [⬡] Traçabilité renforcée                 │
│ │              │      Expertise unique dans la logistique…  │
│ │              │  [⬡] Expérience digitale moderne           │
│ │              │      Interopérabilité avec RFUI & Fiori…   │
│ │              │  [⬡] Continuité opérationnelle             │
│ └──────────────┘      Assure les activités lors de la…      │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Pas de section banner | Ce slide n'a pas de bandeau de section (exception ou slide d'intro de section) |
| Logo | Ipanova couleur, haut-droit |
| Photo gauche | ~38% largeur, hauteur quasi-totale, ouvrier logistique |
| Badge SAP EWM | Logo SAP EWM sur la photo, bas-centre |
| Titre | "POURQUOI EWM TRANSFORME LA" dark + "SUPPLY CHAIN" teal, UPPERCASE |
| Sous-titre | Poppins Regular ~14pt, dark, 2 lignes, sous le titre |
| 4 icon-blocks | Hexagone teal 48pt + label bold + description 2 lignes |

---

## Différences vs slide-05

- Pas de section banner → slide de type "intro de section approfondie"
- Sous-titre descriptif présent (absent sur slide-05)
- 4 blocs (vs 6) → description plus longue par bloc
- Pas de chevrons décoratifs

---

## Tokens appliqués

- Titre : `colors.dark` + `colors.primary` pour le mot-clé fort final
- Sous-titre : `colors.dark`, `typography.weights.regular`
- Mots gras dans description : `typography.weights.bold` sur termes techniques clés

---

## Points de vigilance

- Les **mots en gras dans la description** sont des termes métier clés (réception, prélèvement, migration…)
- Le sous-titre sous le titre principal est une accroche résumant la valeur — 1-2 lignes max
