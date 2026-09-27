# LUX
LUX ULTIMATE v2.0.0 — Langage de balisage remplacant HTML + CSS + JS # 60+ primitives, 16 themes, composants dynamiques, routage SPA, # etat reactif, formulaires, tables, graphiques, animations, i18n, # plugins, compilation multi-cibles (HTML/JSON/Markdown/SVG). # Auteur : Aissa Mohammedi (DGK) # Licence : NEXUS-OPEN-2.0

# LUX — Langage de balisage remplaçant HTML + CSS + JS
[![Version](https://img.shields.io/badge/version-2.0.0-00ffc8)](https://github.com/Aissamohammedi88/lux)
[![License](https://img.shields.io/badge/license-NEXUS--OPEN--2.0-ff00c8)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.7+-00c8ff)](https://www.python.org/)
[![Dependencies](https://img.shields.io/badge/dependencies-0-00ff88)]()

> **Un seul fichier. Un seul langage. 60+ primitives. 16 thèmes. Zéro dépendance.**

Créé par **Aissa Mohammedi (DGK)** — [awamomo646@outlook.com](mailto:awamomo646@outlook.com)

---

## Pourquoi LUX ?

Parce que le web moderne est devenu trop compliqué.

Aujourd'hui, pour faire une page simple, il faut :
- **HTML** pour la structure
- **CSS** pour le style
- **JS** pour l'interaction
- **npm + webpack/vite** pour builder
- **500 Mo de `node_modules`**
- **10 ans d'expérience** pour tout maîtriser

**LUX remplace tout ça par un seul fichier.**

---

## Le problème que LUX résout

| Problème | HTML/CSS/JS | LUX |
|----------|-------------|-----|
| Fichiers à créer | 3+ | **1** |
| Lignes pour un bouton | 5+ | **1** |
| Sélecteurs CSS à retenir | 50+ | **0** |
| Événements à câbler | 20+ | **inline** |
| Temps réel | fetch + setInterval + DOM | **1 ligne** |
| Thème | 100 lignes CSS | **1 mot** |
| Build | Webpack / Vite | **aucun** |
| Dépendances | 500 Mo | **0** |

---

## Exemple — 6 lignes LUX = 40 lignes HTML+CSS+JS

**En LUX :**

```lux
page titre="Mon site" theme="cyber"
titre "Bienvenue" taille=48 couleur=#00ffc8
texte "Ceci est une page LUX."
bouton "Cliquer" action="alert('Hello')" couleur=#ff00c8
horloge
compteur depart=0 pas=1 intervalle=1000
