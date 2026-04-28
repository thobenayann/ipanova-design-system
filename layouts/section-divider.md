# Layout : Section Divider (Slide de transition)

**Référence visuelle :** slide 3

---

## Objectif
Annoncer l'entrée dans une nouvelle section. Crée une pause visuelle forte entre les chapitres.

---

## Structure visuelle

```
┌────────────────────────────────────────────────────────┐
│                                                        │
│  [01]  TITRE SECTION                [hexa photo 1]    │
│        ipanova                      [hexa photo 2]    │
│              ·                                        │
│                                                       │
└────────────────────────────────────────────────────────┘
```

---

## Spécifications

### Fond
- Blanc `#FFFFFF`
- Pas de bandeau de section, pas de logo top-right séparé

### Ghost number
- Poppins Black 900, ~200pt
- Couleur : `ghost (#CCCCCC)`, opacité **35%**
- Position : **haut-gauche**, le titre textuel vient par-dessus
- Le numéro correspond à la section (01, 02, 03...)

### Titre de section
- **Ligne 1** : numéro section en `dark (#333333)`, style `h1-section-divider`
- **Ligne 2** : "NOM DE LA SECTION" en Poppins Black, 56-72pt, UPPERCASE, `dark`
- **Ligne 3** : `ipanova` en logo textuel, ~80pt, `secondary (#006688)`
- Le point final du logo ipanova est en `primary (#51bdcb)`
- Alignement : **gauche**

### Cluster hexagonal (droite)
- 2 hexagones imbriqués avec photos à l'intérieur
- Bordure : `primary (#51bdcb)`, 3pt
- Hexagone haut : ~240pt, hexagone bas : ~200pt
- Les hexagones se chevauchent légèrement (~30pt)
- Photos : contexte professionnel en rapport avec la section
- Positionnement : **droite de la slide**, centré verticalement

### Proportions
- Texte : ~55% de la largeur (gauche)
- Hexagones : ~40% de la largeur (droite)

---

## Variantes

| Section | Thème photo suggéré |
|---|---|
| Présentation Ipanova | Collaboration, réunion |
| Notre offre | Digital, laptop, tech |
| SAP / EWM | Logistique, entrepôt, système |
| IA | Futuriste, data, réseau |
| Clients | Poignée de main, succès |

---

## Ce qu'on ne fait PAS

- ❌ Texte de description sur cette slide
- ❌ Bullets ou items de contenu
- ❌ Plus de 2 hexagones
- ❌ Logo séparé (le nom "ipanova" fait office de logo ici)
