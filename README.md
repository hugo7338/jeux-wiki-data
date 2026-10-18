# jeux-wiki-data

Données publiées automatiquement pour les jeux du projet Jeux Wiki (d'abord **Obscur**). Ne pas éditer à la main : tout est regénéré chaque semaine par un workflow.

- `obscur/index.json` : liste des catégories et date de l'instantané
- `obscur/calendar.json` : les cinq catégories de chaque jour
- `obscur/categories/<id>.json` : membres d'une catégorie (titre d'article Wikipédia, identifiant Wikidata, alias, vues du dernier mois)
- `obscur/report.md` : rapport du dernier run

Sources : titres et identifiants depuis Wikipédia en français et Wikidata (CC0 pour Wikidata), nombres de vues depuis les dumps `pageview_complete` de la Wikimedia Foundation (CC0). Ces fichiers dérivés sont placés sous licence CC0 1.0. Projet sans lien avec la Wikimedia Foundation.

Servi à l'app par jsDelivr : `https://cdn.jsdelivr.net/gh/hugo7338/jeux-wiki-data@main/obscur/calendar.json`
