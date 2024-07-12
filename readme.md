# Lab: Amélioration du Projet Dataform avec JavaScript
## Objectif du Lab
Ce lab a pour objectif d'améliorer notre projet existant en introduisant les notions de JavaScript présentées précédemment. Vous allez créer plusieurs fichiers JavaScript pour documenter, définir des constantes, et inclure des fonctions communes utiles pour vos transformations de données.

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
6. Dans les tables `dim` et `fct`, ajouter une colonne de clé unique en utilisant la fonction créée.
7. Utiliser la fonction de déduplication pour dédupliquer les données des tables `dim`.