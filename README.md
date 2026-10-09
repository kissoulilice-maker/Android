
# DocuBlériot — Application Android

## Présentation

DocuBlériot est une application Android destinée à faciliter la gestion des documents numériques du Lycée Louis Blériot.

L'application a pour objectif de permettre aux utilisateurs de consulter, remplir, signer et suivre leurs documents depuis leur téléphone.

## Objectifs du projet

- Centraliser les documents associés à un compte.
- Consulter les conventions de stage et les autorisations parentales.
- Remplir les documents numériques.
- Permettre la signature et la validation des documents.
- Suivre l'avancement des signatures.
- Informer les utilisateurs lorsqu'un document nécessite leur intervention.
- Réduire l'utilisation du papier et les impressions.

## Fonctionnalités

### Gestion des documents

- Affichage des documents.
- Consultation des détails d'un document.
- Préparation de l'importation de fichiers PDF.
- Remplissage des champs d'un document.

### Circuit des cinq signatures

Une convention de stage doit pouvoir être transmise successivement aux cinq intervenants :

1. Élève ou représentant légal
2. Enseignant référent
3. Tuteur entreprise
4. Représentant de l'entreprise
5. Chef d'établissement

L'application doit afficher la progression des signatures et empêcher un intervenant de signer avant que son tour soit arrivé.

### Notifications

- Notification lors de la réception d'un nouveau document.
- Rappel des documents à compléter ou à signer.
- Suivi de l'état de validation.

## Technologies utilisées

- Kotlin
- Jetpack Compose
- Android Studio
- SharedPreferences pour certaines données locales
- PHP pour l'API serveur prévue
- MySQL pour la base de données serveur prévue
- DocuSeal pour le circuit de signature prévu

## Installation

### Prérequis

- Android Studio
- Kotlin et Jetpack Compose
- Un téléphone Android ou un émulateur compatible

### Lancement

1. Ouvrir le projet dans Android Studio.
2. Attendre la synchronisation Gradle.
3. Sélectionner la configuration `app`.
4. Connecter un téléphone ou démarrer un émulateur.
5. Cliquer sur **Run ▶**.

## Sécurité

Le projet devra prévoir :

- Une authentification sécurisée.
- Des autorisations selon le rôle de chaque utilisateur.
- La protection des documents et des signatures.
- Une communication HTTPS en production.
- Un historique des actions et des validations.

## État du projet

DocuBlériot est en cours de développement.

L'intégration complète du serveur, de la base de données, des notifications et du circuit des cinq signatures doit être testée avant une utilisation réelle.

## Informations

- **Nom :** DocuBlériot
- **Établissement :** Lycée Louis Blériot
- **Plateforme :** Android
- **Langage :** Kotlin
- **Objectif :** Gestion numérique des documents et suivi des signatures
