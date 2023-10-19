# food_nb

L'agence Santé Publique France souhaite améliorer sa base de données Open Food Facts.

Cette base de données open source est mise à la disposition de particuliers et d’organisations afin de leur permettre de connaître la qualité nutritionnelle de produits. 

Aujourd’hui, pour ajouter un produit à la base de données d'Open Food Facts, il est nécessaire de remplir de nombreux champs textuels et numériques, ce qui peut conduire à des erreurs de saisie et à des valeurs manquantes dans la base. 

L’agence Santé Publique France souhaite un système de suggestion ou d’auto-complétion pour aider les usagers à remplir plus efficacement la base de données.

L’objectif de ce projet est de faire un focus sur la prise en main des données, leur nettoyage et leur exploration, afin de déterminer la faisabilité de cette idée d’application de Santé Publique France.

Le notebook se compose en deux parties :
- nettoyage des données avec sélection des variables intéressantes, suppression des outliers, vérification des doublons et remplacement des valeurs nulles (médiane, formules de calcul, algorithme k-NN)
- analyse exploratoire univariée et multivariée (ANOVA, ACP)
