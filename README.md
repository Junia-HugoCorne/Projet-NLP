# Projet-NLP

# Inspiration et Évolution du Projet

## Contexte et Inspiration
Le projet s'inspire de la compétition [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/search?q=jigsaw+toxic+comment+classification+challenge) sur Kaggle, qui propose un cadre riche pour explorer la classification des commentaires toxiques.

## Évolution du Modèle

### 1. Phase Baseline
Dans un premier temps, une phase baseline a été mise en place afin d'établir une référence rapide. Cette étape repose sur l'utilisation de techniques classiques de machine learning, telles que la régression logistique et les SVM, pour effectuer une première analyse des données. L'objectif est d'obtenir un modèle initial servant de point de comparaison pour les améliorations futures.

### 2. Passage au Deep Learning
Par la suite, le projet est passé au deep learning afin de mieux capturer les nuances et le contexte des textes. Des architectures comme les RNN et les LSTM ont été implémentées pour une modélisation plus efficace des séquences textuelles. Cette approche a permis une nette progression des performances par rapport à la baseline grâce à une meilleure compréhension contextuelle.

### 3. Modèle Final Performant
Enfin, un modèle final a été développé avec pour objectif d’optimiser la précision et la robustesse. Pour cela, des architectures comme les Transformers, notamment BERT, ont été adoptées avec un fine-tuning sur des jeux de données spécifiques. L’optimisation est passée par un ajustement des hyperparamètres et une validation croisée pour maximiser la performance. Le modèle obtenu est capable de classifier efficacement les commentaires toxiques.

## Conclusion
L'évolution de notre approche, de la mise en place d'une baseline simple à l'intégration de techniques avancées de deep learning, illustre notre capacité à itérer et améliorer continuellement notre modèle. Chaque étape, en commençant par le notebook initial, a permis d'apporter des améliorations significatives pour aboutir à un modèle final optimal.
