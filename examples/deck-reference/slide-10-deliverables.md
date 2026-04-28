# Slide 10 — Deliverables (Livrables du cadrage)

**Layout :** `deliverables`  
**Fichier source :** `../16.png`

---

## Aperçu visuel

```
┌──────────────────────────────────────────── [logo] ──────────┐
│                                                              │
│  LES LIVRABLES DU CADRAGE                                   │
│  Des livrables précis pour décider, estimer et              │
│  garantir un déploiement fluide du projet                   │
│                                                              │
│         ┌──────────┐                                        │
│        ╱            ╲   1. Flux actualisés AS-IS            │
│       ╱   [triangle]  ╲     • bullet 1                      │
│      ╱  graphique svg  ╲    • bullet 2                      │
│     ╱____________________╲                                  │
│     │  OPTION-  │ OPTION- │  2. Référentiel fonctionnalités │
│     │  NEL      │ NEL     │  3. Analyse des écarts & impacts│
│                           │  4. Projection projet : chiffré │
│                                                              │
│  [quote box]  "Des livrables qui garantissent…"             │
└──────────────────────────────────────────────────────────────┘
```

---

## Éléments présents

| Élément | Spécification observée |
|---|---|
| Pas de section banner | Slide sans bandeau (continuation directe de la séquence) |
| Logo | Ipanova couleur, haut-droit |
| Titre | "LES LIVRABLES DU" dark + "CADRAGE" teal, UPPERCASE |
| Sous-titre | Poppins Regular ~13pt, dark, 2 lignes |
| Infographie triangle | Schéma triangulaire avec sections, teal et gris, côté gauche (~40% largeur) |
| 4 livrables (droite) | Numérotés 1-4, label bold + bullets Regular, côté droit (~55% largeur) |
| Labels triangle | "OPTIONNEL" en Poppins Bold ~11pt, disposés dans les sections du triangle |
| Quote box | Bas de slide, fond dark, texte white italic Poppins, ~pleine largeur |

---

## Structure du livrable (droite)

| Sous-élément | Valeur observée |
|---|---|
| Numéro | Chiffre "1." Poppins Bold 700, ~14pt, teal ou dark |
| Label | Poppins Bold 700, ~14-15pt, dark |
| Bullets | Poppins Regular 400, ~12pt, dark, 2-4 par livrable |
| Mots gras | Termes clés en Bold dans les bullets |

---

## Tokens appliqués

- Titre split : `colors.dark` + `colors.primary`
- Quote box fond : `colors.dark`
- Infographie : `colors.primary` pour les zones actives, gris pour les zones optionnelles

---

## Points de vigilance

- L'infographie triangle est une **illustration SVG/custom** — ne pas tenter de la recréer en texte pur
- Le côté gauche (triangle) et le côté droit (livrables) sont visuellement complémentaires
- La quote box de clôture est une **synthèse décisionnelle** — elle doit être courte et percutante (1-2 lignes)
