# Qu'est-ce que l'Apprentissage Automatique (Machine Learning) ?

## Introduction

L'**apprentissage automatique** (ou Machine Learning, ML) est une branche de l'intelligence artificielle (IA) qui permet aux machines d'apprendre à partir de données sans être explicitement programmées. Grâce à des algorithmes et des modèles statistiques, l'IA identifie des motifs dans les données et fait des prédictions, que ce soit dans des domaines comme la santé, la finance, etc. L'apprentissage automatique révolutionne le monde en automatisant des tâches complexes et en améliorant la prise de décisions.

---

## A. L’apprentissage automatique et l’apprentissage profond

Apprentissage automatique : Développement d'algorithmes permettant aux ordinateurs d'apprendre et de s'améliorer à partir de données.

Apprentissage profond : Sous-domaine utilisant des réseaux de neurones profonds pour traiter des informations complexes.

## B. L’apprentissage supervisé

Méthode d'entraînement utilisant des données labellisées, où le modèle apprend à associer des entrées à des sorties connues.

## C. L’apprentissage non supervisé

Le modèle identifie des structures cachées dans des données non étiquetées sans intervention humaine.

## D. La classification supervisée

Technique d’apprentissage supervisé où le modèle assigne une catégorie à une nouvelle donnée en se basant sur ses apprentissages passés.

## E. La classification non supervisée

Identification automatique de groupes ou de clusters dans des données non étiquetées.

## F. La validation croisée

Technique utilisée pour évaluer la performance d’un modèle en répartissant les données en plusieurs sous-ensembles d’entraînement et de test.

## G. Données d’entraînement, de test et de validation

Données d'entraînement : Servent à apprendre les paramètres du modèle.

Données de test : Évaluent la performance finale.

Données de validation : Aident à ajuster les hyperparamètres et à éviter le surajustement.

## H. Corrélation linéaire (de Pearson) entre deux variables

Mesure statistique indiquant le degré d’association linéaire entre deux variables quantitatives.

## I. Une fonction de coût

Outil permettant d’évaluer l’erreur d’un modèle en comparant ses prédictions aux valeurs réelles.

## J. La descente de gradient

Algorithme d'optimisation ajustant progressivement les paramètres d’un modèle en minimisant la fonction de coût.

---

Ce document se concentre sur deux concepts importants en apprentissage automatique : **La Science des Données** et **La Régression**.

---

## Sommaire

1. [La Science des Données](#la-science-des-données)
2. [La Régression](#la-régression)
   - [Types de Régression](#types-de-régression)
   - [Régression à Descente de Gradient](#régression-à-descente-de-gradient)

---

## La Science des Données

La **science des données** consiste à utiliser des statistiques, de la programmation et de l'analyse pour extraire des informations utiles à partir de grandes quantités de données. Cela inclut plusieurs étapes comme la collecte, le nettoyage, l'analyse et la visualisation des données.

### Objectifs de la Science des Données

Les objectifs principaux sont de :

1. **Explorer les données** : Trouver des liens cachés entre différentes variables.
2. **Analyser les données** : Utiliser des méthodes statistiques pour tirer des conclusions.
3. **Créer des modèles** : Utiliser l'apprentissage automatique pour faire des prédictions.
4. **Communiquer les résultats** : Présenter les découvertes de manière claire, souvent avec des graphiques.

### Outils et Technologies

Les outils courants incluent des langages comme **Python** et **R**, des bibliothèques comme **pandas**, **NumPy**, et des plateformes de Machine Learning comme **TensorFlow** et **scikit-learn**.

---

## La Régression

La **régression** est une technique qui permet de prédire une valeur continue (comme le prix d'une maison) en fonction de certaines caractéristiques (comme la taille de la maison). Elle sert à comprendre la relation entre plusieurs variables.

### Types de Régression

1. **Régression Linéaire Simple** : C'est le cas de régression le plus simple où l'on relie une variable à une autre de manière linéaire.
2. **Régression Linéaire Multiple** : Quand on utilise plusieurs variables pour faire des prédictions.
3. **Régression Polynomiale** : Utilisée quand la relation entre les variables n'est pas linéaire.

### Exemple de Régression Linéaire Simple

La régression linéaire modélise la relation entre deux variables avec une droite. Cela peut être décrit par :

- y : la valeur à prédire (la cible).
- x : les caractéristiques qui aident à prédire y.
- β₀ : l'ordonnée à l'origine (le point où la droite coupe l'axe des y).
- β₁ : le coefficient de régression (la pente de la droite).
- ϵ : l'erreur du modèle.

---

## Régression à Descente de Gradient

La **descente de gradient** est une méthode utilisée pour ajuster les paramètres d'un modèle afin de minimiser l'erreur entre les prédictions et les vraies valeurs. Cela consiste à mettre à jour les paramètres en fonction de l'erreur.

### Comment fonctionne la Descente de Gradient ?

1. **Initialisation** : On commence avec des valeurs pour les paramètres β₀ et β₁.
2. **Calcul du Gradient** : On détermine dans quelle direction ajuster les paramètres pour réduire l'erreur.
3. **Mise à Jour** : On met à jour les paramètres selon une formule.
4. **Répétition** : On répète l'étape 3 jusqu'à ce que l'erreur soit minimale.

La descente de gradient est très utilisée pour optimiser différents modèles, y compris la régression linéaire et logistique.
