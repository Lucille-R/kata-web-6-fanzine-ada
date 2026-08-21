# Notes
## Q1 : Pourquoi le résultat du défi 1b change quand on redimensionne la fenêtre ?
::first-line ne s'applique que sur la 1ère ligne, il est donc normal qu'en redimensionnant la page, le nombre de mots de cette 1ère ligne soit modifié, et donc les mots qui redescendent en 2nde ligne ne sont plus en capitale.

## Q2 : Un pseudo-élément ::before est-il lisible par un lecteur d'écran ? Qu'est-ce que ça implique pour ce qu'on y met ?
Le pseudo-élément ::before n'est pas toujours accessible de manière fiable par les lecteurs d'écran. Il est alors déconseillé de s'en servir pour ajouter du contenu.