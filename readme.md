Exercice 2 :

1. La structure WeightedGraph représente le graphe pondéré. Elle stocke les noeuds, les arrêtes, leurs poids, les relations de voisinage entre les nœuds, ainsi que des fonctions pour ajouter ou supprimer des nœuds et des arêtes.

La structure PositionedGraph complète WeightedGraph en associant en plus la position de chaque noeud.

2. - extraction OSM : lis le fichier OSM et extrait la représentation sous forme de graphe.
   - simplification : simplifie le graphe en supprimant les noeuds et arrêtes inutiles.
   - visualize : visualiser le graphe.

3. La simplification identifie les nœuds voisins dans une profondeur donnée du graphe, puis vérifie leur distance. Si plusieurs nœuds sont suffisamment proches, ils sont regroupés dans un même cluster ou associés au cluster le plus proche avant d’être fusionnés.
Cela sert à rendre le graphe plus lisible, moins complexe à lire et aussi plus facile à traiter pour l'algo. En revanche, on perd de la précision.