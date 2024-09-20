# IFT3150 Cours projet

INTRO DE L'APPLICATION

Le projet consiste à intégrer un prototype de "jeu" ou d'affichage de données dans l'application mobile Oups!, destinée à aider les femmes ménopausées à réduire les symptômes d'incontinence urinaire à travers un programme d'exercices. L'objectif est de permettre aux utilisatrices de suivre et d'améliorer leurs exercices de contraction du plancher pelvien en temps réel à l'aide d'un objet connecté Bluetooth mesurant les pressions et mouvements via des capteurs.

## Description détaillée
Intégration d'un système de biofeedback en temps réel pour l'amélioration des exercices du plancher pelvien dans l'application Oups!

## Spécification fonctionnelle

Le système intégré permet de guider les utilisatrices à travers des exercices hebdomadaires de contraction du plancher pelvien. Grâce à un objet connecté équipé de capteurs de force, d'un accéléromètre et d'un gyroscope, l'application évalue la qualité des contractions et fournit des retours en temps réel. Le prototype a intégré présente un jeu qui permet à la patiente de visualiser et d'ajuster ses efforts pendant les exercices. 
L'application utilise un appareil connecté Bluetooth pour capturer les données des capteurs. Les données collectées sont analysées pour déterminer si les contractions du plancher pelvien sont effectuées correctement.

## Environnement et contraintes techniques : 
L'application mobile est programmée en JavaScript, avec le framework Ionic/Angular pour la création de l'interface utilisateur et la génération d'applications iOS et Android. 
Prérequis techniques : Node.js (v16), Ionic CLI, Angular CLI, CocoaPods (pour iOS), XCode Command Line Tools.

Architecture logicielle :
L'application est divisée en plusieurs modules :

Interface utilisateur : Créée avec Angular et Ionic, elle permet l'affichage des résultats des exercices en temps réel.
Module de traitement des données des capteurs : Utilisation des données captées (force, orientation, mouvement) pour déterminer la qualité des exercices.

Système de feedback en temps réel : Affichage interactif sous forme de jeu pour guider les utilisatrices pendant leurs exercices.
Modules principaux :

Capteurs et détection des mouvements : Utilisation des données fournies par les capteurs pour évaluer la force et la direction des contractions.
Affichage interactif : Présentation des résultats via une interface graphique utilisant des éléments de jeu pour encourager la progression.
Feedback utilisateur : Détermination si l'exercice est bien ou mal effectué selon des critères prédéfinis.
Discussions avec l'usager : Tests et feedback des utilisatrices pour améliorer l'expérience et l'ergonomie.

## Plan de développement :
Date de début : 1er septembre 2024
Date de fin : 15 décembre 2024

## Autres Dates prévues :
Intégration du module de traitement des données : 15 octobre 2024
Développement de l'interface de feedback en temps réel : 1er novembre 2024
Vérification et validation des modules principaux : 1er décembre 2024
Cette description devrait répondre aux exigences du cours et mettre en valeur ton travail sur le projet Oups!






