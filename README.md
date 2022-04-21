# docker

Vous suivrez au fil de ce cours sur docker, les pratiques vous permettant de comprendre et même en place cet outil dans votre écosystème.

## Qu'est-ce que docker ?

Docker est une plate-forme logicielle, permettant de créer, tester et déployer des applications rapidements, et sans risquer des problèmes de compatibilité entre les systèmes. 

Le comportement de docker est proche d'une machine virtuelle. Les conteneurs virtualisent un système d'exploitation d'un serveur. A la différence d'une machine virtuelle, un conteneur ne va virtualiser que ce qui nous intéressent pour le fonctionnement de notre application, système ou sous-système; alors qu'une machine virtuelle va virtualiser un ordinateur complet et son système d'exploitation. 
Un conteneur est donc plus légé et rapide qu'une machine virtuelle, ce qui permet d'en déployer plusieurs facilement sur une seule machine.

Les conterneurs sont fortement portables. Un conteneur peut être porté sur une autre machine et démarrer immédiatement. C'est donc un outil très adapté au travail collaboratif.