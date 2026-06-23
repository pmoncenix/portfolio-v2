---
layout: default
modal-id: 10
date: 2026-01-25
img: mango.png
alt: Interface de combat du projet Arènes du Mordor
project-date: Janvier 2026
client: Projet scolaire BUT3 Informatique
category: Développement Web
images:
  - mango1.png
  - mango2.png
description: Arènes du Mordor est une application Angular réalisée individuellement dans le cadre du projet M.A.N.G.O. Elle reprend le principe de Tour of Heroes pour proposer une gestion complète de héros et d'armes. L'utilisateur peut créer, modifier, supprimer, filtrer et trier les deux types de ressources. Chaque héros dispose d'un budget de caractéristiques à répartir, tandis que les armes appliquent des bonus et des malus dont la somme doit rester équilibrée. <br><br> Les règles métier empêchent notamment d'équiper une arme qui ferait descendre une caractéristique sous son minimum. Les données sont persistées à distance dans Firebase Firestore et chaque action importante est signalée dans l'interface. En complément des fonctionnalités CRUD, une arène permet de sélectionner deux héros, de prendre en compte leurs armes et de simuler un combat tour par tour jusqu'à la victoire de l'un des participants.
objectifs:
  - objectif: Développer une application Angular complète autour de ressources liées et de règles métier
  - objectif: Assurer la persistance distante des héros et des armes avec Firebase Firestore
  - objectif: Proposer une interface de gestion ergonomique avec recherche, tri, validation et retours utilisateur
  - objectif: Ajouter une simulation de combat exploitant les caractéristiques cumulées des héros et de leurs armes
individuel:
  - travail: Conception et réalisation de l'ensemble de l'application, du modèle de données à l'interface
  - travail: Développement des opérations CRUD et des formulaires validant les règles d'équilibrage
  - travail: Intégration de Firebase Firestore dans les services Angular pour la persistance distante
  - travail: Implémentation du moteur de combat tour par tour et de son journal détaillé
competences:
  - competence: Développement avancé avec Angular, TypeScript, composants autonomes et formulaires
  - competence: Modélisation et validation de règles métier portant sur des objets liés
  - competence: Intégration d'une base de données distante avec Firebase Firestore
  - competence: Conception d'une interface responsive proposant tri, filtres et retours d'action
technologies:
  - name: "Angular"
  - name: "TypeScript"
  - name: "Firebase"
  - name: "Git"
---
