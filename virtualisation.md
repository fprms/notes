# La virtualisation du système de développement

## Pourquoi ?


## Docker et le système de conteneurs

Docker s’appuie sur la technologie linux qui sépare dans des conteneurs des espaces de travails distinct qui partagent les mêmes ressources (contrairement à une machine virtuelle qui embarque à chaque fois l’OS complet).

Le conteneur virtualise l’environnement d'exécution. Il faut imaginer ça comme une sorte de boîte qui va être isolée du système d’exploitation dans laquelle on va installer toutes les librairies nécessaires au fonctionnement de l’application. 

Ce principe ressemble fort au système des machines virtuelles, cependant il est plus léger. En effet, les machines virtuelles fonctionnent au dessus de la couche système et multiplie les instances d’OS pour autant de machines virtuelles nécessaires. Docker permet d’éviter cette étape. 

Facile à transporter et améliore la performance car beaucoup plus léger qu’une machine virtuelle. 

Les composants
Le Docker Deamon tourne en tâche de fond sur le serveur
Le Docker Client tourne sur la machine et permet de contrôler les conteneurs, lancer des commandes.
Boot2Docker, petite machine virtuelle qui intègre les outils de Docker.

Docker Machine :

Docker Compose : 

Qu’est-ce qu’un Cgroups ?
Qu’est-ce qu’un NameSpace ?
Quel est le rôle du contrôleur ?

Qu’est-ce qu’un hyperviseur
 

##Vagrant 
