# Curanobilis — site vitrine

Page unique, autonome : tout le CSS et le JS sont dans `index.html`.
Seule dépendance externe : les polices Google (Cormorant Garamond, Hanken Grotesk).

## Voir la page

Double-cliquer `index.html`, ou servir le dossier :

    python3 -m http.server 4321 --directory ~/Documents/curanobilis

puis http://localhost:4321

## Contenu

- Bilingue FR / EN — bascule en haut à droite, choix mémorisé (localStorage)
- Thème clair / sombre automatique (`prefers-color-scheme`)
- Sections : hero · prestations · parcours · cas complexes · équipe · formules · confidentialité · contact

## À remplacer avant mise en ligne

- Téléphone `+41 22 000 00 00` (masthead, encart contact, message de confirmation du formulaire)
- Adresse `Rue du Rhône 00, 1204 Genève`
- `contact@curanobilis.ch`
- Les engagements chiffrés : 90 minutes d'intervention, rappel sous 2 h, zones desservies
- Le formulaire n'envoie rien — il affiche une confirmation. À brancher sur un service d'envoi
  (Formspree, Basin) ou un endpoint maison avant toute diffusion.

## Déploiement

Site statique : n'importe quel hébergeur convient (Infomaniak, Netlify, Cloudflare Pages).
Déposer `index.html` à la racine.
