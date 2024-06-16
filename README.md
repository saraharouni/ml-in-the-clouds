# ML IN THE CLOUD

## Sujet

Le thème principal de ce sujet est la comparaison de différents outils de machine learning dans le cloud.  

Pour cette comparaison, nous allons traiter des données textuelles qui serviront pour faire de la prédiction d'émotions.  

Le fichier d'entrainement contient 6 émotions qui seront testées sur pycaret mais aussi from scratch. L'idée est de comparer également ces outlils en terme de temps et de ressources utilisées.  

Par la suite, nous devons aussi prétraiter le fichier de test qui contient des colonnes supplémentaires ainsi que 14 émotions.  
Avec cet enrichissement de données, il a fallu recréer de nouveaux modèles entrainés non plus sur 6 émotions mais sur 14.  

En parrallèle, nous avons aussi tester nos données sur DataRobot. 

## Veille informatique

### Les avantages principaux de l’AutoML

1. **Une bonne base pour la préparation des données**

    La préparation des données doit reposer sur des opérations de nettoyage (filtrage du bruit dans les données) et de formatage (recodage en données catégorielles par exemple) fiables. L’AutoML permet d’accélérer cette phase grâce à un processus formatant et détectant le bruit dans les données de manière différente.

2. **Éviter l’utilisation des paramètres par défaut dans les modèles**

    La recherche des meilleurs paramètres passe par une maîtrise des méthodes de recherche par quadrillage et aléatoires (des techniques d’optimisation qui permettent de calculer les valeurs optimales des hyperparamètres) afin d’obtenir une liste de paramètres parmi lesquels choisir les plus appropriés. Ce processus est parfois chronophage, d’où l’intérêt de l’AutoML qui permet de résoudre ce problème.

3. **Simplification des processus de création et de gestion des modèles**

    En général, les Data Scientists établissent une liste de modèles intéressants en fonction du contexte et du problème. Ce qui requiert une connaissance approfondie et de l’expertise métier dans le domaine de la donnée. L’AutoML simplifie cette étape car il met à disposition un véritable réservoir proposant davantage de modèles, adaptés à une majorité de problèmes.

4. **Optimisation du Deep Learning**

    Le Deep Learning s’inspire du fonctionnement du cerveau humain pour traiter les données et créer les modèles à utiliser dans les processus de prise de décisions. Son objectif est de trouver l’architecture de réseau neuronal la plus appropriée pour aborder une question donnée. Avec, par exemple, Keras, une bibliothèque open source dédiée au Deep Learning, de nombreuses lignes de code sont nécessaires pour créer cette meilleure architecture. Toutefois, grâce à la méthode Auto-Keras (bibliothèque d’apprentissage en profondeur) d’apprentissage automatique, il est désormais possible d’obtenir de meilleurs résultats avec beaucoup moins de lignes.

