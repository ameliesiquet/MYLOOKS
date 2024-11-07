# MYLOOKS -Votre garde-robe virtuelle

Le projet MYLOOKS est une application mobile réalisée pour le cours de Développement d’Application Mobile à l’HEPL. 
L'application **MyLooks** répond au besoin des utilisateurs de gérer et organiser facilement leur garde-robe, créer des tenues, et s'inspirer de nouveaux looks.

## Table de matières
- **Architecture du projet**
- **Etude de l'existant**
- **Public cible**
- **Fonctionalités**



## Architecture du Projet
Le répertoire lib est organisé de manière à séparer clairement les différentes composantes de l'application, facilitant ainsi la compréhension et la maintenance du code.

-  🚪 **`main.dart`**
Le point d'entrée principal de l'application. C'est ici que l'initialisation de l'application et la navigation de base commencent.

---

- 📱 **`screens`** : Contient toutes les pages principales de l'application.
  - **`login_screen.dart`** : Page de connexion pour l'authentification des utilisateurs.
  - **`register_screen.dart`** : Page d'inscription pour les nouveaux utilisateurs.
  - **`home_screen.dart`** : Page d'accueil, affichant le tableau de bord principal.
  - **`closet_screen.dart`** : Page pour visualiser la garde-robe virtuelle.
  - **`outfit_screen.dart`** : Page pour visualiser les outfits enregistrés dans l'application.
  - **`dressMe_screen.dart`** : Page qui propose des suggestions de tenues en fonction des vêtements ajoutés par l'utilisateur.
  - **`profile_screen.dart`** : Page pour ajuster les paramètres du profil.
  - **etc.** : Autres pages selon les besoins fonctionnels de l'application.
---

-  🛠️ **`services`** : Dossier pour les services de l'application
  - **`firebase_options.dart`** : Fichier de configuration pour la connexion Firebase.
  - **`notification_service.dart`** : Service pour gérer les notifications dans l'application, permettant d'envoyer des rappels et alertes personnalisées.

---

- 📦 **`widgets`** : Dossier pour les widgets de l'application
  - **`form`** : Composants de formulaires (par ex., champs de texte, boutons de validation).
  - **`services`** : Widgets associés aux services.
  - **etc.**

---

- 🎨 **`styles`**: Dossier pour les styles souvent utilisé dans l'application.
  - **`colors.dart`** : Fichier pour les couleurs utilisées dans l'application.
  - **`fonts.dart`** : Fichier pour les polices et tailles de texte.
  - **`spacing.dart`** : Fichier pour les espacements et marges.
  - **etc.** : Autres éléments de style récurrents.

---


## Étude de l'existant

## 🙋🏼‍♀️ Public cible
L'application MyLooks est conçue pour une large gamme d'utilisateurs, avec un accent particulier sur les jeunes adultes, en particulier les femmes, qui s'intéressent à la mode et à l'organisation de leur garde-robe. Cependant, elle est adaptée à tous, quel que soit l'âge, car chacun peut en tirer parti en fonction de ses besoins. 
- **Besoins** : L'application **MyLooks** répond au besoin des utilisateurs de gérer et organiser facilement leur garde-robe, créer des tenues, s'inspirer de nouveaux looks et optimiser l'utilisation de leurs vêtements tout en offrant une interface simple, intuitive et esthétique.

## 📲 Fonctionnalités
- **Gestion de la garde-robe** : L'application permet d'organiser et de catégoriser vos vêtements par type, saison, et occasion, afin d'optimiser votre garde-robe et de faciliter la création de tenues.  

- **Création de tenues personnalisées** : Vous pouvez assembler vos vêtements en différentes tenues, en sélectionnant des hauts, bas et accessoires, pour obtenir des suggestions ou voir ce qui se marie bien ensemble.  

- **Inspiration de looks** : L'application propose des idées de tenues basées sur des tendances actuelles, des saisons ou des événements spéciaux, afin d'aider à renouveler votre style et trouver des combinaisons originales.  

- **Ajout de nouveaux vêtements** : Vous pouvez ajouter de nouveaux articles à votre garde-robe en utilisant des photos depuis votre galerie, et les classer en fonction de leurs couleurs, types et catégories.  

- **Filtrage et recherche avancée** : Grâce à un système de filtres (couleurs, types de vêtements, catégories de tenues), vous pouvez rapidement trouver le vêtement ou l'outfit qui correspond à vos besoins.  

- **Gestion des tenues favorites** : Vous pouvez enregistrer vos looks préférés et les retrouver facilement pour les utiliser ultérieurement ou pour vous inspirer.  

- **Création d'outfits pour différentes occasions** : L'application permet de créer des tenues spécifiques pour des événements comme des festivals, des soirées, ou des journées d'été, avec la possibilité de filtrer les articles selon la saison ou l'occasion.






