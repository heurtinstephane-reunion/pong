# Pong 🏓

Petit jeu Pong jouable dans le navigateur, 100 % HTML/CSS/JavaScript, sans dépendance.

## Comment jouer

Ouvre le jeu ici : https://heurtinstephane-reunion.github.io/pong/

- **Souris** ou flèches **↑ / ↓** (aussi **W / S**) pour bouger la raquette
- **Tactile** : glisse n'importe où sur l'écran, la raquette suit (zone invisible plein écran)
- **2 joueurs** (dans le menu) : tactile moitié gauche = joueur 1, moitié droite = joueur 2 (ou W/S vs ↑/↓ au clavier)
- **Bouton central du plateau** : lance la partie, met en pause (message « PAUSE »), reprend (le bouton devient un triangle ▶) et effectue chaque remise en jeu (la balle attend collée à la raquette du serveur)
- **Menu** : bouton « ☰ Menu » en haut à droite, **P** ou **Échap**
- Le menu contient des réglages en direct : mode (1 joueur IA / 2 joueurs), puissance et durée du lift, vitesse de la balle, difficulté de l'IA, orientation du plateau (auto / paysage forcé / jamais) — mémorisés localement
- **Effet (lift)** : si la raquette bouge au moment du contact, la balle part en courbe à la manière du tennis (balle orangée + traînée)
- Premier à **7 points** gagne ; l'animation « GOAL! » précède la remise en jeu par celui qui encaisse
- **Mobile / orientation** : bouton **⟲** (touche **R**) pour basculer entre les deux sens de paysage (et revenir à l'affichage droit) ; le menu propose aussi Auto / Paysage ↻ / Paysage ↺ / Jamais. Boutons et menu pivotent avec le plateau (☰ à gauche, ⟲ et ⛶ à droite)
- **Plein écran** : bouton **⛶** (touche **F**)

## En local

Télécharge `index.html` et ouvre-le dans n'importe quel navigateur.

## Publication

Le site est publié gratuitement avec GitHub Pages : dans le dépôt, **Settings → Pages**,
choisir **Branch : main** puis **Save**. Le jeu est mis à jour automatiquement à chaque
modification de `main`.
