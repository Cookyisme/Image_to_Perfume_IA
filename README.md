# Image_to_Perfume_IA

Cette archive contient deux scripts Python permettant d'associer une image à un parfum en utilisant un modèle d'intelligence artificielle pré-entrainé : ResNet50. Ce modèle effectue une analyse avancée des caractéristiques visuelles de l'image, qui seront ensuite vectorisées et comparées à une base de données de parfums.

Le premier script, Prédiction_réduite.py, réalise une association rapide en comparant l'image à la base "final_perfume_data.csv". Cette approche est efficace et permet un temps d'exécution réduit tout en fournissant des résultats pertinents basés sur une sélection de parfums prédéfinis.

Le second script, Prédiction_longue.py, suit un processus similaire mais adopte une méthodologie plus approfondie. Il compare les vecteurs de l'image non seulement aux parfums répertoriés, mais également aux notes de parfum vectorisées issues de la base "perfume_table". Cette approche affine considérablement l'interprétation des préférences de l'utilisateur, bien que cela entraîne un temps d'exécution plus conséquent.

Des améliorations futures sont envisagées, notamment une optimisation des performances pour accélérer les calculs, l'intégration de nouvelles données pour enrichir la précision des recommandations, ainsi que le développement d'une interface utilisateur intuitive. De plus, l'utilisation de modèles d'intelligence artificielle plus performants que ResNet50 pourrait être explorée.
