# TP Javascript DOM - Année au Canada

Ce projet a été réalisé dans le cadre de mes cours durant mon année au Canada. Il contient deux exercices distincts, chacun avec des exigences et technologies spécifiques.

## Exercice 1 : Affichage via le DOM

### Description
Dans ce premier exercice, l'objectif était d'afficher dynamiquement des éléments dans le DOM en utilisant les données provenant d'un fichier JSON. L'exercice incluait également l'utilisation de la bibliothèque **Lodash** pour générer des nombres aléatoires et **StandardJS** pour l'application de bonnes pratiques de codage.

### Fonctionnalités
- **DOM** : Utilisation du DOM pour créer dynamiquement un tableau avec des nombres aléatoires.
- **JSON** : Les paramètres pour la génération des nombres sont extraits d'un fichier JSON, incluant des informations comme le nombre de lignes, de colonnes, et la plage des nombres aléatoires.
- **Lodash** : Utilisation de la fonction `_.random` de Lodash pour générer des nombres aléatoires dans la plage spécifiée.
- **StandardJS** : Le projet respecte les bonnes pratiques de codage, avec l'application de l'outil **StandardJS** pour assurer un code propre et lisible.

### Fonctionnalité principale
- Génération d'un tableau dynamique dans le DOM avec des données provenant d'un fichier JSON externe.
- Calcul du nombre de cellules dont la valeur dépasse un seuil donné et affichage de ce résultat à la fin du tableau.

### Technologies utilisées
- **HTML** (Structure de la page)
- **CSS** (Styles de base)
- **JavaScript** (Manipulation du DOM)
- **Lodash** (Librairie pour la génération de nombres aléatoires)
- **StandardJS** (Linter et formateur de code)

## Exercice 2 : Calculateur de coefficient de traînée

### Description
Le deuxième exercice consistait à développer un calculateur de coefficient de traînée (Cd), utilisé dans des simulations physiques, en respectant un wireframe précis. Cet exercice a été réalisé en utilisant **Bootstrap** pour la mise en page et le respect du wireframe.

### Fonctionnalités
- **Calcul du coefficient de traînée (Cd)** : Le calculateur prend en entrée des valeurs comme la force de traînée, la densité de l'air, et la vitesse, et renvoie le coefficient de traînée en utilisant la formule appropriée.
- **Bootstrap** : Utilisation de **Bootstrap** pour rendre l'interface utilisateur responsive et conforme au wireframe fourni.
- **Validation des entrées** : Validation des entrées de l'utilisateur pour s'assurer que les données sont valides avant d'effectuer le calcul.

### Technologies utilisées
- **HTML** (Structure de la page)
- **CSS** (Mise en page avec Bootstrap)
- **JavaScript** (Logique du calcul et validation des entrées)
- **Bootstrap** (Framework CSS pour le wireframe)

## Installation

### Prérequis
- **Node.js** et **npm** pour la gestion des dépendances.
- **Lodash** et **StandardJS** doivent être installés.