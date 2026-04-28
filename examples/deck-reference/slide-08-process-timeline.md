# Slide 08 — Process Timeline (Cycle de vie SAP EWM)

**Layout :** `process-timeline`  
**Fichier source :** `../14.png`

---

## Aperçu visuel

```
┌─ NOTRE ACCOMPAGNEMENT DE BOUT EN BOUT ──────── [logo] ───────┐
│                                                              │
│  DE LA CONCEPTION INITIALE AU SUPPORT OPÉRATIONNEL,         │
│  IPANOVA COUVRE TOUT LE CYCLE DE VIE SAP EWM                │
│                                                              │
│  ┌──────────┐  ──→  ┌──────────┐  ──→  ┌──────────┐  ──→  ┌──────────┐  │
│  │ CADRAGE  │       │IMPLÉMEN- │       │FORMATION │       │ SUPPORT  │  │
│  │          │       │TATION    │       │  GO LIVE │       │          │  │
│  │• Compa-  │       │• Paramé- │       │• Supports│       │• Correctif│ │
│  │  rer les │       │  trage   │       │  pédago- │       │• Correc-  │ │
│  │  flux    │       │• Intégra-│       │  giques  │       │  tions    │ │
│  │• Évaluer │       │  tion    │       │• Migra-  │       │  données  │ │
│  │  effort  │       │  fluide  │       │  tions   │       │• Accompa- │ │
│  │• Établir │       │          │       │• Gestion │       │  gnement  │ │
│  └──────────┘       └──────────┘       └──────────┘       └──────────┘  │
│                                                   [icône avion haut-droit]│
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Section banner | "NOTRE ACCOMPAGNEMENT DE BOUT EN BOUT" (sans badge numéro) |
| Logo | Ipanova couleur, haut-droit |
| Titre | "DE LA CONCEPTION INITIALE AU SUPPORT OPÉRATIONNEL," dark → retour ligne → "IPANOVA COUVRE TOUT LE CYCLE DE VIE SAP EWM" (mix dark/teal) |
| Icône déco | Avion ou flèche orientée droite, haut-droit, teal, 40pt environ |
| 4 colonnes d'étapes | Largeur égale (~22% chacune), séparées par flèches horizontales teal |
| Titre de colonne | Poppins Bold 700, UPPERCASE, ~15pt, dark, fond légèrement coloré (teal très pâle ou gris clair) |
| Badge GO LIVE | Pastille "GO ▶ LIVE" sur la colonne Formation, teal fond |
| Contenu colonne | Bullet points Poppins Regular 11-12pt, dark |
| Mots gras | Termes techniques clés en Poppins Bold dans le contenu |
| Flèches | Chevrons teal (`#51bdcb`), centré verticalement entre colonnes |

---

## Tokens appliqués

- Flèches/chevrons : `colors.primary`
- Titre colonne fond : `colors.primary` à ~15% opacité ou `#e8f7f9`
- Badge GO LIVE : fond `colors.primary`, texte white

---

## Points de vigilance

- 4 étapes = maximum pour ce layout horizontal (sinon colonnes trop étroites)
- Les flèches sont **entre les colonnes**, pas dans les colonnes
- Chaque colonne doit avoir **3-5 bullet points** max
- L'icône décorative (avion) symbolise le secteur client — à adapter selon le contexte