[source](https://fr.blog.businessdecision.com/machine-learning-automatise/)


## Machine Learning as a Service (MAAS) : définition

Le Machine Learning as a Service regroupe différents outils de Machine Learning distribués sous forme de services Cloud. Il permet aux utilisateurs de profiter du Machine Learning à moindre coût, tout en leur permettant de gagner du temps et d'éviter de prendre le risque de former une équipe interne dédiée au Machine Learning.

Le traitement préalable des données, l'entraînement et l'évaluation de modèle, ainsi que les prédictions peuvent être effectuées via le MLaaS. Les fournisseurs de services proposent des outils d'analyses prédictives, de Deep Learning, de Dataviz, de traitement naturel du langage et bien plus encore. La puissance de calcul nécessaire est fournie par les Data Centers des fournisseurs de services.

## Machine Learning as a Service (MAAS) : quels sont les avantages ?

Pour les entreprises, le principal avantage du MLaaS est d'éviter d'avoir à développer une infrastructure sur site en partant de zéro. Il s'agit d'un point particulièrement avantageux pour les PME qui n'ont pas les ressources nécessaires pour stocker et gérer des volumes massifs de données.

En l'occurrence, ce sont les fournisseurs de services qui se chargent du stockage et de la gestion de données sur leurs propres serveurs. Ainsi, les PME peuvent accéder aux mêmes technologies de Machine Learning que les grandes entreprises afin de pouvoir rester compétitives.

[source](https://www.lebigdata.fr/mlaas-definition/)


## Google Cloud Platform (GCP)

C'est une suite de services de cloud computing offerts par Google. Pour les data scientists, GCP fournit des outils puissants pour l'analyse de données, l'apprentissage automatique (via AI Platform), le traitement de données massives (avec BigQuery), ainsi que des infrastructures évolutives pour le stockage et le calcul, facilitant ainsi la gestion et l'exploitation des données à grande échelle.

[Google Cloud Platform (GCP)](https://cloud.google.com)

## Vertex AI  

Vertex AI est une plate-forme de machine learning (ML) qui vous permet d'entraîner et de déployer des modèles de ML et des applications d'IA, et de personnaliser les modèles de langage volumineux (LLM) à utiliser dans vos applications basées sur l'IA. Vertex AI combine les workflows d'ingénierie des données, de science des données et d'ingénierie de ML, ce qui permet à vos équipes de collaborer à l'aide d'un ensemble d'outils commun et de faire évoluer vos applications en tirant parti des avantages de Google Cloud.  

[Vertex AI](https://cloud.google.com/vertex-ai/docs/start/introduction-unified-platform?hl=fr)


## AWS  

Amazon Web Services (AWS) est la plateforme cloud la plus complète et la plus largement adoptée au monde. Elle propose plus de 200 services complets issus de centres de données du monde entier. Des millions de clients (dont certaines des startups les plus dynamiques au monde, de très grandes entreprises et des agences fédérales de premier plan) utilisent AWS pour réduire leurs coûts, gagner en agilité et innover plus rapidement.

[AWS](https://aws.amazon.com/fr/what-is-aws/)

## Sagemaker  

Amazon SageMaker est un service d'apprentissage automatique (ML) entièrement géré. Les data scientists et les développeurs peuvent ainsi créer, former et déployer rapidement et en toute confiance des modèles de machine learning dans un environnement hébergé prêt pour la production. SageMaker Il fournit une interface utilisateur pour exécuter des flux de travail ML qui rend les outils de SageMaker ML disponibles dans plusieurs environnements de développement intégrés (IDE).

[Sagemaker](https://docs.aws.amazon.com/fr_fr/sagemaker/latest/dg/whatis.html)  

## Microsoft Azure

C'est une plateforme de cloud computing de Microsoft offrant une large gamme de services pour le stockage, le calcul, et l'analyse des données. Pour les data scientists, Azure fournit des outils tels que Azure Synapse Analytics pour le traitement des données massives, ainsi que des services de machine learning et d'intelligence artificielle pour développer, entraîner et déployer des modèles de machine learning à grande échelle.

[Microsoft Azure](https://azure.microsoft.com)

## Azure Machine Learning

C'est un service cloud de Microsoft Azure conçu pour les data scientists et les ingénieurs en machine learning. Il permet de construire, entraîner et déployer des modèles de machine learning de manière simple et efficace, en offrant des outils pour l'automatisation du machine learning, la gestion des pipelines, et l'intégration continue pour le développement de modèles à grande échelle.

[Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)


## DataRobot

C'est une plateforme de machine learning automatisée qui aide les data scientists à construire, déployer et gérer des modèles de machine learning rapidement et efficacement. DataRobot propose des outils avancés pour l'automatisation de l'ingénierie des caractéristiques, la sélection des algorithmes, l'optimisation des hyperparamètres et la gestion des modèles, facilitant ainsi l'ensemble du cycle de vie des projets de data science.

[DataRobot](https://www.datarobot.com)

# Analyse et évaluation des modèles  

## Data Robot

## From Scratch

## Pycaret

# Conclusion

