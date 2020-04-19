# Présentation de *revueincroyable.github.io*


## Choix du contenu

### Pourquoi ce thème ?
Nous sommes tous les deux des “**G4M3R**”, c’est-à-dire que nous jouons beaucoup aux jeux vidéo. Nous pensons avoir une expérience et une connaissance importantes dans ce sujet. Nous avons décidé d’aborder le sujet des jeux vidéo afin de partager notre passion (en réalité, Alex voulait absolument parler de ses claviers, il a donc eu droit à sa page, comme nous le verrons ensuite).

### Pourquoi ce nom ?
Notre site a pour vocation de présenter plusieurs jeux vidéo, logiciels et périphériques et d’en faire une critique. Il nous fallait un nom accrocheur et simple à retenir. Après une longue réunion auprès de nos ~~actionnaires~~ membres, nous avons voté et choisi Revue Incroyable (2 voix pour, 0 contre, 0 abstentions).

### Pourquoi ces jeux ?
Nous avons décidé d’évoquer des jeux qui nous ont marqué que ce soit par leur histoire ou par leur style. Ainsi, nous n’avons sélectionné que des jeux pour lesquels l’un de nous deux a plusieurs dizaines d’heures de jeu.

### Pourquoi une page clavier ?
Alex souhaitant écrire une page sur les claviers mécaniques, il a été nécessaire ~~de céder à son caprice~~ d’intégrer sa page. Ce périphérique étant important pour pouvoir jouer convenablement, cet ajout a apporté une plus-value importante.


## Choix techniques

### Site moderne
Le site [revueincroyable](https://revueincroyable.github.io) est écrit en HTML5 et CSS. Il est compatible avec les navigateurs récents (de toutes façons, les véritables “**G4M3R**” possèdent un système à jour ~~et utilisent Chrome comme tout le monde~~).

### Site responsive
Le site utilise flexbox pour lui permettre d’être utilisé sur tous supports, même si la fenêtre est réduite. Plusieurs pages possèdent des images situées à côté du texte. Ces images se retrouvent au dessus ou en dessous du texte s’il n’y a pas assez de place.

### Menu
La page d’accueil possède un menu permettant d’accéder aux autre pages. Il y a même un sous menu pour les jeux. Le menu n’est pas présent sur toutes les pages, il est remplacé par un ou deux boutons retour.

### Boutons retour
Les boutons de la page claviers et celui des autres pages permettent de revenir à la page d’accueil et en haut de la page. Ils restent toujours en haut de l’écran. Il existe une petite différence, en effet, les boutons de claviers.html ne sont pas tout en haut de la page lorsque nous arrivons dessus. En réalité, les boutons utilisent deux valeurs différentes pour l’attribut *position*. Le “Retour accueil” seul a la valeur *fixed*, il sera toujours à la même place sur l’écran, en revanche, les deux boutons de claviers.html ont la valeur *sticky* qui leur permet de se comporter de deux manières différentes. Par défaut, l’élément se déplace normalement sur l’écran en fonction du défilement, cependant, lorsqu’il atteint une certaine hauteur (ici *1%*), il se comporte comme s’il avait la valeur *fixed*.
