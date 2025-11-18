# SBT Executive – Static Master Package

Ce package contient :
- `index.html` : page d'accueil statique.
- `sbt_master_hierarchical.json` : structure hiérarchique (pages → blocs → CTA).
- `master_with_cta.csv` : CSV maître fusionné avec toutes les règles de CTA.

## Déploiement sur GitHub + Vercel

1. Dézipper ce dossier à la racine d'un dépôt GitHub.
2. Connecter le dépôt à Vercel.
3. Paramètres recommandés :
   - Framework Preset : **Other**
   - Build Command : _(laisser vide ou `:`)_
   - Install Command : _(laisser vide ou `:`)_
   - Output Directory : `.`

Vercel servira alors :
- `/` → `index.html`
- `/sbt_master_hierarchical.json`
- `/master_with_cta.csv`
