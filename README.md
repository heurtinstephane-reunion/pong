# Pong 🏓

Petit jeu Pong jouable dans le navigateur, 100 % HTML/CSS/JavaScript, sans dépendance.

## Comment jouer

Ouvre le jeu ici : https://heurtinstephane-reunion.github.io/pong/

- **Souris** ou flèches **↑ / ↓** (aussi **W / S**) pour bouger la raquette
- **Tactile** : glisse n'importe où sur l'écran, la raquette suit (zone invisible plein écran)
- **Menu** : tap sur le cercle central du plateau, bouton « ☰ Menu » en haut à droite, **Espace**, **P** ou **Échap**
- Le menu contient des réglages en direct : puissance et durée du lift, vitesse de la balle, difficulté de l'IA, orientation du plateau (auto / paysage forcé / jamais) — mémorisés localement
- **Effet (lift)** : si la raquette bouge au moment du contact, la balle part en courbe à la manière du tennis (balle orangée + traînée)
- Premier à **7 points** gagne ; l'animation « GOAL! » précède la remise en jeu par celui qui encaisse
- **Mobile** : en portrait, le plateau pivote automatiquement en paysage — tourne le téléphone dans le sens horaire (l'orientation peut être changée dans le menu)

## En local

Télécharge `index.html` et ouvre-le dans n'importe quel navigateur.

## Publication

Le site est publié gratuitement avec GitHub Pages : dans le dépôt, **Settings → Pages**,
choisir **Branch : main** puis **Save**. Le jeu est mis à jour automatiquement à chaque
modification de `main`.
