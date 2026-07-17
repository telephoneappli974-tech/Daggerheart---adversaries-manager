# Gestionnaire de combat Daggerheart

Application web locale pour gérer :

- les PJ et leur Évasion ;
- les adversaires ;
- les alliés ;
- les HP, le Stress, les seuils et les états ;
- les jets d’attaque et de dégâts ;
- la Fear et les repos ;
- une carte de distances avec zoom, déplacement, mesure et portées.

## Utilisation locale

Ouvrir `index.html` dans un navigateur récent.

Les données sont sauvegardées automatiquement dans le stockage local du navigateur. Utiliser régulièrement **Exporter** pour créer une sauvegarde JSON indépendante.

## Mise en ligne avec GitHub Pages

1. Créer un dépôt GitHub.
2. Envoyer les fichiers de ce dossier à la racine du dépôt.
3. Ouvrir **Settings → Pages**.
4. Choisir **Deploy from a branch**.
5. Sélectionner la branche `main` et le dossier `/root`.
6. Enregistrer.

## Fichiers

- `index.html` : structure de l’application ;
- `style.css` : apparence et mise en page ;
- `script.js` : fonctionnement, sauvegarde, jets et carte.
