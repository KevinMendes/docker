# Image et Conteneur


## Image

Une image, comme son homonyme, est un fichier immuable qui est une capture d'un moment, ici, d'un conteneur.

Une image est donc le fichier qui nous permettra de monter un conteneur, ce conteneur sera démarré dans les mêmes conditions qu'au moment où l'image a été créée. 

Les images peuvent être créée de 4 manières différentes.

- Via un Dockerfile
  - Cette méthode permet via un simple fichier text de définir quel programme doit être intégré à l'image et quels sont les commandes à effectuer au démarrage du conteeneur.

- Via la commande docker pull NomDeLimage (ex: `docker pull ubuntu`)
  - Une image va être directement téléchargée depuis le site [docker-hub](https://hub.docker.com/).

- Via Docker Compose
  - Docker compose permet d'assembler des images afin de faire du multi-container. C'est l'outil le plus puissant de docker qui utilise des fichier docker-compose.yml pour fonctionner.

- Via la commande docker load
  - Cette commande permet de charger une image qui vous a été envoyé au préalable. 


## Conteneur

Un conteneur est une instance exécutable d'une image. Nous pouvons créer plusieurs conteneur à partir d'une même image, chaque conteneur sera indépendant. Le conteneur est donc ce qui "fonctionne", est l'état vivant, là où l'image elle est statique, n'est qu'une photo d'un instant représentant l'état initial des futurs conteneur.



Vous pouvez maintenant passer à la pratique avec la [création de votre premier conteneur](../3_Run_d_un_conteneur/run_conteneur.md)