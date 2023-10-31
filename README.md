# Projet Web Sémantique avec Jena SPARQL, Spring Boot, Protégé et Angular

Ce projet démontre l'utilisation de Jena SPARQL, Spring Boot, Protégé et Angular pour travailler avec des données sémantiques, générer un fichier RDF, et afficher les résultats de requêtes SPARQL dans une interface front-end Angular.

## Table des matières

1. [Introduction](#introduction)
2. [Configuration requise](#configuration-requise)
3. [Installation](#installation)
4. [Utilisation](#utilisation)
5. [Structure du projet](#structure-du-projet)
6. [Contribution](#contribution)

## Introduction

Ce projet vise à démontrer comment intégrer des technologies sémantiques dans une application Web. Voici un aperçu des composants clés du projet :

- **Jena SPARQL :** Utilisé pour interroger des données RDF et effectuer des opérations SPARQL.
- **Spring Boot :** Utilisé pour créer une API REST qui communique avec la partie front-end.
- **Protégé :** Utilisé pour la génération de fichiers RDF à partir de données sémantiques.
- **Angular :** Utilisé pour créer une interface utilisateur permettant de saisir des requêtes SPARQL et afficher les résultats.

## Configuration requise

Assurez-vous d'avoir installé les éléments suivants avant de commencer :

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Maven](https://maven.apache.org/)
- [Node.js](https://nodejs.org/)
- [Angular CLI](https://cli.angular.io/)

## Installation

1. Clonez le dépôt depuis GitHub :
git clone https://github.com/votreutilisateur/votre-projet.git


2. Accédez au répertoire du projet :
cd Web-semantique


3. Installez les dépendances Maven pour le backend :
mvn install


4. Accédez au répertoire frontend pour installer les dépendances Angular :
cd frontend
npm install


## Utilisation

- Démarrez le backend Spring Boot :
mvn spring-boot:run

- Démarrez le serveur de développement Angular depuis le répertoire frontend :
ng serve


- Accédez à l'application Web à l'adresse [http://localhost:4200](http://localhost:4200).

## Structure du projet

- `backend/` : Contient le code source de l'application Spring Boot.
- `frontend/` : Contient le code source de l'application Angular.
- ...

## Contribution

Les contributions sont les bienvenues ! Si vous souhaitez contribuer à ce projet, veuillez suivre ces étapes :

1. Fork du projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Validez vos changements (`git commit -am 'Ajout d'une nouvelle fonctionnalité'`)
4. Poussez votre branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Ouvrez une demande d'extraction sur GitHub
