# Slide 05 — Content Split (Présentation Ipanova — chiffres clés)

**Layout :** `content-split`  
**Fichier source :** `../5.png`

---

## Aperçu visuel

```
┌─ PRÉSENTATION IPANOVA ─────────── 1 ──────────── [logo] ────┐
│                                                              │
│ ┌──────────────┐  PARTENAIRE DE PROXIMITÉ, ENGAGÉ           │
│ │              │  DANS VOTRE RÉUSSITE A LONG TERME          │
│ │   [photo]    │                                            │
│ │              │  [🔷] 4 pôles d'expertise : ERP SAP...    │
│ │ Created &    │  [🔷] Des clients de toutes tailles...    │
│ │ Managed By   │  [🔷] 100 consultants passionnés...       │
│ │ consultants  │  [🔷] Écoute, Réactivité...               │
│ │              │  [🔷] 6,5M€ de CA en 2024                 │
│ │ AGENCES      │  [🔷] Création de l'entreprise en 2015    │
│ │ TOULOUSE...  │                                            │
│ └──────────────┘                                            │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Section banner | "PRÉSENTATION IPANOVA" + badge "1" |
| Logo | Ipanova couleur, haut-droit, ~88pt large |
| Photo gauche | ~38% largeur slide, hauteur quasi-totale, image consultants |
| Overlay sur photo | Texte blanc "Created & Managed By consultants" en Poppins Italic |
| Pictos sur photo | Drapeaux FR/USA et labels agences en Poppins Bold blanc |
| Badge SAP | Logo SAP Partner sur la photo |
| Titre | "PARTENAIRE DE PROXIMITÉ," dark + "ENGAGÉ DANS VOTRE RÉUSSITE A LONG TERME" avec mots teal |
| Liste icônes | 6 icon-blocks en format compact (icône hexagone teal 48pt + label bold + texte) |

---

## Tokens appliqués

- Titre : `colors.dark` avec `colors.primary` pour les mots forts
- Icon-blocks : hexagone `colors.primary`, label `typography.weights.bold`
- Section banner : fond `#555555`, texte white

---

## Points de vigilance

- Le titre est sur **2 lignes** avec un saut de ligne intentionnel
- Les mots accentués dans le titre sont teal : "ENGAGÉ", "VOTRE RÉUSSITE"
- 6 icon-blocks est le **maximum** pour ce layout — au-delà la slide devient trop dense
- L'overlay photo avec texte blanc est spécifique à ce slide (témoignage/positioning statement)
