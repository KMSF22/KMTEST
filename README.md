# KMTEST — Slack & Claude, le guide

Minisite statique en français : un guide pratique pour prendre en main Slack
et utiliser Claude dans Slack (Claude Tag), du premier message au premier
workflow automatisé.

## Contenu

| Fichier | Rôle |
| --- | --- |
| `site/index.html` | Page unique du guide (5 chapitres : Bases, Organiser son travail, Fichiers & intégrations, Utiliser Claude dans Slack, Astuces productivité). |
| `site/style.css` | Styles : thème clair/sombre (`prefers-color-scheme`), mise en page en colonne unique, navigation sticky. |
| `Filetest` | Fichier de test préexistant du dépôt. |

Aucune dépendance de build ni JavaScript. Seules les polices (Fraunces,
Source Sans 3, JetBrains Mono) sont chargées depuis Google Fonts.

## Voir le site en local

```sh
cd site
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Publier avec GitHub Pages

Settings → Pages → Source : branche `main`, dossier `/site` (ou déployer via
une GitHub Action).

## Origine

Page adaptée d'un artefact Claude (« Slack & Claude, le guide »), séparée en
HTML et CSS pour être hébergée comme site statique.
