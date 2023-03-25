# MovieLens-park

## Chargement											
Tout d'abord, nous devons importer les bibliothèques et initialiser Spark

## 1.	Analyse du jeu de données	
Ensuite, il est important de s'approprier le jeu de données, notamment en vérifiant les valeurs nulles, en changeant les types de données des colonnes et en identifiant les doublons.
 
Ensuite, nous générons quelques indicateurs sur le jeu de données, à savoir le nombre de films par collection et la liste des genres de films.
						
## 2.	Modèle de prédiction des recettes et de la moyenne des votes
Nous mettons en œuvre trois modèles pour effectuer la prédiction des recettes et de la moyenne des votes.
### 2.1. Prétraitement
Pour commencer, une étape obligatoire, le prétraitement.
								
### 2.2. Premier modèle : régression linéaire	
						
### 2.3. Deuxième modèle : Régression par arbre de décision	
				
### 2.4. Troisième modèle : régression par boosting de gradient	
				
### 2.5. Modèle de prédiction de la moyenne des votes						
Une fois les trois modèles mis en œuvre, passons à la prédiction de la moyenne des votes.


## 3.	Recommandation du modèle									
Il est maintenant temps de mettre en place l'objectif final du projet : le modèle de recommandation. Nous avons choisi deux algorithmes pour ce faire : Top N movies closer with a movie title et Predict user rating.

### 3.1.	Les N films les plus proches d'un titre de film	
Comme d'habitude, nous commençons par le prétraitement. Ensuite, nous avons choisi un processus NLP pour notre système de recommandation : Tf-Idf.
 					
### 3.2.	Prédire l'évaluation de l'utilisateur	
Enfin, le système de prédiction de l'évaluation de l'utilisateur.

## Conclusion
Ce projet s'est avéré constructif car il nous a permis de prendre conscience des possibilités offertes par spark pour le traitement de données importantes, à travers un cas d'utilisation grand public, à savoir le cinéma.

Néanmoins, les modèles créés dans ce projet ne sont pas performants en raison de la mauvaise qualité du jeu de données utilisé pour les entraîner. En effet, ce jeu de données présente trop de Nan, beaucoup de valeurs nulles, du JSON dans les colonnes ou un mauvais parsing. Il est donc important de nettoyer et de prétraiter soigneusement le jeu de données avant d'entraîner les modèles afin de garantir les meilleurs résultats possibles.

