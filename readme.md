# Traitement Automatique de Langue Naturelle

Ou **Natural Language Processing (NLP)** en anglais. La gestion des données textuelles est complexes. Cette difficulté, combinée au foisonnement des données et des applications (et accessoirement des financements) fait de la communauté NLP, la plus grosse et la plus isolée des communautés du Machine Learning.

* Des conférences à part: ACL, EMNLP, ... [lien vers la biblio](https://aclanthology.org)
* Des pré-requis spécifiques
    * Jouer avec les données textuelles impose la maitrise des expressions régulières: **regex**
    * Maitriser les commandes systèmes de base pour manipuler les fichiers en profondeur, extraire les statistiques de base et vérifier les informations contenues
* Un choix parmi les nombreuses ressources disponibles, celles de l'équipe la plus connue au monde: [Stanford NLP Group](https://nlp.stanford.edu)
    * Ressources pédagogiques: [lien](https://nlp.stanford.edu/teaching/)
    * En particulier, les slides sur les regex à garder sous le coude: [lien](https://web.stanford.edu/class/cs124/lec/124-2021-UnixForPoets.pdf)


## 1. Les sacs de mots

1. Classification de documents

2. Analyse thématique, clustering, approches non-supervisées

## 2. Apprentissage non supervisé

1. Survol de différentes techniques non-supervisées
    * Ressources historiques en TAL
    * Frequent Itemset
    * Construction de ressources
2. De k-mean à LDA
    * utilisation de la librairie `gensim`


## 3. Vers le deep-learning

1. Apprentissage de représentation de mots
    * de Bengio et Collobert à Word2Vec et FastText
    * Analyse quantitative sur la sémantique
2. Fonctions d'agrégation
    * RNN, CNN, Transformers
3. Reflexion sur la gestion des connaissances et les modèles génératifs

## Supports supplémentaires

Le cours d'opinion-mining (ou classification de sentiments) n'est plus vraiment à jour: il est centré sur les sacs de mots alors que la tâche est maintenant quasi-exclusivement abordée en deep-learning. 

Je poste cependant les transparents pour deux raisons:

1. Les représentations avancées en sac de mots conservent un intéret pour certaines tâches
    * les supports peuvent aussi être utiles pour ceux qui veulent approfondir les TP.
2. Cette tâche illustre vraiment très bien la problématique du transfert, qui devient centrale en deep