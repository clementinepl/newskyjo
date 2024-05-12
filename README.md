# newskyjo
Une revisite du jeu de cartes Skyjo, rééquilibré et avec de nouvelles mécaniques

----- NEWSKYJO -----
Par Clémentine Plissonnier, Game designer Freelance

-> L'équilibrage du Skyjo original provoque des scores très écartés et aléatoires, ce que j'ai voulu corriger
-> Le jeu manque d'interactions entre joueurs, ce que j'ai changé en ajoutant des effets aux cartes.


---- MODE D'EMPLOI ----

- Comme au Skyjo classique, on distribue 12 cartes par Joueur (3 à 8 joueurs). Chaque joueur place toutes ses cartes face cachée devant lui, et les dispose en une grille de 4 cartes de longueur par 3 cartes de hauteur.
- Chaque joueur retourne 2 cartes de son jeu, celui qui a la somme la plus élevée commence. (LES EFFETS DES CARTES NE SONT PAS JOUES A CETTE  ETAPE).
- Chacun son tour un joueur peut : 
	- Retourner une carte de son jeu pour en découvrir la valeur. SI LA CARTE PORTE UN EFFET, IL DOIT l'APPLIQUER APRES AVOIR RETOURNE 	LA CARTE
	- Tirer une carte dans la pioche :
		- Si la carte lui plait, il peut l'échanger avec une des cartes de son jeu, face cachée ou retournée. SI LA CARTE PORTE UN 		EFFET, IL DOIT L'APPLIQUER AVANT DE POUVOIR LA POSER SUR SON JEU.
		- Si la carte ne lui convient pas, il peut la défausser sans jouer son effet. Il doit alors retourner une carte de son jeu.
	- Récupérer la dernière carte de la pioche. SI LA CARTE PORTE UN EFFET, IL N'EST PAS APPLIQUE
- Quand un joueur aligne verticalement trois cartes de la même valeur, ces cartes sont mises de côté et leur valeur ne comptera pas à la fin de la partie. Les cartes sont mises sur le côté et ne sont pas défaussées.
- Quand un joueur a retourné toutes ses cartes, la partie se termine. On termine le tour (chaque joueur peut jouer une dernière fois) normalement, puis tout le monde retourne les cartes qui n'ont pas encore été découvertes. ON NE JOUE PLUS LES EFFEtS A CE STADE DE LA PARTIE.
- Tout le monde calcule la somme des valeurs de ses cartes, en comptant celles qui n'avaient pas été retournées à la fin de la partie. La personne avec la somme la plus faible gagne.



---- COMPOSITION ----

La composition du jeu est aussi disponible en format csv

135 cartes avec une face identique et une face comportant un numéro de -2 à 12, et parfois un effet.

-2 : 5 cartes, dont zéro sans effet
	- Laisse la personne à ta droite échanger une de ses cartes avec une des tiennes, puis pose cette carte sur ton jeu
	- Tu peux uniquement placer cette carte en bas à gauche de ton jeu *2
	- La personne qui joue après toi joue deux fois
	- Echange ta carte la plus basse avec la dernière carte de la défausse, puis place cette carte sur ton jeu

-1 : 7 cartes, dont zéro sans effet
	- Tu peux uniquement placer cette carte en haut à gauche de ton jeu
	- Tu peux uniquement placer cette carte en haut à droite de ton jeu *2
	- La personne qui joue après toi joue deux fois*2
	- Echange ta carte la plus basse avec la dernière carte de la défausse, puis place cette carte sur ton jeu
	- Laisse la personne à ta droite échanger une de ses cartes avec une des tiennes, puis pose cette carte sur ton jeu

0 : 8 cartes, dont 2 sans effet
	- Tu peux uniquement placer cette carte en haut à droite de ton jeu
	- Tu peux uniquement placer cette carte en bas à gauche de ton jeu
	- Echange ta carte la plus basse avec la dernière carte de la défausse, puis place cette carte sur ton jeu *2
	- La personne qui joue après toi joue deux fois*2

