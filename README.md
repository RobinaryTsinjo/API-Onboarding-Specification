# API-Onboarding-Specification

Ce dépôt contient la spécification YAML d'une API de gestion des étudiants. Cette spécification décrit les endpoints,
les méthodes, les réponses et les requêtes pour interagir avec l'API.

## Spécification

- Le fichier `API_Onboarding.yml` contient la spécification complète de l'API au format YAML.

## Endpoints

### `/students`

- **GET** : Récupère les informations des étudiants.
  - Réponse 200 : Renvoie les détails d'un étudiant.
  - Réponse 500 : En cas d'erreur, renvoie un message d'erreur.

- **POST** : Ajoute un nouvel étudiant.
  - Corps de la requête : Format JSON pour spécifier les détails de l'étudiant.
  - Réponse 200 : Confirme l'ajout de l'étudiant.
  - Réponse 500 : En cas d'erreur, renvoie un message d'erreur.
    
- **PUT** : Met à jour les informations d'un étudiant.
  
- **DELETE** : Supprime un étudiant.

  
### `/teachers`

- **GET** : Récupère les informations des enseignants et des cours.
  
- **POST** : Ajoute un nouvel enseignant avec des cours.

## Tags

- Les endpoints sont marqués avec les tags `Students` et `Teachers` pour une meilleure organisation.


Pour ouvrir la spécification d'API (`API_Onboarding.yml`) dans Swagger UI pour explorer les détails, voici le lien pour accéder au fichier source:
  (https://raw.githubusercontent.com/RobinaryTsinjo/API-Onboarding-Specification/main/API%20Onboarding.yml)

   


