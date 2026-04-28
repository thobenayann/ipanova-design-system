# Layout : Closing (Slide de fermeture / contact)

**Référence visuelle :** slide 17 (Merci)

---

## Objectif
Fermer le deck avec impact et laisser les coordonnées de contact.

---

## Structure visuelle

```
┌──────────────────────┬──────────────────────────────────────┐
│                      │                                      │
│  ○ ○ ○ ○  Merci      │  ipanova ·              2026         │
│                      │                                      │
│  pour l'opportunité  │                                      │
│  de présenter notre  │        ↓                             │
│  expertise. [texte]  │                                      │
│                      │                                      │
│  [Photo overlay      │  [Photo overlay                      │
│   sombre gauche]     │   teal/neutre droite]                │
│                      │                                      │
│                      │  NOM PRÉNOM                          │
│                      │  +33 (0)X.XX.XX.XX  📞               │
│                      │  https://www.ipanova.com  🌐          │
│                      │  Adresse                  📍          │
└──────────────────────┴──────────────────────────────────────┘
```

---

## Spécifications

### Fond global
- Deux photos plein bleed, côte à côte (split 50/50)
- Photo gauche : overlay sombre `rgba(0,0,0,0.65)` — dominante noire
- Photo droite : overlay teal/neutre `rgba(0, 50, 80, 0.55)` — dominante teal/gris
- Photo type : mains, collaboration, bureau Ipanova

### Panneau gauche

#### Dots décoratifs
- 4 cercles vides (outline) blancs, ~12pt, alignés horizontalement
- Position : haut-gauche, au-dessus du "Merci"

#### Titre "Merci"
- Poppins Bold 900, ~72pt
- Couleur : **white**
- Alignement : gauche

#### Texte de courtoisie
- Poppins Regular, 16pt, white
- Max 4-5 lignes
- Ton : engagement, co-construction, disponibilité

### Panneau droit

#### Logo ipanova
- Version **blanche** (sur fond sombre)
- Position : haut, centré ou légèrement gauche
- Taille standard

#### Année
- Poppins Regular, 18pt, white
- Aligné à droite du logo

#### Flèche vers le bas
- Flèche fine blanche →↓ (direction bas)
- Taille ~50pt
- Position : centre du panneau, milieu vertical
- Symbolise : "la suite se passe ici"

#### Bloc contact
- Position : bas du panneau droit
- **Nom Prénom** : Poppins Bold, 16pt, white, UPPERCASE
- Ligne phone : icône 📞 + numéro, Regular, white
- Ligne site : icône 🌐 + URL, Regular, white (souligné)
- Ligne adresse : icône 📍 + adresse, Regular, white
- Espacement entre lignes : 8pt

---

## Ce qu'on ne fait PAS

- ❌ Fond uni (doit rester photo)
- ❌ Logo en couleur sur fond sombre
- ❌ Contact sans tous les éléments (téléphone + site + adresse = obligatoires)
- ❌ "Merci" en teal (doit rester blanc)
- ❌ Texte trop long côté gauche (4-5 lignes max)
