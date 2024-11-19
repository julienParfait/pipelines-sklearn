# Création d'un pipeline avec scikit-learn et data vizualisation avec plotly

Dans ce notebook je partage comment réaliser un pipeline simple de traitement de données pour la modalisation, le machine learning. 

Un pipeline en machine learning est un outil structurant permettant d’automatiser et de simplifier le flux de traitement des données et de modélisation. Il consiste en une séquence ordonnée d’étapes, où chaque étape correspond à une transformation spécifique (prétraitement, sélection de caractéristiques, etc.) ou à un modèle d’apprentissage. Il permet de gagner en temps, productivité et éviter les fuites de données. 

La visualisation de données avec Plotly permet de transformer des données complexes en graphiques interactifs et intuitifs, facilitant l'exploration et la communication d'informations clés. Grâce à ses fonctionnalités puissantes et polyvalentes, Plotly offre un large éventail de visualisations adaptées à une variété de domaines, de la science à l'entreprise, tout en assurant une meilleure compréhension des données pour une prise de décision éclairée.

Simple et facile d'utilisation, plotly est très simple d'utilisation comme je le montre dans la seconde partie avec des bouts de codes bien structurés. Il suffit de connaitre le nom de l'appel d'un type de graphe tel que px.histogram(), px.bar() et ensuite de lui passer un dataFrame, d'affecter chaque variable à un axe et vous obtenez votre premier graphe comme le montre les codes ci-dessous. Le reste des lignes de code n'est qu'une adaptation, formatage (titre du graphe, nom des axes, etc.).

```{tableofcontents}
```
