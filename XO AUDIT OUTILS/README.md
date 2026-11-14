# XO Audit — Portail avec logo officiel

Cette version remplace l’ancien monogramme XO par le logo XO Audit transmis.

## Publication GitHub Pages

Remplacer le fichier `index.html` du dépôt par celui de cette archive. Conserver / importer le dossier `applications` pour que les deux liens fonctionnent.

Le logo est intégré directement dans `index.html` (image PNG encodée en base64) : aucun fichier image supplémentaire, serveur ou appel externe nécessaire. La politique CSP autorise les images `data:` mais continue de bloquer les communications réseau.

## Applications conservées
- Balances âgées FEC
- Contrôle des stocks

Les fichiers clients sont traités dans le navigateur ; ne jamais publier des données clients sur GitHub.
