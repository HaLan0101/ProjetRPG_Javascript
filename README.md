# ProjetRPG_Javascript
 
menu.php to play

Présentation de la page :

En haut à gauche vous afficherez un encadré indiquant le nom du personnage ses points de vie ses points de magie et son or. En cliquant sur le nom du personnage, un encadré apparaît au milieu de la page présentant les caractéristiques de ce personnage (sa classe, ses points de vie, ses points de magie, son attaque, sa défense, sa magie, sa défense magique, son esquive et sa vitesse). Cet encadré aura également une croix pour le fermer et revenir sur l’affichage principale.

A droite de l’écran vous afficherez une liste d’option améliorer l’arme, la protection, la magie, restaurer les pv et mp (et autres si vous souhaitez).

En bas de l’écran un encadré présente l’historique des actions réalisées par le personnage et par l’adversaire. En dessous, une liste des actions réalisables par le joueur (attaquer, défendre, utiliser un sort, fuir)

Au centre de la page, vous pourrez afficher une image de l’adversaire ou autre.

Lorsqu’un joueur démarre, il a la possibilité de choisir sa classe (une guerrière, une magique, une stratégique, … (je vous laisse être inventif)). Chaque classe a des caractéristiques différentes. Le joueur clique sur un bouton attaquer pour lancer un combat. Un adversaire ce présente (les adversaires peuvent aussi avoir des classes différentes et des caractéristiques différentes). Vous ferez en sorte que les caractéristiques des adversaires soient toujours assez proches de celles du personnage (différence de 10% en supérieur ou inférieur par exemple).

Le personnage le plus rapide commence à attaquer. Et le combat se déroule de façon classique. A chaque dégâts, la barre de vie diminue et à l’utilisation des sorts, la barre de magie diminue. Arrivé à 0 en points de vie, le personnage a perdu.

A la victoire contre ennemi, le personnage gagne de l’or qu’il peut dépenser pour augmenter ses caractéristiques ou se soigner. A chaque achat d’augmentation de caractéristiques, le prix augmente.

Les données du personnage seront sauvegardées soit sur le localstorage, soit sur un csv.
