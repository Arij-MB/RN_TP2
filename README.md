# RN_TP2
Data Set : Nous allons utiliser le dataset “Iris Species” du Fisher's classic 1936 paper. Ce jeu de données inclut 3 espèces Iris (Iris_Setosa, Iris_Versicolor et Iris_Virginica) avec 50 échantillons pour chaque type. Dans le fichier drive: “https://drive.google.com/file/d/1lCrldn-uT1K6ctUC2xt7-hMjbMZ9Ft9r/view?us p=sharing”. Nous avons un fichier excel des jeux de données et qui contient six colonnes : la première correspond aux identifiants de chaque fleur, la seconde pour la longueur des pétales en cm., la troisième pour la largeur des pétales et les autres pour les sébales ainsi qu’une dernière colonne qui contient l’espèce de la fleur.

Travail demandé: 

1- Créer Un DataFrame en utilisant les données de fichier ‘’Iris.csv” qui contient notre dataSet. 

2-Afficher les 10 premières lignes du DataFrame. 

3-Afficher les dimensions du dataframe. 

4-Utiliser la bibliothèque python Seaborn pour visualiser les données en fonction de la longueur des pétales et de largeur des sépales. 

5-Ecrire un script python permettant de labelliser les différentes espèces d’iris.( Iris_Setosa → 0 , Iris_Versicolor→ 1 et Iris_Virginica → 2 ) 

6-Afficher du nouveau les 10 premières lignes du nouveau DataFrame contenant les labels. 

7-Écrire un script python permettant la division de dataset en des données d’apprentissage (70%) et des données de test (30%). 

8-Afficher les 10 premières données d’apprentissage et celles de test. 

9-Ecrire un script python qui utilise un perceptron multicouche pour l’apprentissage des données avec un optimisateur (‘lbfgs’, epsilon=0.07 et nombre maximum d’itération=150) . 

10-Evaluer ce perceptron en affichant son “accuracy” et le temps de réponse. 

11-Afficher la matrice de confusion associée à notre cas. 

12-Selon les résultats affichés commenter le perceptron que vous avez utilisé. 

13-On va ajouter le paramètre de taux d’apprentissage au niveau de classifieur utilisé pour une valeur égale 0.7 

14-Nous allons étudier la variation du paramètre de taux d’apprentissage, donc nous allons afficher la courbe d'évolution d’apprentissage et celle de test en fonction de variation du taux d’apprentissage. 

15-Nous allons fixer un nombre d’itération égale à 10 fois le nombre fixé au début. Quel est le phénomène constaté ? et comment pouvons- nous surmonter celui-ci ? 

16-Tester d’autres classifieurs de type réseau de neurones (Dynamique/Récurrent et Non récurrent) . 

17-Dans notre cas de base de donnée Iris, est ce qu’il est intéressant d’avoir un réseau de neurones récurrent ou non ? justifier vos réponses.
