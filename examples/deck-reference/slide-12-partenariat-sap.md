# Slide 12 — Notre Partenariat SAP

**Layout :** `content-split` (variante)
**Fichier source :** `../partenariat-sap.png`
**Pôle Ipanova :** ERP / SAP

---

## Aperçu visuel

```
┌─ NOTRE PARTENARIAT SAP ──────────────────── [logo] ──────────┐
│                                                              │
│ ┌──────────────────────┐   Compétences complémentaires       │
│ │ ipanova  &  SAP      │                                     │
│ │         Partner      │   [⬡] Structure des produits        │
│ │                      │       Décompose la nomenclature…    │
│ │ Depuis 2015,         │                                     │
│ │ Ipanova développe    │   [⬡] Intégration des systèmes      │
│ │ une expertise…       │       Connecte les applications…    │
│ │                      │                                     │
│ │ Produits sous        │   [⬡] Business Technology Plat.     │
│ │ licence :            │       Plateforme cloud pour…        │
│ │ Business One         │                                     │
│ │ BI & Data            │   [⬡] Reporting BI/FP&A             │
│ │ BTP · S4/HANA        │       Analyse des données…          │
│ └──────────────────────┘                                     │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Section banner | "NOTRE PARTENARIAT SAP" |
| Logo | Ipanova couleur, haut-droit |
| Panneau gauche | Fond blanc — co-branding "ipanova & SAP Partner" + texte intro + liste produits SAP sous licence |
| Co-branding | Logo ipanova + logo SAP Partner côte à côte, même ligne |
| Texte intro | Poppins Regular ~13pt, dark, 3-4 lignes — mentionne "depuis 2015" et les domaines SAP couverts |
| Produits SAP | Liste avec logos SAP officiels (Business One, BI&Data, BTP, S/4HANA, ERP Generation) |
| Panneau droit | 4 icon-blocks teal — compétences complémentaires |

---

## Spécificités layout

- Variante de `content-split` où le panneau gauche contient du **texte + logos partenaires** plutôt qu'une photo
- Les logos SAP officiels remplacent les icônes hexagone sur la liste produits (exception autorisée pour logos tiers certifiés)
- Le badge "SAP Partner" est affiché tel quel sans modification

---

## Tokens appliqués

- Titre : `colors.dark` + `colors.primary` ("SAP" en teal)
- Icon-blocks droite : hexagone `colors.primary` standard

---

## Points de vigilance

- Ne jamais déformer les logos SAP officiels
- Le texte "Depuis 2015" est un ancrage de crédibilité — toujours présent sur cette slide
