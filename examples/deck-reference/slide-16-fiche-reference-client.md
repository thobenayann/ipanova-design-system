# Slide 16 — Fiche Référence Client (Airbus)

**Layout :** `deliverables` (variante fiche client)
**Fichier source :** `../fiche-reference-client.png`
**Pôle Ipanova :** ERP / SAP · Secteur Aéronautique

---

## Aperçu visuel

```
┌─ AIRBUS - TOULOUSE ─── [technologies] ──── [logo] ──────────┐
│                                                              │
│ ┌──────────────────────┐  Technologies                       │
│ │ CONCEPTION ET        │  ┌──────────────────────────────┐  │
│ │ DÉPLOIEMENT DE       │  │ SAP S4 · SAP EWM · SAP GTS   │  │
│ │ L'AIRBUS EWM         │  │ SAP SD · SAP PP · SAP QM     │  │
│ │ CORE MODEL           │  └──────────────────────────────┘  │
│ │                      │                                     │
│ │ Contexte :           │  Key numbers                        │
│ │ Dans le cadre de la  │  ┌──────────────────────────────┐  │
│ │ mise en service d'un │  │  [N] utilisateurs              │  │
│ │ EWM core model…      │  │  [N] sites de référence        │  │
│ │                      │  │  [N] mois de projet            │  │
│ │ Notre intervention : │  └──────────────────────────────┘  │
│ │ • Assistance au      │                                     │
│ │   paramétrage…       │                                     │
│ │ • Réalisation des    │                                     │
│ │   tests…             │                                     │
│ │                      │                                     │
│ │ ✅ Résultats         │                                     │
│ └──────────────────────┘                                     │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Section banner | "AIRBUS - TOULOUSE" (nom client + localisation) |
| Tags technologies | Pastilles teal sur fond clair listant les modules SAP utilisés |
| Logo | Ipanova couleur, haut-droit |
| Panneau gauche | Titre de mission + 3 blocs : Contexte / Notre intervention / Résultats |
| Titre de mission | Poppins Bold ~20pt, dark, 3-4 lignes |
| Bloc Contexte | Label bold teal + texte Regular 12pt |
| Bloc Intervention | Liste bullets avec pictos |
| Bloc Résultats | Badge vert ✅ + texte de bilan |
| Panneau droit | 2 blocs : Technologies (liste modules) + Key numbers (chiffres clés) |
| Key numbers | Pastilles ou tableau de 3 chiffres clés du projet |

---

## Usage du layout fiche référence

Ce layout documente une **mission client réalisée**. Structure systématique :
1. **Contexte** — problématique du client
2. **Notre intervention** — ce qu'Ipanova a fait
3. **Résultats** — impact mesurable
4. **Technologies** — stack SAP utilisée
5. **Key numbers** — 2-3 métriques fortes

---

## Tokens appliqués

- Titre de section banner = nom client (pas un thème Ipanova)
- Tags technologies : fond `colors.light-teal`, texte `colors.dark`, border `colors.primary`
- Badge résultats : fond vert clair, icône ✅

---

## Points de vigilance

- Les **chiffres clés** doivent être validés par le client avant publication
- Le logo du client (Airbus) n'apparaît pas sur cette slide — politique de discrétion
- Cette slide est reproductible pour tout client — changer banner, titre, contenu et technologies
