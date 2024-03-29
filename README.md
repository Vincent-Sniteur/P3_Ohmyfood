﻿ ### Projet 3 Ohmyfood - Dynamiser un site web avec des animations CSS - OpenClassroom

 ### Création du site Ohmyfood! Paris

* Ohmyfood est une entreprise de commande de repas en ligne. Notre concept permet aux
utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les
restaurants car leur menu est préparé à l’avance. Plus de perte de temps à consulter la carte !


***
### Pages à intégrer : 
* Pages d'accueil
* Pages de menu (4 au total)

#### Animations
##### Boutons
* Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
* À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol au lieu du clic.

##### Page d'accueil
* Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

##### Pages de menu
* À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrées”, “Plats” et “Desserts”. 
* Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.


## Technologies
***
* Autorisées : HTML, CSS, préprocesseur CSS > SASS
* Interdites : JavaScript, inline CSS

### Identité graphique

Polices :
* Logo et titres : Shrikhand
* Texte : Roboto

Couleurs :
* Primaire: #9356DC
* Secondaire: #FF79DA
* Tertiaire: #99E2D0

### Compatibilité
Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre.
* L’ensemble du site devra être responsive sur mobile, tablette et desktop.
* Les pages devront passer la validation W3C en HTML et CSS sans erreurs.
* Le site doit être parfaitement compatible avec les dernières versions desktop de
Chrome et Firefox.

### DEV Dependencies
SASS : npm run sass-watch
