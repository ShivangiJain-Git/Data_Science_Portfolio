# DOMAIN : BEVERAGES/DRINKS 

- ### CONTEXT 
  This datasets is related to red variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) 
  variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

  These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

- ### OBJECTIVE 
  The objective of this case study is to assess wine quality using a decision tree, and test it against the wine-quality dataset from the UC Irvine Machine Learning Repository. 
  The wine dataset is a classic and very easy multi-class classification dataset.

- ### DATASET 
  winequality-red.csv

Variable - Description 

1. fixed acidity (tartaric acid - g / dm^3)

2. volatile acidity (acetic acid - g / dm^3)

3. citric acid (g / dm^3)

4. residual sugar (g / dm^3)

5. chlorides (sodium chloride - g / dm^3

6. free sulfur dioxide (mg / dm^3)

7. total sulfur dioxide (mg / dm^3)

8. density (g / cm^3)

9. pH

10. sulphates (potassium sulphate - g / dm3)

11. alcohol (% by volume)

 - Output variable (based on sensory data): quality (score between 0 and 10)


- ### Notebook
  Ensemble_Decision_Tree.ipynb                                          