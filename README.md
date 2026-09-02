# Bengacoon 360 / Cocoon — site vitrine

Site vitrine **public** des applications **Bengacoon 360** (édition pro thérapeute) et
**Cocoon** (édition famille) — deux éditions construites sur le même code, par Bengacoon.

L'application est **en cours de développement** : le site présente le produit à venir,
sans lien de téléchargement actif pour l'instant.

## Contenu

- `index.html` — page de présentation (deux éditions, 8 modules, tronc commun, téléchargement)
- `privacy.html` — politique de confidentialité (données 100 % locales, aucune télémétrie)
- `CHANGELOG.md` — historique des versions de l'application (1.0.0 → 1.11.0)
- `FONCTIONNALITES.md` — descriptif complet des fonctionnalités
- `updates/` — manifestes de mise à jour in-app (`bengacoon360.json`, `cocoon.json`)
- `assets/` — logo, favicon et logos des 8 modules

## Publication (GitHub Pages)

Le site est servi par **GitHub Pages** depuis la branche `main` (racine) :
https://jdviallat.github.io/bengacoon-360-site/

Le fichier `.nojekyll` désactive Jekyll (service des fichiers tels quels).

## Manifestes de mise à jour (`updates/`)

Les apps interrogent un manifeste `latest.json` au démarrage pour proposer une mise à
jour (format : `version`, `url`, `notes`, `mandatory`, `minVersion`).

⚠️ **Pas encore actifs** : les URLs `url` pointent vers les assets de la release
`v1.11.0` du dépôt de code `jdviallat/bengacoon-360`, qui est **privé** pour l'instant
(l'application n'est pas publiée). GitHub ne sert pas les releases des dépôts privés :
ces manifestes s'activeront automatiquement à la publication de l'application, quand
la release APK sera rendue accessible. D'ici là, ils sont hébergés ici, prêts.

## Dépôts

- `jdviallat/bengacoon-360` — code de l'application (privé)
- `jdviallat/bengacoon-360-site` — ce site (public, GitHub Pages)

© 2026 Bengacoon.
