# Ipanova Design System — Slides

> Référentiel de design pour la génération automatisée de présentations Ipanova.
> Injecte ce repo dans le contexte de Claude Code, Cursor ou tout LLM pour obtenir des slides conformes à la charte.

---

## Philosophie

**Sobre. Structuré. Impactant.**

Les slides Ipanova ne font pas de bruit pour faire du bruit. Chaque élément a sa raison d'être.
La couleur primaire accentue, elle ne décore pas. Le texte convainc, il ne rembourre pas.

---

## Structure du repo

```
ipanova-design-system/
├── tokens/
│   ├── colors.json          # Palette complète
│   ├── typography.json      # Polices, tailles, graisses
│   └── spacing.json         # Marges, paddings, grids
├── layouts/
│   ├── cover.md             # Slide de couverture principale
│   ├── sommaire.md          # Slide sommaire numérotée
│   ├── section-divider.md   # Slide de transition de section
│   ├── content-split.md     # Layout 2 colonnes photo/contenu
│   ├── content-icon-list.md # Liste d'items avec icônes et taglines
│   ├── content-map.md       # Slide avec visuel + texte bas
│   ├── process-timeline.md  # Timeline de processus horizontale
│   ├── numbered-steps.md    # Étapes numérotées avec pills
│   ├── deliverables.md      # Liste livrables avec bordures colorées
│   ├── closing.md           # Slide de fermeture / contact
│   └── _global-rules.md     # Règles de composition globales
├── components/
│   ├── logo.md              # Usage du logo ipanova
│   ├── section-banner.md    # Bandeau de section gris
│   ├── ghost-number.md      # Grands chiffres décoratifs
│   ├── icon-block.md        # Bloc icône + titre + texte
│   ├── chevron-accent.md    # Chevron décoratif teal
│   ├── hexagon-frame.md     # Cadre hexagonal pour photos
│   ├── quote-block.md       # Bloc citation avec "66"
│   ├── left-border-item.md  # Item avec bordure gauche colorée
│   └── teal-dots.md         # Points décoratifs
├── editorial/
│   ├── tone-of-voice.md     # Ligne éditoriale
│   ├── title-patterns.md    # Structures de titres récurrentes
│   └── forbidden.md         # Ce qu'on ne fait jamais
├── prompts/
│   ├── system-prompt.md     # Prompt système à injecter
│   └── generation-brief.md  # Template de brief de génération
└── examples/
    └── deck-ia-offre/       # Deck de référence IA documenté
```

---

## Démarrage rapide

Pour générer un deck, injecte `prompts/system-prompt.md` comme system prompt, puis fournis un brief au format `prompts/generation-brief.md`.

Pour générer en `.pptx`, combine avec la skill `pptx/SKILL.md`.

---

## Versions

| Version | Date | Notes |
|---------|------|-------|
| 1.0.0 | 2026-04 | Extraction initiale depuis slides de référence |
