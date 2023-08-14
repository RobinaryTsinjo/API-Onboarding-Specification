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

## Utilisation

1. Clonez ce dépôt sur votre ordinateur :

2. Ouvrez la spécification d'API (`API_Onboarding.yml`) avec un éditeur de texte ou Swagger Editor pour explorer les détails.

3. Vous pouvez également utiliser Swagger Viewer pour visualiser et tester l'API en utilisant la spécification.


