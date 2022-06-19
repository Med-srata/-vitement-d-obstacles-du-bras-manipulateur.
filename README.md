# Evitement d'obstacles du bras manipulateur.
L'objectif de ce projet est de proposer une méthode de commande d'un bras de robot à deux degrés de liberté pour l'évitement d'obstacles en utilisant des réseaux de neurones. Ce bras se déplace d'une position initiale donnée à une position d'arrivée bien définie dans un environnement bien défini.
Cette méthode permet au robot d'atteindre un but avec une capacité d'évitement d'obstacles. 

Nous proposons également une base de données extraite du modèle géométrique qui facilitera l'apprentissage et le suivi de la trajectoire du robot, afin de surmonter l'efficacité de l'approche proposée.

l'extraction de la base de données est faite par le code python que vous trouverez dans la section code 

Pour déduire le comportement de notre modèle de réseau de neurones et de notre modèle dynamique exécuté dans notre bras robotique, nous aurons besoin d'un moyen efficace et très puissant, étant donné les énormes données que notre modèle recevra, qui seront utilisées pour faire des études préliminaires et comparatives, tant dans la phase de développement (conception) que pendant le fonctionnement normal du système.

Par conséquent, ce projet consistera à simuler les deux modèles : le modèle de réseau neuronal et le modèle dynamique. Pour réaliser cette simulation, nous utiliserons l'environnement SIMULINK-Matlab.
