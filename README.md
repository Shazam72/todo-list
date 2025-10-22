# Projet de test pratique - Liste de tâches

## Objectif
Créer une application simple de gestion de tâches (To-Do List) avec une API REST.

## Tâches

### Front-End :
Construire une interface simple pour afficher une liste de tâches.
  - Permettre aux utilisateurs d'ajouter, de supprimer, modifier et de marquer des tâches comme complètes.
  - Les taches peuvent comporter des bannières
  - Utiliser le framework React.

### Back-End :
Créer une API REST en utilisant Laravel pour gérer les tâches.
  - Points d'API à créer :
    - **POST /register** : Création de compte
    - **POST /login** : Authentification
    - **GET /tasks** : Récupérer toutes les tâches.
    - **POST /tasks** : Ajouter une nouvelle tâche.
    - **DELETE /tasks/:id** : Supprimer une tâche par son ID.
    - **PUT /tasks/:id** : Mettre à jour le statut d'une tâche.
  - Intégrer la gestion d'images commes des bannières pour les tâches
  
### Base de données :
  - Utiliser une base de données (par exemple MySQL ou PostgreSQL ou MongoDB) pour stocker les tâches.
  - Écrire les modèles et migrations pour la base de données si nécessaire.

### Arborescence
  ```
  todo-list/
  ├── front-end/ # fait avec ReactJS
  ├── back-end/  # fait avec Laravel
  ```

### Contrôle de version :
  - Utiliser Git pour le contrôle de version.
  - Pousser le code terminé sur le dépôt GitHub suivant :
    [https://github.com/Shazam72/todo-list](https://github.com/Shazam72/todo-list)

### Délai
La deadline pour ce projet est pour **le Vendredi 28 Février 2025**.

## Procédure de contribution au projet

### 1. Fork du projet
  - Allez sur le dépôt GitHub du projet : [https://github.com/Shazam72/todo-list](https://github.com/Shazam72/todo-list).
  - Cliquez sur le bouton **Fork** en haut à droite pour créer une copie du dépôt sur votre propre compte GitHub.

### 2. Clone du dépôt
  - Clonez votre fork localement en utilisant la commande suivante dans votre terminal :
    ```bash
    git clone https://github.com/votre-nom-d-utilisateur/todo-list.git
    ```
  - Accédez au répertoire du projet :
    ```bash
    cd todo-list
    ```

### 3. Créez une nouvelle branche
  - Avant de commencer à travailler sur une fonctionnalité, créez une nouvelle branche pour vos modifications :
    ```bash
    git checkout -b nom-de-votre-branche
    ```

### 4. Développer les fonctionnalités
  - Travaillez sur les fonctionnalités assignées dans le projet (front-end, back-end, base de données, etc.).
  - N'oubliez pas de tester vos modifications en local avant de les valider.

### 5. Commiter les modifications
  - Ajoutez vos fichiers modifiés à l'index Git :
    ```bash
    git add .
    ```
  - Créez un commit avec un message clair et descriptif :
    ```bash
    git commit -m "Description de votre modification"
    ```

### 6. Push vers GitHub
  - Poussez vos modifications sur votre fork GitHub :
    ```bash
    git push origin nom-de-votre-branche
    ```

### 7. Créer une Pull Request
  - Une fois vos modifications poussées sur GitHub, ouvrez une **Pull Request** (PR) pour proposer vos changements au dépôt principal.
  - Allez sur la page de votre fork et cliquez sur le bouton **Compare & pull request**.
  - Ajoutez une description détaillée, puis soumettez la PR pour révision.

### 8. Révision et fusion
  - Le responsable du projet examinera votre Pull Request et pourra demander des modifications supplémentaires si nécessaire.
  - Une fois validée, votre PR sera fusionnée dans le dépôt principal.

### 9. Synchronisation avec le dépôt principal
  - N'oubliez pas de synchroniser votre fork avec le dépôt principal avant de commencer de nouvelles tâches. Utilisez les commandes suivantes :
    ```bash
    git remote add upstream https://github.com/Shazam72/todo-list.git
    git fetch upstream
    git merge upstream/main
    ```

## Entretien

Un entretien technique aura lieu le **Lundi 27 Octobre 2025** à **10h30** au siège de Legrand WEB Services à Nagrin, Ouagadougou.

Nous discuterons des points suivants :
  - Les technologies front-end et back-end utilisées.
  - L'architecture et la conception de l'application.
  - Les points d'API REST créés et les choix de conception qui ont guidé leur création.
  - L'évaluation des fonctionnalités principales de l'application, notamment la gestion des tâches (ajout, suppression, marquage comme complètes).
  - L'examen de l'historique des commits Git dans le dépôt GitHub et l'organisation des commits.

## Conseils et Ressources

### Conseils:

- Avant de commencer, assurez-vous de comprendre les exigences et les fonctionnalités attendues pour le projet
- Utilisez les routes, les contrôleurs et les modèles de Laravel pour créer une API REST robuste et sécurisée
- Utilisez les requêtes et les réponses pour gérer les interactions entre l'API et les clients
- Le résultat compte dans l'évaluation de la performance mais le processus de travail et de réflexion sera le point clé (sinon le plus important) dans l'évaluation alors prenez votre temps ; )
- N'hésitez à me contacter en cas d'incompréhension:
  - Email: **[jf.zouba@legrandwebservices.com](mailto:jf.zouba@legrandwebservices.com)**
  - Teléphone/Whatsapp: **[+226 56698331](tel:+22656698331)**

### Ressources et liens utiles

-  Freecodecamp: [https://www.freecodecamp.org/news/build-a-todo-app-from-scratch-with-reactjs/](https://www.freecodecamp.org/news/build-a-todo-app-from-scratch-with-reactjs/)
-  ReactJS Docs: [https://react.dev/](https://react.dev/)
-  Laravel Docs: [https://laravel.com/docs/11.x/readme](https://laravel.com/docs/11.x/readme)
