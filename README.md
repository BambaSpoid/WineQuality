# Predicting the quality of wine

# Kaggle Challenge - Knowledge

## Relevant information:

   Both data sets are related to the red and white variants of the Portuguese wine "Vinho Verde".
   For more details, see: http://www.vinhoverde.pt/en/ or reference [Cortez et al., 2009].
   Due to confidentiality and logistical issues, only physicochemical (inputs) and sensory (outputs) variables
   are available (e.g., there is no data on grape type, wine brand, wine selling price, etc.).

## Challenge

   These data sets can be considered as classification or regression tasks. The classes are ordered and unbalanced (for example, there are more normal
   excellent or bad). Outlier detection algorithms could be used to detect the few excellent or poor wines. Moreover, 
   we do not know if all input variables are relevant. So it could be interesting to test feature selection methods.

## Goal

- Predicting wine quality

-1 Use the classification strategy to collect and preprocess data.
-2 Choose a model, train it, and evaluate it.
-3 Set the hyperparameters to make the best machine learning prediction.

#### Note: Several of the attributes may be correlated, so it makes sense to apply some sort of feature selection. 

Number of lines: 6497
- red wine: 1599
- white wine: 4898
- Number of columns: 12

Missing values: none
       
###  Classification : LogisticRegression, DecisionTreeClassifier ,KNeighborsClassifier 


Score:  
  * Train set: 0.94   
  * Test set:  0.94   


Score after evaluation:
  * Train set: 0.95     
  * Test set:  0.95    
  


## Author
Bamba Spoid

Feedback is always welcome
