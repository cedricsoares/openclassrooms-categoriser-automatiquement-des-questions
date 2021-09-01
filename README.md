# Introduction
Le projet de ce notebook a été réalisé dans le cadre de la formation d'[ingénieur machine learning proposé par Openclassrooms](https://openclassrooms.com/fr/paths/148-ingenieur-machine-learning).

Il portait sur les développement d'une API de suggestion de tags à destination des utilisateur de [Stack Overflow](https://stackoverflow.com/). Il a étét l'occasion de mettre en oeuvre des méthodes de NLP / TAL. 
Ce repository porte sur l'analyse exploratoire et l'entrainement de modèles supervisés et non supervisés afin de répondre au besoin.
Un [second repository](https://github.com/cedricsoares/openclassrooms-api-categoriser-automatiquement-des-questions) contient le code de l'API.

Il était demandé de réaliser:

- Le fitrage des données issue de l'API [stackexchange explorer](https://data.stackexchange.com/stackoverflow/query/new)
- Réaliser le pétraitement des documents 
- Comparer des approches suppervisées (KNN, SVM, Random Forest, Gradient Boosting) et non supervisées (LDA) afin de prédire des tags
- Réaliser les fonctions et classes nécessaire à l'implémentation de l'API. 
- Développer une API et la mettre en production.

# Contenu du repositiry:
- Un notebook d'exploration des données.
- Un notebook de pré-traitement des documents et d'entrainement des modèles supervisés et non supervisés.
- Un rapport de synthèse des travaux réalisés
- Une présentation sous forme de diapositives

# Données:
- [API stackexchange explorer](https://data.stackexchange.com/stackoverflow/query/new)