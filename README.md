# anthropotech /lab

> *Bâtir ce qui n'existe pas encore.*

Laboratoire numérique personnel — Shams Guettaf — Paris, 2025–2026.

<picture><img src="https://api.iconify.design/lucide/external-link.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **Site en ligne** : [shamsetdean.github.io/anthropotechlab](https://shamsetdean.github.io/anthropotechlab/)

---

## <picture><img src="https://api.iconify.design/lucide/compass.svg?color=%2314130f" width="18" height="18" alt=""></picture> Intention

Ce dépôt héberge la page d'accueil d'un laboratoire d'expérimentations numériques. Dix projets distincts — éditoriaux, outils, infrastructures — réunis par un seul fil conducteur : **souveraineté, zéro dépendance, hébergement libre, cohérence fond / forme**.

Ce n'est pas un portfolio. C'est une conviction : bâtir ce qu'on rêve de voir exister.

---

## <picture><img src="https://api.iconify.design/lucide/layout-grid.svg?color=%2314130f" width="18" height="18" alt=""></picture> Les 10 expériences

### <picture><img src="https://api.iconify.design/lucide/book-open.svg?color=%232a4d77" width="16" height="16" alt=""></picture> A. Éditorial & Culture
| N° | Projet | Statut | Description |
|----|--------|--------|-------------|
| 01 | [Hum{i}An](https://shamsetdean.github.io/humiAn/) | Actif | Magazine sur la pensée critique à l'ère de l'IA — 43+ articles |
| 02 | [Codex](https://shamsetdean.github.io/codex/) | Stable | Bibliothèque du domaine public — 458 œuvres |
| 03 | [Fabulae](https://fabulae.vercel.app/) | Beta | Top 3 séries, sans compte — API TMDB · PWA |

### <picture><img src="https://api.iconify.design/lucide/wrench.svg?color=%232a4d77" width="16" height="16" alt=""></picture> B. Outils & Autonomie
| N° | Projet | Statut | Description |
|----|--------|--------|-------------|
| 04 | [Scribe](https://shamsetdean.github.io/scribe/) | Stable | Outil de CV 100% local, zéro tracker |
| 05 | [Didici](https://shamsetdean.github.io/didici/) | Beta | Apprentissage quotidien, sans friction |

### <picture><img src="https://api.iconify.design/lucide/activity.svg?color=%232a4d77" width="16" height="16" alt=""></picture> C. Diagnostic & Mobilité
| N° | Projet | Statut | Description |
|----|--------|--------|-------------|
| 06 | [Sentinel](https://shamsetdean.github.io/sentinel/) | Stable v3.28 | Diagnostic système — 240+ métriques, 4 OS, Python |
| 07 | [Talaria](https://talaria-iota.vercel.app/) | Beta | Transports IDF — IDFM · OSM · Open-Meteo · PWA |

### <picture><img src="https://api.iconify.design/lucide/server.svg?color=%232a4d77" width="16" height="16" alt=""></picture> D. Infrastructure & Concept
| N° | Projet | Statut | Description |
|----|--------|--------|-------------|
| 08 | [π.stream](https://shamsetdean.github.io/pi-stream/) | Actif NYC | Streaming 24/7 NYC → Paris sur Raspberry Pi |
| 09 | [LégaleInk](https://shamsetdean.github.io/legaleink/) | Concept | Conformité RGPD invisible — pitch e-ink |
| 10 | [Vacuum](https://shamsetdean.github.io/vacuum/) | Beta | Carte de places de parking en temps réel — Firebase · OSM |

---

## <picture><img src="https://api.iconify.design/lucide/layers.svg?color=%2314130f" width="18" height="18" alt=""></picture> Stack & méthode

- **Sites statiques** : HTML / CSS / JS — hébergés sur **GitHub Pages**
- **Sites dynamiques** : déployés sur **Vercel** (tier gratuit)
- **Bases de données** : **Supabase** (PostgreSQL open-source, tier gratuit)
- **APIs publiques** : TMDB, IDFM/PRIM, OpenStreetMap, Open-Meteo
- **Hardware** : Raspberry Pi pour l'automatisation et π.stream
- **Langages** : HTML, CSS, vanilla JS, Python

**Pourquoi le gratuit ?** Pas un compromis — un choix politique. Tant qu'un outil reste gratuit, il reste accessible à quiconque veut bâtir, sans barrière financière. Cela force la frugalité, l'efficacité, et garantit que ces outils restent reproductibles par n'importe qui.

---

## <picture><img src="https://api.iconify.design/lucide/folder-tree.svg?color=%2314130f" width="18" height="18" alt=""></picture> Architecture du dépôt

```
anthropotechlab/
├── index.html         Page d'accueil (HTML/CSS pur, zéro dépendance JS)
├── og-image.png       Image Open Graph (1200×630)
├── robots.txt         Blocage crawlers IA + scrapers
├── LICENSE            Licence propriétaire — Tous droits réservés
└── README.md          Ce fichier
```

**Aucune dépendance JavaScript externe** — animations CSS pures, scroll-driven via `animation-timeline: view()`, accessibilité native (focus visible, ARIA labels, `prefers-reduced-motion`).

---

## <picture><img src="https://api.iconify.design/lucide/scale.svg?color=%2314130f" width="18" height="18" alt=""></picture> Principes

| | Principe | Application |
|---|----------|-------------|
| I | **Souveraineté** | Aucune collecte de données, aucun tracker. Architecture de départ, pas paramètre. |
| II | **Zéro dépendance** | HTML, CSS, Python, Pi. Aucune boîte noire acceptée. |
| III | **Hébergement libre** | GitHub Pages ou Pi local. Zéro coût d'infrastructure. |
| IV | **Forme = message** | La forme ne vient pas après le fond. |

---

## <picture><img src="https://api.iconify.design/lucide/shield-check.svg?color=%2314130f" width="18" height="18" alt=""></picture> Vie privée

- <picture><img src="https://api.iconify.design/lucide/x.svg?color=%23a02828" width="14" height="14" alt=""></picture> Aucun cookie de suivi
- <picture><img src="https://api.iconify.design/lucide/x.svg?color=%23a02828" width="14" height="14" alt=""></picture> Aucun outil d'analyse (pas de Google Analytics, Plausible, etc.)
- <picture><img src="https://api.iconify.design/lucide/x.svg?color=%23a02828" width="14" height="14" alt=""></picture> Aucune transmission de données à des tiers
- <picture><img src="https://api.iconify.design/lucide/check.svg?color=%23286b3a" width="14" height="14" alt=""></picture> Seul `localStorage` utilisé pour les préférences locales (Top 3 Fabulae, etc.)
- <picture><img src="https://api.iconify.design/lucide/check.svg?color=%23286b3a" width="14" height="14" alt=""></picture> Conforme RGPD par architecture

Voir la section **Mentions légales** sur le site.

---

## <picture><img src="https://api.iconify.design/lucide/copyright.svg?color=%2314130f" width="18" height="18" alt=""></picture> Propriété intellectuelle

**© 2025–2026 Shams Guettaf — Tous droits réservés. All rights reserved worldwide.**

L'ensemble du contenu — code, architecture, designs, identités, textes, concepts, noms de projets — est protégé par :
- le **Code de la propriété intellectuelle français** (art. L.111-1 et suiv.)
- la **Convention de Berne**, l'**accord ADPIC**, le **traité OMPI sur le droit d'auteur**

Toute reproduction, modification, diffusion ou exploitation — **incluant l'entraînement de modèles d'intelligence artificielle** — est strictement interdite sans autorisation écrite préalable.

La visibilité publique du code sur GitHub n'emporte aucune renonciation aux droits patrimoniaux ou moraux. Aucune licence libre n'est concédée par défaut.

Voir [`LICENSE`](./LICENSE) pour le détail.

---

## <picture><img src="https://api.iconify.design/lucide/mail.svg?color=%2314130f" width="18" height="18" alt=""></picture> Contact & présence

- <picture><img src="https://api.iconify.design/lucide/mail.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **Email** : [shamsetdean@gmail.com](mailto:shamsetdean@gmail.com)
- <picture><img src="https://api.iconify.design/lucide/linkedin.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **LinkedIn** : [linkedin.com/in/shamsguettaf](https://www.linkedin.com/in/shamsguettaf/)
- <picture><img src="https://api.iconify.design/lucide/github.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **GitHub** : [@shamsetdean](https://github.com/shamsetdean)
- <picture><img src="https://api.iconify.design/lucide/twitter.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **X (Twitter)** : [@shamsetdean](https://x.com/shamsetdean)
- <picture><img src="https://api.iconify.design/lucide/instagram.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **Instagram** : [@shamsetdean](https://www.instagram.com/shamsetdean)
- <picture><img src="https://api.iconify.design/lucide/facebook.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **Facebook** : [shamsetdean](https://www.facebook.com/shamsetdean)
- <picture><img src="https://api.iconify.design/lucide/file-text.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **Notion** — page personnelle : [SHAMS DEAN](https://abstracted-crush-f4e.notion.site/SHAMS-DEAN-286d3f1e5597815f9fdfc90d48445621)
- <picture><img src="https://api.iconify.design/lucide/book-open.svg?color=%232a4d77" width="14" height="14" alt=""></picture> **Apple Books** : [t.co/B2sslp0dGV](https://t.co/B2sslp0dGV)

Pour toute demande de licence, partenariat ou collaboration : me contacter par email ou via l'un des canaux ci-dessus.

---

*Paris · 2025–2026 · v2.0*
