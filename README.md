# DocuBlériot

Application Android de gestion des documents numériques du Lycée Louis Blériot.

## Présentation

DocuBlériot a pour objectif de simplifier la gestion, le remplissage, la signature et le suivi des documents administratifs depuis un téléphone Android ou un ordinateur.

Le projet vise à limiter les impressions papier et à centraliser les documents des utilisateurs.

## Fonctionnalités

### Gestion des documents
- Consulter ses documents.
- Accéder aux détails d'un document.
- Remplir les champs des formulaires.
- Prévoir l'importation et la consultation de fichiers PDF.
- Suivre le statut des documents.

### Documents pris en charge
- Convention de stage.
- Autorisation parentale.
- Fiche administrative.
- Documents de l'établissement.

### Circuit de signature

Le circuit de signature prévu comprend cinq intervenants :

1. Élève ou représentant légal.
2. Enseignant référent.
3. Tuteur entreprise.
4. Représentant de l'entreprise.
5. Chef d'établissement.

Chaque intervenant doit pouvoir signer lorsque le document lui est transmis. La progression des signatures doit être visible dans l'application.

### Notifications
- Réception de nouveaux documents.
- Documents en attente de remplissage.
- Documents en attente de signature.
- Suivi des validations.

## Technologies

- **Langage :** Kotlin
- **Interface :** Jetpack Compose
- **IDE :** Android Studio
- **Stockage local :** SharedPreferences pour certaines données
- **Serveur prévu :** PHP
- **Base de données prévue :** MySQL
- **Gestion des signatures prévue :** DocuSeal

## Installation et lancement

1. Ouvrir le projet dans Android Studio.
2. Attendre la synchronisation Gradle.
3. Connecter un téléphone Android ou démarrer un émulateur.
4. Sélectionner la configuration `app`.
5. Cliquer sur **Run** pour compiler et lancer l'application.

## Sécurité

Les évolutions du projet devront intégrer :
- Une authentification des utilisateurs.
- Des droits d'accès adaptés aux rôles.
- La protection des documents et des signatures.
- Une connexion HTTPS en production.
- Un historique des signatures et des validations.

## État du projet

DocuBlériot est en cours de développement. La connexion complète au serveur, l'automatisation des cinq signatures et la génération des PDF finaux doivent être intégrées et testées avant une utilisation réelle.

## Informations du projet

- **Nom :** DocuBlériot
- **Établissement :** Lycée Louis Blériot
- **Plateforme :** Android
- **Langage :** Kotlin
- **Objectif :** Gestion numérique des documents et suivi des signatures
