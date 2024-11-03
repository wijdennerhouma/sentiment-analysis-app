# sentiment-analysis-app
Application d'analyse de sentiments pour les avis clients
# Analyse des Sentiments des Avis Clients

## Description
Ce projet consiste en une application d'analyse de sentiments dédiée à l'extraction d'informations significatives sur les opinions et émotions des utilisateurs à partir de leurs commentaires. En utilisant des techniques de traitement du langage naturel (NLP), ce modèle est capable de classer les sentiments exprimés dans des textes, tels que des avis clients ou des publications sur les réseaux sociaux. L'objectif principal est d'aider les entreprises à comprendre les réactions de leurs clients vis-à-vis de leurs produits ou services, afin d'améliorer leurs stratégies marketing et de développement de produits en fonction des retours des consommateurs.

## Fonctionnalités
- **Analyse des sentiments** : Classifie les commentaires en trois catégories de sentiments : positif, négatif et neutre.
- **Visualisation des résultats** : Fournit des graphiques et des statistiques pour illustrer la répartition des sentiments dans les données analysées.
- **Prédiction des sentiments** : Permet d'entrer de nouveaux commentaires pour prédire le sentiment associé, facilitant ainsi une évaluation rapide de la satisfaction client.

## Installation
Pour installer les dépendances nécessaires au bon fonctionnement de l'application, assurez-vous d'avoir Python installé sur votre machine. Ensuite, exécutez la commande suivante dans votre terminal :
```bash
pip install -r requirements.txt

Cette commande installera toutes les bibliothèques nécessaires, notamment pandas, numpy, scikit-learn, nltk, matplotlib, et seaborn.

Utilisation
Pour exécuter le modèle d'analyse des sentiments, ouvrez le notebook Jupyter notebooks/sentiment_analysis.ipynb. Suivez les instructions fournies à l'intérieur du notebook pour charger les données, entraîner le modèle, et effectuer des prédictions sur de nouveaux textes. Assurez-vous que le dataset est accessible dans le dossier data/ pour un bon fonctionnement.

Exemples de Données
Le jeu de données utilisé pour entraîner le modèle est disponible dans le dossier data/. Il contient des colonnes telles que :

textID : Un identifiant unique pour chaque commentaire.
text : Le texte du commentaire à analyser.
selected_text : Le texte sélectionné pour l'analyse des sentiments.
sentiment : L'étiquette de sentiment associée (positif, négatif, neutre).
Time of Tweet, Age of User, Country, Population -2020, Land Area (Km²), Density (P/Km²) : Données contextuelles qui peuvent être utilisées pour des analyses supplémentaires.
Références
Documentation scikit-learn : Une ressource précieuse pour comprendre les algorithmes de machine learning utilisés dans ce projet.
Documentation NLTK : Guide complet sur le Natural Language Toolkit, utilisé pour le prétraitement et l'analyse des données textuelles.
Kaggle Dataset : Lien vers le site où vous avez obtenu le dataset utilisé pour l'analyse.
Contribuer
