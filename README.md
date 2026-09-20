# Explorer mes possibilités d’évolution professionnelle

Prototype interactif IFAP / LIANE — version GitHub Pages.

## Déploiement

Aucune compilation n’est nécessaire. Le site est statique.

1. Déposer le contenu de ce dossier à la racine du dépôt GitHub.
2. Dans GitHub : **Settings → Pages**.
3. Dans **Build and deployment**, choisir **Deploy from a branch**.
4. Sélectionner la branche `main` et le dossier `/ (root)`.
5. Enregistrer.

Le point d’entrée est `index.html`.

## Structure

- `index.html` : module interactif ;
- `assets/infographies/` : 4 infographies SVG ;
- `.nojekyll` : empêche le traitement Jekyll inutile ;
- `CREDITS.md` : crédits et dépendances externes.

## Données apprenant

Le prototype conserve les réponses dans le stockage local du navigateur (`localStorage`). Aucune donnée personnelle du carnet n’est envoyée vers GitHub.

## À faire avant diffusion de production

- remplacer ou localiser les portraits externes ;
- terminer la recette tablette / desktop ;
- intégrer la couche SCORM 1.2 pour LIANE ;
- effectuer la recette réglementaire finale avant publication.
