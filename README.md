# Conway's Game of Life
>Fait pendant la Nuit de l'informatique

Ce programme reprends le fameux jeu de la vie de John H. Conway

## Règles du jeu
>Repris directement de https://www.nuitdelinfo.com/inscription/defis/271

Le jeu se déroule sur une grille à deux dimensions, théoriquement infinie (mais de longueur et de largeur finies et plus ou moins grandes dans la pratique), dont les cases qu’on appelle des « cellules », par analogie avec les cellules vivantes — peuvent prendre deux états distincts : « vivante » ou « morte ». 
 
Une cellule possède huit voisins, qui sont les cellules adjacentes horizontalement, verticalement et diagonalement. 
 
À chaque étape, l’évolution d’une cellule est entièrement déterminée par l’état de ses huit voisines de la façon suivante : 
 *   une cellule morte possédant exactement trois voisines vivantes devient vivante (elle naît) ; 
 *   une cellule vivante possédant deux ou trois voisines vivantes le reste, sinon elle meurt. 
 
On peut également formuler cette évolution ainsi : 
 *   si une cellule a exactement trois voisines vivantes, elle est vivante à l’étape suivante. 
 *   si une cellule a exactement deux voisines vivantes, elle reste dans son état actuel à l’étape suivante.
 *   si une cellule a strictement moins de deux ou strictement plus de trois voisines vivantes, elle est morte à l’étape suivante. 

Recharger la page permet d'avoir différents patterns dont un aléatoire

---

réalisé par : 
>Rabouan Amaury | Guichoux Léo | Fabre Valentin