# Introduction sur l'application OUPS!

L'application OUPS! a été mise au point par le Laboratoire Santé des femmes et vieillisement, dirigé par la professeure Chantale Dumoulin (Ph.D.), physiothérapeute et professeure titulaire à l'École de réadaptation de l'Université de Montréal. Dans le cadre de leurs recherches, l’équipe et ses partenaires ont développé l'application mobile Oups!, qui offre un programme de réhabilitation pelvienne. Plus particulièrement, les utilisatrices sont guidés à travers des séries d'exercices hebdomadaires sur 12 semaines conçus pour renforcer le plancher pelvien. Elles sont accompagnées par des capsules éducatives et motivationnelles, et via utilisation d'un appareil connecté Bluetooth. Cet objet connecté doit être placé à l'intérieur du vagin des patientes afin de mesurer avec précision leurs contractions pelviennes. Basée sur des données probantes, le programme a pour but de réduire, voire éliminer, les symptômes d'incontinence urinaire chez les femmes ménopausées. L'application Oups! a été créée pour permettre à un grand nombre de femmes d'avoir accès à ce programme d'exercices.

Le laboratoire de langages de programmation et compilation dirigé par Marc Feeley (Ph. D.), professeur titulaire du DIRO, a été mandaté en mai dernier pour la seconde phase du développement de l'application. Cette phase consiste à intégrer la biofeedback de l'objet connecté Bluetooth à l'application mobile. L'été dernier, une partie de ce travail a été effectuée: développement du firmware de l'objet connecté, amélioration du UI de l'application et prototypage de l'affichage du biofeedback en temps réel lors des exercices. Le dernier point a été le coeur de mon stage l'été dernier. 

## Description détaillée
Mon travail pour le cours IFT3150 s'inscrira donc dans la continuité de mon travail. Il comportera deux volets : 
1. Intégration d'un système de biofeedback en temps réel pour l'amélioration des exercices du plancher pelvien dans l'application Oups! Le prototype actuel, que j'ai programmé en javascript, est conçu sous la forme d'un jeu permettant à la patiente de visualiser et d'ajuster ses efforts pendant les exercices. Cependant, ce prototype fonctionne uniquement dans un furteur, avec des données fictives.
2. Développement d'un algorithme afin de déterminer si les contractions du plancher pelvien sont effectuées correctement. Cette algorithme sera basé sur l'analyse des données collectées par un objet connecté Bluetooth mesurant les pressions et mouvements via des capteurs: gyroscope, accéléromètre et capteur de force.

À la fin de mon travail, le système permettra de guider les utilisatrices à travers des exercices hebdomadaires de contraction du plancher pelvien. Grâce à un objet connecté équipé de capteurs de force, d'un accéléromètre et d'un gyroscope, l'application évaluera la qualité des contractions et fournira des retours en temps réel. 

### Environnement et contraintes techniques 
L'application mobile est programmée en JavaScript, avec le framework Ionic/Angular pour la création de l'interface utilisateur et la génération d'applications iOS et Android. 

## Plan de développement
- Date de début : 20 septembre 2024
- Date de fin : 9 décembre 2024

### Autres dates prévues
- **Volet 1 : integration du biofeedback** : 20 septembre au 15 octobre
- **Vérification, testing et validation du volet 1** : 15 octobre au 1er decembre
- **Volet 2 : Developpement de l'algorithme**: 15 octobre au 15 novembre
- **Vérification, testing et validation du volet 2** : 15 novembre au 1er décembre
- **Écriture du rapport et préparation de la présentation** : 1er au 9 décembre








