# Application de gestion de tâches

Cette application Java permet de gérer une liste de tâches avec les fonctionnalités suivantes :

- Ajouter une nouvelle tâche avec un titre et une description
- Marquer une tâche comme terminée
- Générer et afficher un rapport des tâches terminées et non terminées

## Fonctionnalités

### 1. Ajouter une nouvelle tâche
L'application permet d'ajouter des tâches avec un titre et une description. Chaque tâche est initialement marquée comme "non terminée".

### 2. Marquer une tâche comme terminée
Les tâches peuvent être marquées comme "terminées" en fonction de leur index dans la liste.

### 3. Générer un rapport des tâches
L'application permet de générer deux rapports :
- **Tâches terminées** : Affiche les tâches qui ont été complétées.
- **Tâches non terminées** : Affiche les tâches qui n'ont pas encore été complétées.

## Structure du projet

L'application est organisée selon le principe de **Responsabilité Unique (SRP)**. Voici la description des classes principales :

### Classe `Task`
Cette classe représente une tâche individuelle avec :
- `title` : Le titre de la tâche
- `description` : La description de la tâche
- `completed` : Le statut de la tâche (terminée ou non terminée)

### Classe `TaskManager`
Cette classe est responsable de la gestion de la liste des tâches. Elle permet :
- d'ajouter des tâches,
- de marquer des tâches comme terminées,
- de récupérer la liste des tâches.

### Classe `TaskReport`
Cette classe est responsable de la génération et de l'affichage des rapports. Elle permet :
- d'afficher les tâches terminées,
- d'afficher les tâches non terminées.

## Realisé par :
- LAASRI Zaid
- ADANSAR Abdellah
