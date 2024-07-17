# Lab: Amélioration du Projet Dataform avec JavaScript

Pour intégrer JavaScript de manière robuste dans Dataform, le processus commence par la création soignée de fichiers JavaScript dans le répertoire `includes/`. Ceux-ci serviront de référence centrale pour organiser et réutiliser des fonctions, des constantes et d'autres objets nécessaires à vos transformations de données. En suivant une méthodologie structurée, voici comment vous pouvez enrichir votre projet existant dans Dataform en introduisant et en exploitant JavaScript de manière efficace :

## Objectif du Lab

L'ajout de scripts JavaScript dans notre projet Dataform représente une étape significative vers une gestion plus structurée et réutilisable du code. Ces fichiers nouvellement créés serviront à consolider la documentation, à définir des constantes applicables à l'ensemble du projet, et à encapsuler des fonctions utiles pour manipuler et transformer les données de manière cohérente.

En structurant ces fichiers dans le répertoire `includes/`, vous créez une base solide pour gérer la complexité croissante des opérations de transformation de données. Chaque fichier JavaScript peut être conçu pour remplir des rôles spécifiques, facilitant ainsi la maintenance, la réutilisation et l'extension de vos pipelines de données dans Dataform.

## Contexte
Nous allons ajouter des scripts JavaScript dans le projet Dataform pour mieux organiser et réutiliser le code. Les fichiers créés incluront des documentations, des constantes, et des fonctions communes.

## Étapes du Lab
1. **Créer un Fichier de Documentation**: Dans le dossier includes, créer un fichier `docs.js` et y mettre la documentation des colonnes et tables déjà définies dans les fichiers `sqlx`.
2. Replacer la documentation définie dans les fichiers `sqlx` par la documentation dans `docs.js`.
3. **Créer un Fichier de Constantes**: Dans le dossier includes, créer un fichier `constants.js` et y mettre les constantes déjà définies dans les fichiers `sqlx`.
4. Replacer les constantes définies dans les fichiers `sqlx` par les constantes dans `constants.js`.
5. **Créer un Fichier de Fonctions Communes**: Dans le dossier includes, créer un fichier `commons.js` et y mettre les fonctions suivantes :
   * Une fonction de déduplication
  * Une fonction de calcul de clé unique
6. Dans les tables `stg`, ajouter une colonne de clé unique en utilisant la fonction créée.
7. Utiliser la fonction de déduplication pour dédupliquer les données des tables `dim`.