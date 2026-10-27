# hors-zone-ai.github.io

La racine de l'adresse https://hors-zone-ai.github.io/ de l'association Hors Zone AI. Le site lui-même vit dans le dépôt [site](https://github.com/hors-zone-ai/site), publié sur https://hors-zone-ai.github.io/site/.

Ce dépôt ne sert qu'à poser ce qui doit être à la racine de l'adresse :

- `robots.txt` : tous les robots sont autorisés, moteurs de recherche et IA compris, avec le lien vers le sitemap du site ;
- `llms.txt` : un résumé du site pour les modèles et les agents IA ;
- `.well-known/security.txt` : comment signaler une faille (signalement privé GitHub sur le dépôt site), date d'expiration à repousser chaque année ;
- `index.html` : renvoie vers le site ;
- `.nojekyll` : pour que GitHub Pages publie le dossier `.well-known`.

Quand le site passera sur horszone.ai, ces fichiers iront à la racine du dépôt site.
