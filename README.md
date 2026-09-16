# De Locataire à Propriétaire — Landing page

Page de vente (single-file `index.html`) pour le guide PDF **« De Locataire à Propriétaire : Le Guide Étape par Étape Pour Devenir Propriétaire Sans Prêt »**.

## Caractéristiques
- Un seul fichier `index.html` autonome (HTML + CSS + JS inline, aucune dépendance lourde).
- Design responsive mobile-first, palette terre cuite / sable / or.
- SEO complet (Open Graph, Twitter Card, Schema.org, favicon).
- Compte à rebours, FAQ, témoignages, notifications d'achat, aperçu vidéo (flipbook).
- Prêt à déployer sur Vercel.

## Déploiement (Vercel)
1. Importer ce dépôt dans [Vercel](https://vercel.com/new).
2. Aucune configuration de build nécessaire (site statique).
3. Avant la mise en production, mettre à jour dans `index.html` :
   - les balises `canonical` et `og:url` avec le vrai domaine ;
   - `og:image` / `twitter:image` avec l'image de couverture définitive (1200×630).

## Aperçu en local
Ouvrir `index.html` dans un navigateur, ou servir le dossier avec un petit serveur statique.
