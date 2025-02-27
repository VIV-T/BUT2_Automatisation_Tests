# Bataille Navale

## Présentation

Ce projet s'inscrit dans un contexte universitaire (2e année de BUT). Il nous a été demandé de refactorer un code python d'un jeu de bataille navale et de créer un script de tests automatisé sur le code que nous avons produit.

J'ai construit un code avec plusieurs classes, permettant de structurer et docummenter correctement le code. Après avoir développé le code - et pendant le développement, il a fallu développer un script de test avec le packages Unittest Python.

## Arborescence du code

Le jeu bataille navale peut être lancé avec le script "main".
Le classes "ChoiStrategie", "Strategie" et "CreationStrategie" sont relatif à la création, au choix et à la structure des différentes stratégie établies par le joueur ou pré-enregistrées dans le fichier "sauvegardes_strategie.txt".
La classe "Grille" permet de définir la structure des matrices utilisées comme grilles de jeu ensuite dans la classe "BatailleNavale".

Enfin la classe "Test" regroupe l'ensemble des tests unitaires automatisés, ainsi qu'un scénario de tests (simulation d'une partie fictive qui test le bon déroulement de la partie selon le scénario défini).
