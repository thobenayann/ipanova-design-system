# Slide 13 — Expertise SAP Fonctionnelle

**Layout :** `content-wheel` (layout infographique custom)
**Fichier source :** `../sap-expertise-fonctionnelle.png`
**Pôle Ipanova :** ERP / SAP

---

## Aperçu visuel

```
┌─ EXPERTISE SAP IPANOVA ──────────────────── [logo] ──────────┐
│                                                              │
│  [dot]   [Materials Management]         [Global Trade Svc]  │
│          Gère les processus d'achat…    Gère le commerce…   │
│                                                              │
│     MM ●                    ● GTS                           │
│                                                              │
│  [Quality Mgt]  QM ●  [SAP]  ● MRO  [Maintenance,Repair]   │
│                    FUNCTIONAL                                │
│                    ⬡ Expert                                  │
│  [Ext. Warehouse] EWM●  ● SD  [Sales & Distribution]        │
│                                                              │
│     MES ●  FICO ●  PP ●                                     │
│                                                              │
│  [Manuf. Exec.]  [Finance]  [Production Planning]           │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Section banner | "EXPERTISE SAP IPANOVA" |
| Logo | Ipanova couleur, haut-droit |
| Roue centrale | Logo SAP + texte "FUNCTIONAL" centré, entouré de modules en cercle |
| Modules (cercle) | MM, QM, EWM, MES, FICO, PP, SD, MRO, GTS — cercles colorés avec sigles |
| Couleur modules | Vert = Expert · Teal = Advanced · Jaune = Intermediate |
| Légende niveau | 3 niveaux : Expert (avion vert), Advanced (avion teal), Intermediate (avion jaune) |
| Labels autour | Nom complet du module + description courte en Poppins Regular 11pt |
| Teal dot déco | 1 point teal visible coin haut-gauche |
| Chevron déco | Chevron teal bas-droit (motif signature) |

---

## Logique de couleur des niveaux

| Couleur | Niveau | Modules concernés |
|---|---|---|
| Vert `#4caf50` | Expert | MM, EWM |
| Teal `#51bdcb` | Advanced | QM, MES, SD, MRO |
| Jaune `#ffc107` | Intermediate | GTS, FICO, PP |

---

## Spécificités layout

- **Layout custom non reproductible automatiquement** — nécessite un placement manuel des éléments en cercle
- La roue infographique est un asset SVG ou Canva, pas générée par python-pptx seul
- À utiliser comme **slide de crédibilité** dans les decks commerciaux SAP

---

## Points de vigilance

- Ne pas changer les couleurs des niveaux (vert/teal/jaune sont des conventions de la slide-type Ipanova)
- Le logo SAP au centre ne doit pas être modifié
