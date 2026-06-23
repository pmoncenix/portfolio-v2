---
layout: default
modal-id: 9
date: 2025-11-14
img: cs2api.png
alt: Documentation OpenAPI de l'API eSport CS2
project-date: Automne 2025
client: Projet scolaire BUT3 Informatique
category: Développement Web/API
images:
  - cs2api1.png
description: API eSport CS2 est une API REST développée avec Node.js pour gérer les données d'un écosystème compétitif Counter-Strike 2. Le modèle couvre les tournois, les équipes, les joueurs, les matchs et les cartes, ainsi que leurs relations. Chaque ressource dispose d'opérations de consultation, création, modification et suppression, complétées par des routes dédiées comme la composition d'une équipe ou les matchs associés à un tournoi. <br><br> Le projet a été mené avec une approche « API first ». J'ai d'abord décrit les ressources, les schémas, les paramètres, les réponses et les codes HTTP dans une spécification OpenAPI 3.0, puis généré et complété le squelette du serveur avec oas3-tools. Les données de démonstration sont chargées depuis des fichiers JSON et les modifications y sont persistées. Une documentation interactive Swagger UI permet enfin de découvrir et de tester les différents endpoints.
objectifs:
  - objectif: Concevoir une API REST cohérente pour un domaine comportant plusieurs ressources liées
  - objectif: Formaliser le contrat de l'API avec une spécification OpenAPI complète
  - objectif: Implémenter les opérations CRUD, la pagination et une gestion adaptée des réponses HTTP
individuel:
  - travail: Modélisation des tournois, équipes, joueurs, matchs et cartes CS2
  - travail: Rédaction de la spécification OpenAPI et génération du squelette du serveur
  - travail: Implémentation des contrôleurs, services et règles de persistance dans les fichiers JSON
  - travail: Création d'un client de démonstration pour vérifier les principaux scénarios CRUD
competences:
  - competence: Conception et développement d'une API REST avec Node.js
  - competence: Documentation d'un contrat d'API avec OpenAPI et Swagger UI
  - competence: Gestion des codes HTTP, de la pagination et des relations entre ressources
  - competence: Structuration d'une application serveur en contrôleurs, services et couche de données
technologies:
  - name: "Node.js"
  - name: "Swagger"
  - name: "JSON"
  - name: "Git"
---