1 : 9 cartes, dont 2 sans effet
	- Inverse la position de deux de tes cartes
	- Echange ta carte la plus basse avec la dernière carte de la défausse, puis place cette carte sur ton jeu
	- La personne qui joue après toi passe son tour *2
	- Le sens de rotation entre les joueurs est inversé
	- Tu peux uniquement placer cette carte en haut à gauche de ton jeu *2
 
2 : 11 cartes, dont 5 sans effet
	- Le sens de rotation entre les joueurs est inversé
	- Tu peux uniquement placer cette carte en bas à droite de ton jeu *2
	- Regarde les 3 prochaines cartes de la pioche et réorganise-les comme tu veux
	- La personne qui joue après toi passe son tour
	- Inverse la position de deux de tes cartes

3 : 11 cartes, dont 6 sans effet
	- La personne qui joue après toi passe son tour
	- Le sens de rotation entre les joueurs est inversé
	- Inverse la position de deux de tes cartes *2
	- Regarde les 3 prochaines cartes de la pioche et réorganise-les comme tu veux

4 : 15 cartes, dont 8 sans effet
	- 4 La personne qui joue après toi passe son tour *2
	- 4 Inverse la position de deux de tes cartes*2
	- 4 Le sens de rotation entre les joueurs est inversé*2
	- 4 Regarde les 3 prochaines cartes de la pioche et réorganise-les comme tu veux

5 : 10 cartes, dont 5 sans effet
	- La personne qui joue après toi passe son tour
	- Découvre ou échange deux cartes au lieu d'une à ce tour
	- Regarde les 3 prochaines cartes de la pioche et réorganise-les comme tu veux
	- Le sens de rotation entre les joueurs est inversé
	- Inverse la position de deux de tes cartes

6 : 10 cartes, dont 5 sans effet
	- La personne qui joue après toi passe son tour
	- Le sens de rotation entre les joueurs est inversé
	- Echange entre elles deux cartes d'autres joueureuses
	- Inverse la position de deux de tes cartes
	- Regarde les 3 prochaines cartes de la pioche et réorganise-les comme tu veux

7 : 8 cartes, dont 3 sans effet
	- Echange entre elles deux cartes d'autres joueureuses
	- Le sens de rotation entre les joueurs est inversé
	- La personne qui joue après toi passe son tour
	- Inverse la position de deux de tes cartes
	-  Regarde les 3 prochaines cartes de la pioche et réorganise-les comme tu veux

8 : 8 cartes, dont 4 sans effet
	- Inverse la position de deux de tes cartes
	- La personne qui joue après toi doit utiliser la dernière carte de la défausse
	- Echange une de tes cartes avec celle de quelqu'un d'autre, puis place cette carte sur ton jeu
	- Découvre ou échange deux cartes au lieu d'une à ce tour

9 : 8 cartes, dont 3 sans effet
	- Echange une de tes cartes avec celle de quelqu'un d'autre, puis place cette carte sur ton jeu *2
	- Inverse la position de deux de tes cartes
	- La personne qui joue après toi doit utiliser la dernière carte de la défausse *2

10 : 7 cartes, dont 2 sans effet
	- Inverse la position de deux de tes cartes *2
	- Découvre ou échange deux cartes au lieu d'une à ce tour *2
	- La personne qui joue après toi doit utiliser la dernière carte de la défausse

11 : 9 cartes, dont 2 sans effet
	- Echange une de tes cartes avec celle de quelqu'un d'autre, puis place cette carte sur ton jeu
	- Découvre ou échange deux cartes au lieu d'une à ce tour *2
	- La personne qui joue après toi doit utiliser la dernière carte de la défausse *2
	- Inverse la position de deux de tes cartes *2

12 : 9 cartes, dont 3 sans effet
	- La personne qui joue après toi doit utiliser la dernière carte de la défausse
	- Echange une de tes cartes avec celle de quelqu'un d'autre, puis place cette carte sur ton jeu *2
	- Découvre ou échange deux cartes au lieu d'une à ce tour
	- Inverse la position de deux de tes cartes *2





