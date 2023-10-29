# Prédiction des Prix Immobiliers à Rouen
Ce projet vise à développer un modèle de prédiction des prix des appartements et des maisons dans la ville de Rouen sur une première phase. La deuxième phase sera dédiée au développement d'une application mobile pour déployer le modèle sélectionné lors de la partie prédiction et Machine Learning

Sur le notebook "DARI.ipynb" nous allons nous concentrer sur la première phase (utilisation de modèle de machine learning pour prédire les prix immobiliers) où nous allons utiliser les données historique des transactions immobilières de la ville de Rouen disponibles sur ce [lien](https://app.dvf.etalab.gouv.fr/).

L'analyse du projet est divisée en deux principales parties :

### Partie 1 : Exploration, Nettoyage et Structuration des Données

<b>Exploration des données :</b> Cette phase initiale nous permettra de prendre connaissance de la structure des données, d'identifier des tendances et des corrélations potentielles, ainsi que de comprendre la nature des variables que nous allons utiliser.

<b>Nettoyage des données :</b> Nous éliminerons les valeurs manquantes, gérerons les valeurs aberrantes et corrigerons toute incohérence dans les données. Un ensemble de données propre est essentiel pour des prédictions précises.

### Partie 2 : Évaluation des Méthodes de Régression

La seconde partie de notre analyse est dédiée à l'évaluation de diverses méthodes de régression pour prédire les prix immobiliers. Nous nous pencherons sur les approches suivantes :

<b>Régression Linéaire :</b> Nous utiliserons un modèle de régression linéaire pour établir une relation linéaire entre les caractéristiques des biens immobiliers et leurs prix.

<b>Régression Ridge :</b> La régression Ridge, une variante de la régression linéaire, utilise une régularisation L2 pour prévenir le surajustement.

<b>Régression Lasso :</b> La régression Lasso est une autre méthode de régression linéaire, mais elle utilise une régularisation L1 pour sélectionner un sous-ensemble de caractéristiques importantes.

<b>Régression Polynomiale :</b> Cette méthode consiste à ajuster des polynômes aux données pour capturer des relations non linéaires entre les caractéristiques et les prix immobiliers.

Nous évaluerons la performance de ces méthodes en utilisant des métriques telles que l'erreur quadratique moyenne (RMSE) et le coefficient de détermination (R²) pour déterminer celle qui offre les meilleures prédictions de prix immobiliers à Rouen.
