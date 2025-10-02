# Homework 3

The purpose of the third homework is to become familiar with Ceteris Paribus (CP) and Partial Dependence profiles (PDP), and its variants like Accumulated Local Effects (ALE). 

Take a model from HW3 (or any other) and calculate CP and PDP explanations. Write down some conclusions.

Focus on the presentation of results; for technical issues, seek support at [Materials towards Homework 4: CP and PDP with XGBoost](https://mim-uw.github.io/eXplainableMachineLearning-2023/hw4_cp_and_pdp_with_xgboost_on_titanic.html).

Submit the homework to this directory.

## Deadline 

2025-11-21 EOD

## Task 1

Consider a following model:

f(x1, x2) = (x1 + x2)^2

Assume that x1, x2 ~ U[-1,1] and x1=x2 (full dependency)

Calculate PD profile for variable x1 in this model.

Extra task if you do not fear conditional expected values: Calculate ME and ALE profiles for variable x1 in this model.


## Task 2

1. Take a model from HW3 (or any other). 
2. Select two observations from the corresponding dataset. 
3. Calculate and plot Ceteris Paribus / ICE profiles for these observations (for selected/important variables).
4. Implement PDP explanations and plot them for selected/important variables.
5. (bonus, ext extra points here) Implement ME or ALE explanations and plot them for selected/important variables.
6. ! COMMENT on the results obtained in (3)-(5)

Submit your results on GitHub to the directory `Homeworks/HW3`.


## **Important note:**

Try to convert the jupyter notebook into an HTML file, e.g. using the following command in bash

```
jupyter nbconvert --to=html --template=classic FILE_NAME.ipynb
```

The submitted homework should consist of two parts:

1. The 1st part is the key results and comments from points (3)-(5). In this part **PLEASE DO NOT SHOW ANY R/PYTHON CODES, ONLY RESULTS (FIGURES, COMMENTS).**
2. The 2nd part should start with the word "Appendix" or "Załącznik" and should include the reproducible R/Python code used to implement points (1)-(5).

Such division: 1. will make this homework more readable, and 2. will develop good habits related to reporting.

