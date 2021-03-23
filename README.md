# Classification des genres  de films à partir des affiches/images utilisant CNNs
## Introduction
### Description du problème 

Ce projet a pour objectif de parvenir à une classification des genres de films basée uniquement sur des des affiches de films.
Pour les spectateurs, les affiches de films sont très significatifs  pour avoir une idée du contenu du film et de son genre. Les humains peuvent avoir une idée en se basant sur les couleurs, les objets, les expressions du  visages des acteurs, etc.. pour déterminer rapidement le genre (horreur, comédie, animation, etc.).
Si les humains sont plus ou moins capables de prédire le genre d'un film en ne regardant que son affiche, alors nous pouvons supposer que l'affiche possède certaines caractéristiques qui pourraient être utilisées dans les algorithmes d'apprentissage machines pour prédire son genre.

### Proposed Approach

Pour ce faire, un Deep Neural Network (Convolutional Neural Network) est construit pour attribuer un genre à une affiche de film donnée. Puisqu'un film peut appartenir à plusieurs genres, il s'agit d'un problème de classification d'images multi-étiquettes mais dans notre projet on se contntera de déterminer le genre dominant.

### Pronostic
Puisque même un humain peut facilement faire des erreurs dans cette tâche, notre objectif initial est de reconnaître correctement au moins la moitié des films.
Notre data Set (images, voire labels) peut etre sujet de modification ou ajustement au cours de notre projet au cas ou on  rencontrera des difficultés.   
(sources and related links: 

