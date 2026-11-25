# Pong 🏓 (édition verticale)

Petit jeu Pong jouable dans le navigateur, 100 % HTML/CSS/JavaScript, sans dépendance.
Le téléphone se tient **en mode portrait** : le joueur 1 est **en bas**, l'IA (ou le joueur 2) est **en haut**.

## Comment jouer

Ouvre le jeu ici : https://heurtinstephane-reunion.github.io/pong/

- **Tactile** : glisse n'importe où sur l'écran. Moitié basse = raquette du joueur 1 (verte), moitié haute = raquette du joueur 2 (bleue, uniquement en mode 2 joueurs). La zone tactile est invisible et couvre tout l'écran. Déplacement droite/gauche uniquement.
- **Souris** : même principe, la raquette suit le curseur selon la moitié de l'écran.
- **Clavier** : flèches **← / →** ou **Q / D** (aussi **A / D**) pour la raquette du bas.
- **Bouton central du plateau** : lance la partie, met en pause (message « Pause »), reprend (les deux barres deviennent un triangle ▶) et effectue chaque remise en jeu (la balle reste collée à la raquette du serveur — celui qui vient d'encaisser sert). Il ne réagit qu'aux tapotements, pas aux glissés.
- **Remise en jeu rapide** : le serveur peut aussi lancer la balle d'un simple tapotement dans sa propre zone.
- **Menu** : bouton « ☰ Menu » en bas à gauche, **P** ou **Échap**.
- **Plein écran** : bouton « ⛶ » en bas à droite, ou touche **F**.
- Le menu, affiché verticalement, contient des réglages en direct : mode (1 joueur IA / 2 joueurs), effet (lift), durée de l'effet, vitesse de la balle, difficulté de l'IA — mémorisés localement. L'IA anticipe la trajectoire de la balle (avec rebonds sur les parois) avec une marge d'erreur qui diminue quand la difficulté augmente.
- **Couleurs des raquettes** : chaque joueur choisit sa couleur (rouge, bleu, jaune, vert ou orange).
- **Contrôles dominants (solo)** : choisis entre la souris et le clavier (flèches) — en mode clavier, la souris ne déplace plus la raquette.
- **Effet (lift)** : si la raquette bouge au moment du contact, la balle part en courbe à la manière du tennis (balle orangée + traînée). Les parois latérales transfèrent une partie de l'effet.
- Le **score** s'affiche en grand et en miroir dans chaque zone : score du joueur 2 en haut, score du joueur 1 en bas. En mode 2 joueurs, le score d'en haut est affiché à l'envers pour être lisible par le joueur 2.
- Premier à **7 points** gagne ; après chaque point, courte animation « GOAL! » horizontale affichée dans la zone de celui qui a marqué, accompagnée d'un petit son, puis remise en jeu.
- **Mise en jeu au clavier** : **↑** sert pour le joueur 1, **↓** pour le joueur 2/IA (pendant l'attente).
- **Musique** : petite musique de fond pendant la partie, bouton **♪ Musique** en bas à droite ou touche **M** pour couper/remettre.
- **Codes triche** (pendant la partie) : **B** transforme la balle en bombe à retardement qui explose au contact de la prochaine raquette (détruite pour un point, restaurée au point suivant, avec bruit d'explosion) ; **G** passe la raquette du joueur 1 en pleine largeur (invincible, rappuyer pour annuler) ; **X** dédouble la balle dans des directions aléatoires (rappuyer pour x4, etc.). Sur smartphone, trois icônes en bas au centre font la même chose : 💣 bombe, ✳ double, 🛡 raquette XL (cachée en mode 2 joueurs).
- **L'IA triche aussi** : selon la difficulté, elle peut armer une bombe, doubler la balle ou activer sa raquette XL (6 s) quand la balle repart vers vous — plus la difficulté est haute, plus souvent et plus malignement.
- Sur smartphone, le glisser vers le bas ne recharge plus la page (comportement tactile désactivé pendant le jeu).

## En local

Télécharge `index.html` et ouvre-le dans n'importe quel navigateur.

## Publication

Le site est publié gratuitement avec GitHub Pages : dans le dépôt, **Settings → Pages**,
choisir **Deploy from a branch**, branche **main**, dossier **/ (root)** puis **Save**.
Le jeu est mis à jour automatiquement à chaque modification de `main`.
