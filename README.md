# Dockerisation d'un Projet Spring Angular Existant

Ce projet vise à dockeriser un projet Web full-stack existant utilisant Spring Boot pour le back-end et Angular pour le front-end.

## Objectif

Dockeriser l'application pour améliorer la portabilité, l'efficacité et la gestion des dépendances.

## Choix de Configuration

### Utilisation d'Images Alpine Linux

Pour optimiser la taille des images Docker, nous avons choisi d'utiliser des images Alpine Linux plutôt que des images standard. Cela réduit la taille des images tout en maintenant la fonctionnalité nécessaire.

### Utilisation de Docker Compose

Docker Compose est utilisé pour orchestrer les conteneurs du back-end et du front-end. Cela simplifie le processus de déploiement en permettant de définir et de gérer les services dans un fichier unique.

### Gestion des Données Persistantes avec des Volumes Docker

Les volumes Docker sont utilisés pour gérer la persistance des données. Cela garantit que les données, par exemple celles de la base de données, survivent aux redémarrages des conteneurs.

### Utilisation d'un Réseau Docker

Un réseau Docker est créé pour permettre la communication entre les conteneurs du back-end et du front-end. Cela garantit une communication fluide entre les services.

## Étapes de Dockerisation

1. **Analyse du Projet Existant :** Explorez la structure du projet, identifiez les dépendances et les services externes.

2. **Configuration Docker :**
   - Fichier Dockerfile pour Spring Boot.
   - Fichier Dockerfile pour Angular.

3. **Configuration Docker Compose :** Créez un fichier `docker-compose.yml` pour orchestrer les conteneurs.

4. **Construction et Exécution :** Utilisez `docker-compose up` pour construire et démarrer les conteneurs.

5. **Optimisations Docker :**
   - Utilisation d'images Alpine Linux.
   - Configuration des conteneurs avec des variables d'environnement.

6. **Gestion des Données Persistantes :** Utilisez des volumes Docker pour assurer la persistance des données.

7. **Docker Network :** Utilisez un réseau Docker pour la communication entre les conteneurs.

8. **Documentation :**
   - Documentez chaque étape dans le fichier README.md.
   - Ajoutez une documentation détaillée sur la façon de dockeriser le projet.

## Livrables

- **Dépôt Git :** [Lien vers le dépôt Git](lien_vers_le_depot_git)
- **Document Expliquatif :** Consultez le fichier `README.md` pour des détails sur la dockerisation du projet.

N'hésitez pas à ajuster cette documentation en fonction des spécificités de votre projet.
