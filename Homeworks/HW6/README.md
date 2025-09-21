# Homework 6

The sixth homework aims to become familiar with Permutation-based Variable Importance (PVI) for models from Rashomon Set. 

Calculate these explanations on few models from RS and see if these estimates are consistent.

Focus on the presentation of results

Submit the homework to this directory.

## Deadline 

2025-11-28 EOD

## Task

For the selected dataset and models, prepare a knitr/jupyter notebook based on the following points (you can reuse models from previous Homeworks).
Submit your results on GitHub to the directory `Homeworks/HW6`.

0. Use data from HW3, train at least 10 complex models (tree based of neural network based, e.g. random forest, xgboost). You may get different models with playing with samples of data or some hyperparamteres.
1. Check their performance and choose small number of models that are epsilon worse than the best one (so called Rashomon set)
2. Implement the permutation based feature importance and apply it to each model from Rashomon Set
3. Compare PFI between models in RS. Are they similar? Different? 
4. ! COMMENT on the results obtained in (1)-(3)


## **Important note:**

Try to convert the jupyter notebook into an HTML file, e.g. using the following command in bash

```
jupyter nbconvert --to=html --template=classic FILE_NAME.ipynb
```

The submitted homework should consist of two parts:

1. The 1st part is the key results and comments from points (2)-(4). In this part **PLEASE DO NOT SHOW ANY R/PYTHON CODES, ONLY RESULTS (FIGURES, COMMENTS).**
2. The 2nd part should start with the word "Appendix" or "Załącznik" and should include the reproducible R/Python code used to implement points (1)-(5).

Such division: 1. will make this homework more readable, and 2. will develop good habits related to reporting.


