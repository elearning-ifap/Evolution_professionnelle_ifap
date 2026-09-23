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


## v0.10
- Personas recontextualisés pour la Nouvelle-Calédonie.
- Portraits intégrés localement dans `assets/portraits/`.
- Suppression des mentions de test/provisoire.
- Aucun chargement distant nécessaire pour les portraits.

## v0.10 — recette de l’accueil

- recomposition verticale du panneau des personas ;
- cartes élargies et meilleure lisibilité des rôles/citations ;
- portraits recadrés sans texte ni faux logo dans l’image ;
- amélioration de l’affichage tablette et mobile ;
- portraits toujours intégrés localement.

## v0.10 — consolidation pédagogique et UX

- début du parcours raccourci : 27 → 24 écrans ;
- fusion de « ce qui m’amène ici » et « ce que je souhaite faire évoluer » ;
- suppression des écrans intermédiaires qui répétaient la démarche ou la synthèse ;
- 4 capacités de sortie visibles dès l’accueil ;
- suppression des principaux doublons texte/infographie ;
- carte des possibilités allégée avec orientation non prescriptive ;
- les 4 personas jouent désormais un rôle dans l’exploration ;
- cas final Maëva remplacé par Mikaël ;
- autoévaluation réduite de 7 à 4 capacités ;
- un scénario suffit, les 2 autres sont explicitement facultatifs ;
- action « maintenant » prioritaire, horizons suivants facultatifs ;
- commande pour effacer les données personnelles locales.
