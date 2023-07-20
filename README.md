# Modèle de Recommandation Personnalisé pour une Plateforme de Commerce Électronique

Ce script Python implémente un modèle de recommandation personnalisé basé sur la méthode de filtrage collaboratif avec les voisins les plus proches (KNN) pour une plateforme de commerce électronique.

## Auteur

Mr. R

## Fonctionnement du Script

1. Le script charge les données de recommandations à partir d'un fichier CSV contenant les caractéristiques des produits et les identifiants des clients.
2. Il divise ensuite les données en ensembles d'entraînement et de test pour évaluer les performances du modèle.
3. Le modèle KNN est créé en utilisant la classe `NearestNeighbors` de la bibliothèque scikit-learn.
4. Les prédictions sont effectuées sur l'ensemble de test en utilisant la méthode `kneighbors` du modèle, qui identifie les voisins les plus proches pour chaque client.
5. Pour chaque client de l'ensemble de test, le script affiche les recommandations personnalisées, en excluant le client lui-même (le plus proche voisin).

## Utilisation du Script

1. Assurez-vous d'avoir installé les bibliothèques requises en exécutant `pip install pandas scikit-learn`.
2. Placez le fichier CSV contenant les données de recommandation dans le même répertoire que le script, ou spécifiez le chemin d'accès correct dans le script.
3. Exécutez le script Python à l'aide de la commande `python ModelDeRec.py`.

## Remarque

Assurez-vous d'adapter le fichier CSV contenant les données de recommandation en fonction de votre propre jeu de données et des caractéristiques spécifiques de votre plateforme de commerce électronique.

Bonnes expérimentations avec notre modèle de recommandation !
