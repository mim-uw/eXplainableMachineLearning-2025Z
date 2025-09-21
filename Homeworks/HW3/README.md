# Homework 3

The goal of the third homework is to become familiar with SHapley Additive exPlanations (SHAP). 

Note that there are three subtasks and each is worth 50% of points.
Do two subtasks to get full credits. 
Solve third one to have some extra bonus.


Submit the homework to this directory.

## Deadline 

2025-10-31 EOD


## Task A

Calculate Shapley values for player A given the following value function

```
v() = 0
v(A) = 20
v(B) = 20
v(C) = 60
v(A,B) = 60
v(A,C) = 70
v(B,C) = 70
v(A,B,C) = 100
```

## Task B

For the selected models, prepare a knitr/jupyter notebook based on the following points.
Submit your results on GitHub to the directory `Homeworks/HW3`.

1. Download a dataset from this repository: https://github.com/adrianstando/imbalanced-benchmarking-set (the fewer variables, the easier it is to do your homework)
2. Train a predictive model on the selected dataset; it can be a random forest, NN, GBM, CatBoost, or any other model.
2. Select two observations from the dataset and calculate the model's prediction.
3. Next, for the same observations, calculate the decomposition of predictions, so-called variable attributions, using Shapley values. Implement the Shapley values algorithm on your own. (It is not necessary to calculate the exact Shapley values (those would be time-consuming). You can approximate them by several random permutations of the variables.)
4. Compare results with the one calculated with `shap` package (or any other package that implements this method)
5. Comment on the results obtained in points (4)-(7)

## Task C

The data you are working with is unbalanced.

For a trained model, calculate the Shapley values for different levels of balancing.

Do they differ? Does this surprise you?



## **Important note:**

Try to convert the jupyter notebook into an HTML file, e.g. using the following command in bash

```
jupyter nbconvert --to=html --template=classic FILE_NAME.ipynb
```

The submitted homework should consist of two parts:

1. The 1st part is the key results and comments from points (4)-(7). In this part **PLEASE DO NOT SHOW ANY R/PYTHON CODES, ONLY RESULTS (FIGURES, COMMENTS).**
2. The 2nd part should start with the word "Appendix" or "Załącznik" and should include the reproducible R/Python code used to implement points (1)-(5) & (7).

Such division: 1. will make this homework more readable, and 2. will develop good habits related to reporting.
