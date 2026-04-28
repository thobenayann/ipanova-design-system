# Composant : Section Banner (Bandeau de section)

---

## Description
Bandeau horizontal en haut de slide indiquant la section en cours.

---

## Spécifications

```
┌────────────────────────────────────────────────┬──────┐
│  NOM DE LA SECTION                             │  n°  │
└────────────────────────────────────────────────┴──────┘
```

| Propriété | Valeur |
|---|---|
| Hauteur | 36pt |
| Fond | `banner (#555555)` |
| Texte | Poppins Bold, 12-13pt, UPPERCASE, letterspacing 3px |
| Couleur texte | white `#FFFFFF` |
| Position | haut de slide, pleine largeur |
| Padding gauche | 60pt |

### Badge numéro de page
| Propriété | Valeur |
|---|---|
| Forme | Carré 30x30pt |
| Fond | `dark (#333333)` |
| Texte | Poppins Bold, 14pt, white, centré |
| Position | extrême droite du bandeau |

---

## Usage

- Présent sur toutes les slides de **contenu** (pas sur cover, sommaire, section-divider, closing)
- Le label correspond au titre de section du sommaire
- Le numéro de page correspond à la position dans le deck

---

## Variante sans badge
Sur certaines slides très denses (process-timeline), le badge peut être omis pour gagner de l'espace.
