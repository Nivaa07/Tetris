Membres de l’équipe : Éric CISSÉ, Kevin KOUAME et Nivaashini SASIBASKARAN

Pour lancer le jeu, il faut lancer la classe Tetris.java. 
Une fois que vous avez lancé le jeu, voici quelques régles pour y jouer.


FONCTIONNEMENT DU JEU  

-	la flèche gauche pour déplacer la pièce vers la gauche 
-	la flèche droite pour deplacer la pièce vers la droite 
-	la fleche d’en haut ou d’en bas pour tourner la pièce
-	la touche espace pour descendre d’un coup  
-	la touche P pour mettre le jeu en pause et ré-appuyez dessus pour continuer
-	la touche R pour recommencer le jeu 
-	la touche X  pour afficher les 5 meilleurs scores


EXERCICE ARCHITECTURE 

Pour suivre notre architecture, vous trouverez dans les fichiers, le fichier : “TetrisProjectArchitecture”. 
C’est un diagramme UML, en classe expliquant la structure de notre projet. Nous avons opter pour une architecture MVC. C’est-à-dire que nous avons la partie utilisateur et la partie interface,qui sont gérer par le contrôleur.

Notre projet est composé de 3 classes principales. 
Nous avons les classes : 
-	Shapes, la classe qui génère les formes de nos pieces (Tétrominos).
-	Board, la classe qui s’occupe du fonctionnement du jeu.
-	Tetris, la classe qui génère la fenêtre et qui lance le jeu.


EXERCICE SOLID 


Nous avons utilise 3 principes du SOLID 

S -> Single Responsibility Principle -> Chaque classe a une seule et unique responsabilité. En effet chacune de nos classes ont un rôle bien précis dans ce jeu. Une classe qui s’occupe de l’interface du jeu, une autre classe qui s’occupe du fonctionnement du jeu et la dernière classe qui génère les formes des Tetrominos.
Ce principe nous a permis de mieux construire notre jeu.

I-> Interface Segregation Principle ->  l’utilisateur ne doit pas implémenter des méthodes inutiles que l’on utilise pas .  En effet , dans chacune de nos classes, les méthodes ont toutes une importance dans la construction du projet. Aucunes de nos méthodes sont inutiles.


D - > Dependency Inversion Principle -> les classes du bas ne dépendent pas des classes du haut.  
Il faut savoir que chacune de nos classes sont ordonné selon leur importance. 





