# K-Means-Clustering
# Le k-means :
est l'algorithme le plus populaire dans l'apprentissage non supervisé, il consiste à regrouper les données selon leur structure commune  et leur ressemblance. Cette constitution s’appelle faire du Clustering. Son fonctionnement principale vise à minimiser la fonction coût appeler inertia et qui représente la distance entre les points d'un cluster et le centroid.

L’algorithme k-means est un algorithme itératif qui fonctionne en deux étape essentiels :

La première étape consiste à placer des points au hasard parmis nos données appelées “centroid”, puis on affecte chaque point du dataset au centroid le plus proche. On répète cette étape plusieurs fois  pour obtenir des differentes positions initiales quand on aura besoin d’eux dans la deuxième étape. 



la deuxième étape est basé sur le déplacement de chaque centroid au centre du cluster on va répéter cette étape jusqu'à ce que les centroid  convergent vers des positions d'équilibre pour assurer que ces dernier converge vers des bonne position on calcule la moyenne entre les différentes points initiale obtenue dans la première étape et le centre du cluster,  par la suite on retient la solution pour la quelle la somme de ses distances est la plus
petit.


# Remarque :
Dans le cas ou on se retrouve avec un dataset avec des centaines de dimensions 
On peut déterminer le bon nombre de clusters on utilise 'ELBOW MÉTHODE'. Cette dernière consiste à tracer l'évolution de notre 
modèle en fonction du nombre de clusters et de détecter dans ce graphe une zone de 'COUDE', cette zone nous indique le nombre de cluster optimale
C-a-d: le nombre  qui nous permet de réduire au maximum le coût de notre modèle tout en conservant un nombre raisonnable de clusters.

||--> Le but de cette méthode consiste a minimiser la fonction coût pour ce faire il suffit de créer autant de clusters 



