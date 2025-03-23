# Projet CDAA - Application CRM en QT

## Auteurs  
- BELASSEL Meryem  
- NICOLLE Thomas  

## Description  
Ce projet a pour objectif de concevoir et réaliser une application CRM en QT permettant d'interagir avec une base de données SQLite.  

## Fonctionnalités  
- Gestion des contacts (ajout, modification, suppression, tri)  
- Gestion des interactions et des tâches associées (Todos)  
- Export des données en JSON  
- Recherche avancée (par nom, entreprise, date de création)  
- Interface graphique intuitive avec tri et filtres  
- Internationalisation (Français, Anglais, Arabe)  

## Base de données  
Le projet utilise SQLite avec les tables suivantes :  
- **Contact** : Stocke les informations des contacts  
- **Interaction** : Contient les interactions liées aux contacts  
- **Todo** : Liste des tâches associées  
- **AssociationInteractionTodo** : Gère les relations entre interactions et tâches  

## Installation et Compilation  
### Prérequis  
- Qt 5 ou supérieur  
- SQLite  

### Compilation  
1. Ouvrir un terminal et exécuter :  
   ```bash
   qmake nomProjet.pro
   make
