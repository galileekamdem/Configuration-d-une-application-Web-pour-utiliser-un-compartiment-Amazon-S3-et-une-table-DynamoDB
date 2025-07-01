# Configuration-d-une-application-Web-pour-utiliser-un-compartiment-Amazon-S3-et-une-table-DynamoDB
Configuration d’une application Web pour utiliser un compartiment Amazon S3 et une table DynamoDB

📁 Annuaire des Employés AWS – Application Web Cloud-Native
Ce projet est un prototype fonctionnel d'une application Web d'annuaire des employés, utilisant Amazon S3 pour le stockage d'images et Amazon DynamoDB pour la gestion des données. Il a été développé dans le cadre d'un atelier AWS et met en pratique des concepts clés en sécurité cloud, architecture scalable et intégration frontend-backend.

🚀 Fonctions principales
📸 Stockage sécurisé des photos dans Amazon S3

🧾 Gestion des données des employés via Amazon DynamoDB

🛡 Accès sécurisé avec IAM Role (EmployeeDirectoryAppRole)

🌐 Interface utilisateur simple et intuitive pour tester l’application

💻 Déploiement sur instance EC2 dans un VPC configuré

📦 Services AWS utilisés
Amazon S3 : Stockage des images des employés

Amazon DynamoDB : Base de données NoSQL pour stocker les informations

IAM : Contrôle d'accès sécurisé à travers des politiques personnalisées

EC2 : Hébergement de l'application Web

VPC & Subnets : Isolation réseau et haute disponibilité

🛠️ Étapes clés de l’implémentation
Création et configuration du compartiment S3

Application d’une politique IAM pour lecture des objets S3

Modification de l’application pour pointer vers le bon bucket

Téléversement des images dans le bucket

Création de la table DynamoDB Employees

Intégration avec l’interface Web pour affichage dynamique

Ajout, modification et suppression d’employés via l’interface ou la console AWS

🎯 Objectifs pédagogiques
Ce projet démontre :

L’intégration d’applications statiques avec des services cloud

Le contrôle d’accès basé sur les rôles IAM

La gestion d’un backend serverless avec DynamoDB

📸 Capture d'écran
(Ajoute ici une capture d'écran de l'application Web en fonctionnement)

🧠 Compétences mobilisées
Gestion des identités et autorisations AWS

Configuration réseau cloud (VPC, Subnets, IGW)

Manipulation des ressources AWS avec la console

NoSQL modeling avec DynamoDB

Communication API entre frontend et backend
