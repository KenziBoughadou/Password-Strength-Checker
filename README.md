# Projet : Vérificateur de Force de Mot de Passe

## Description
Ce projet est un vérificateur de force de mot de passe en ligne de commande. Il analyse les caractéristiques d'un mot de passe (majuscules, minuscules, chiffres, caractères spéciaux, espaces) et attribue un score de robustesse. En fonction du score, le programme fournit une évaluation de la qualité du mot de passe, allant de "Très faible" à "Très fort".

## Objectifs et Fonctionnalités

- **Analyse des Caractères** : Compte les types de caractères dans le mot de passe (lettres minuscules, majuscules, chiffres, espaces, caractères spéciaux).
- **Calcul de la Force** : Attribue un score de force basé sur les types de caractères présents.
- **Feedback Utilisateur** : Fournit des remarques sur la qualité du mot de passe en fonction du score, avec des conseils d'amélioration.

## Technologies Utilisées

- **Python** : Langage de programmation principal.
- **getpass** : Module pour saisir le mot de passe sans l'afficher à l'écran.
- **string** : Utilisé pour vérifier les types de caractères.

## Exemple d’Utilisation
L’utilisateur exécute le programme, saisit un mot de passe, et reçoit un retour sur sa force, avec une évaluation et des conseils si le mot de passe est faible.
