# Les Templiers — Tableau synoptique interactif

Version web du *Tableau synoptique de l'Ordre des Templiers* de François-Xavier Laurec.

## Contenu
- **Frise** : grands maîtres, croisades, rois capétiens, papes, rois de Jérusalem et événements alignés sur 1060-1314 (zoom, clic).
- **Année par année** : qui gouvernait en une année donnée, avec lecture automatique.
- **Index** : filtres par catégorie, siècle, origine, ordre religieux, papes français.
- **Fiches** : contemporains, événements liés, précédent/suivant, extrait et blason Wikipédia/Wikidata chargés à la volée.
- **Carte** (Leaflet), **Généalogies** (Mermaid), **Blasons** (Wikidata P94).

## Publication sur GitHub Pages
1. Créer un dépôt et y déposer `index.html` (et ce README) à la racine.
2. *Settings → Pages → Build and deployment* : source « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. Le site est en ligne à `https://<compte>.github.io/<depot>/`.

## Modifier le contenu
Toutes les données sont dans le bloc `const DATA = {...}` en tête de `index.html` :
`entries` (personnages et croisades), `events`, `places` (coordonnées), `genealogies`.
Dates au format `AAAA`, `AAAA-MM` ou `AAAA-MM-JJ`.
