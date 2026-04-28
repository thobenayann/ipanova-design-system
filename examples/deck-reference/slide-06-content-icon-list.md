# Slide 06 — Content Icon List (Notre offre)

**Layout :** `content-icon-list`  
**Fichier source :** `../7.png`

---

## Aperçu visuel

```
┌─ NOTRE OFFRE ─────────────────── 2 ──────────── [logo] ─────┐
│                                                              │
│  MAXIMISEZ VOTRE PERFORMANCE AVEC DES                       │
│  OUTILS DIGITAUX ADAPTÉS                                     │
│                                                              │
│  ┌──────────────────┐  ┌──────────────────┐                 │
│  │[⬡] Solution ERP  │  │[⬡] Data & BI     │                 │
│  │    SAP           │  │                  │  [photo]        │
│  │    Texte court   │  │    Texte court   │                 │
│  │    ✦ Tagline     │  │    ✦ Tagline     │                 │
│  └──────────────────┘  └──────────────────┘                 │
│  ┌──────────────────┐  ┌──────────────────┐                 │
│  │[⬡] Applications  │  │[⬡] Intelligence  │  [chevrons     │
│  │    sur mesure    │  │    Artificielle  │   déco]         │
│  │    Texte court   │  │    Texte court   │                 │
│  │    ✦ Tagline     │  │    ✦ Tagline     │                 │
│  └──────────────────┘  └──────────────────┘                 │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Section banner | "NOTRE OFFRE" + badge "2" |
| Logo | Ipanova couleur, haut-droit |
| Titre | "MAXIMISEZ VOTRE PERFORMANCE" dark + "AVEC DES OUTILS DIGITAUX ADAPTÉS" split teal |
| Photo | Image équipe, ~25% largeur, bord droit, mi-hauteur (décorative) |
| Grille icon-blocks | 2 colonnes × 2 lignes = 4 blocs |
| Icônes | Hexagone teal 64pt avec icône outline blanche |
| Chevrons déco | Teal, bas-droit, partiellement hors slide |
| Teal dots | 1 point teal visible haut-droit |

---

## Détail d'un icon-block

| Sous-élément | Valeur observée |
|---|---|
| Label | Poppins Bold 700, ~17pt, dark |
| Description | Poppins Regular 400, ~13pt, dark, 2-3 lignes |
| Tagline | Poppins Bold Italic, ~13pt, teal, phrase courte |

---

## Tokens appliqués

- Hexagone : `colors.primary` (`#51bdcb`)
- Taglines : `colors.primary`
- Titre split : `colors.dark` + `colors.primary`

---

## Points de vigilance

- Le titre est sur **2 lignes** — première ligne dark, deuxième partiellement teal
- La photo côté droit est décorative et **ne prend pas toute la hauteur** (contrast avec slide-05)
- Les 4 blocs sont de taille égale — ne pas déséquilibrer
- La tagline italique teal est **obligatoire** sur ce layout (elle exprime la promesse client)
