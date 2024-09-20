# Introduction sur l'application OUPS!

L'application OUPS! a été mise au point par le Laboratoire Santé des femmes et vieillisement, dirigé par la professeure Chantale Dumoulin (Ph.D.), physiothérapeute et professeure titulaire à l'École de réadaptation de l'Université de Montréal. Dans le cadre de leurs recherches, l’équipe et ses partenaires ont développé l'application mobile Oups!, qui offre un programme de réhabilitation pelvienne. Plus particulièrement, les utilisatrices sont guidés à travers des séries d'exercices hebdomadaires sur 12 semaines conçus pour renforcer le plancher pelvien. Elles sont accompagnées par des capsules éducatives et motivationnelles, et via utilisation d'un appareil connecté Bluetooth. Cet objet connecté doit être placé à l'intérieur du vagin des patientes afin de mesurer avec précision leurs contractions pelviennes. Basée sur des données probantes, le programme a pour but de réduire, voire éliminer, les symptômes d'incontinence urinaire chez les femmes ménopausées. L'application Oups! a été créée pour permettre à un grand nombre de femmes d'avoir accès à ce programme d'exercices.

Le laboratoire de langages de programmation et compilation dirigé par Marc Feeley (Ph. D.), professeur titulaire du DIRO, a été mandaté en mai dernier pour la seconde phase du développement de l'application. Cette phase consiste à intégrer la biofeedback de l'objet connecté Bluetooth à l'application mobile. L'été dernier, une partie de ce travail a été effectuée: développement du firmware de l'objet connecté, amélioration du UI de l'application et prototypage de l'affichage du biofeedback en temps réel lors des exercices. Le dernier point a été le coeur de mon stage l'été dernier. 

Mon travail pour le cours IFT3150 s'inscrira donc dans la continuité de mon travail. Il comportera deux volets : 
1. L'intégration dans l'application mobile de l'affichage du biofeedback en temps réel lors des exercices. Cette intégration sera basée sur le prototype que j'ai programmé cet été. 
2. Développement d'un algorithme permettant de détecter les mauvaises contractions. Cet algorithme sera basé sur des données réelles, enregistrées chez des patientes.
À la fin de mon travail, l'application mobile devrait être en mesure de se connecter à l'object connecté, faire l'affichage de données captées par celui-ci, tout en détectant les mauvaises contractions lors des exercices. 



un objet connecté Bluetooth mesurant les pressions et mouvements via des capteurs: gyroscope, accéléromètre et capteur de force. Les données collectées sont analysées pour déterminer si les contractions du plancher pelvien sont effectuées correctement.

## Description détaillée
Intégration d'un système de biofeedback en temps réel pour l'amélioration des exercices du plancher pelvien dans l'application Oups!

### Spécification fonctionnelle

Le système intégré permet de guider les utilisatrices à travers des exercices hebdomadaires de contraction du plancher pelvien. Grâce à un objet connecté équipé de capteurs de force, d'un accéléromètre et d'un gyroscope, l'application évalue la qualité des contractions et fournit des retours en temps réel. Le prototype a intégré présente un jeu qui permet à la patiente de visualiser et d'ajuster ses efforts pendant les exercices. 

### Environnement et contraintes techniques : 
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

### Autres Dates prévues :
Intégration du module de traitement des données : 15 octobre 2024
Développement de l'interface de feedback en temps réel : 1er novembre 2024
Vérification et validation des modules principaux : 1er décembre 2024
Cette description devrait répondre aux exigences du cours et mettre en valeur ton travail sur le projet Oups!






