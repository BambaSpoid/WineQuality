# Predire la qualite du vin

# Kaggle Challenge - Knowledge

## Les informations pertinentes:

   Les deux ensembles de données sont liés aux variantes rouges et blanches du vin portugais "Vinho Verde".
   Pour plus de détails, consulter: http://www.vinhoverde.pt/en/ ou la référence [Cortez et al., 2009].
   En raison de problèmes de confidentialité et de logistique, seules les variables physico-chimiques (entrées) et sensorielles (sorties)
   sont disponibles (par exemple, il n'y a pas de données sur les types de raisin, la marque de vin, le prix de vente du vin, etc.).

  ## Challenge

  Ces ensembles de données peuvent être considérés comme des tâches de classification ou de régression.
   Les classes sont ordonnées et non équilibrées (par exemple, il y a plus de vins normaux
   excellents ou mauvais). Des algorithmes de détection des valeurs aberrantes pourraient être utilisés pour détecter les quelques excellents
   ou des vins pauvres. De plus, nous ne savons pas si toutes les variables d'entrée sont pertinentes. Alors
   il pourrait être intéressant de tester les méthodes de sélection des fonctionnalités.




## Objectif

- Prédire la qualite du vin

1- Utilisez la stratégie de classification pour collecter et prétraiter les données, 
2- Choisissez un modèle, entraînez-le et évaluez-le. 
3- Parametrez les hyperparamètres pour faire la meilleure prédiction d'apprentissage automatique.

#### Remarque: plusieurs des attributs peuvent être corrélés, il est donc logique d'appliquer une sorte de sélection de fonctionnalité. 

Nombre de lignes: 6497
- vin rouge : 1599
- vin blanc : 4898
Nombre de colonnes: 12

Valeurs manquantes: Aucune
       
###  Classification : KNeighborsClassifier, 


Score:  
  * Train set: 0.94   
  * Test set:  0.94   


Score apres evaluation:
  * Train set: 0.95     
  * Test set:  0.95    
  


## Auteur
Bamba Spoid

Les retours sont toujours les bienvenus
