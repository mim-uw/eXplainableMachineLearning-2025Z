# Homework 4

The purpose of the fourth homework is to become familiar with Integrated Gradients (IG). 

You may use any neural network vision model from https://huggingface.co/. 
You can choose any classification problem. 
There are many example models on huggingface, for example, for food classification.
You can also try to reproduce the classification example for wolf/husky classes shown in the paper on LIME.

Try to implement the IG method yourself, for which there is a full set of points. If you have problems, you can use existing implementations, for which there will be a part of points.

**You can follow a tutorial available at [https://www.tensorflow.org/tutorials/interpretability/integrated_gradients](https://www.tensorflow.org/tutorials/interpretability/integrated_gradients)**

Submit the homework to this directory.

## Deadline 

2025-11-28 EOD

## Task

For the selected two or three images and a vision model, prepare a knitr/jupyter notebook based on the following points.
Submit your results on GitHub to the directory `Homeworks/HW4`.

1. Calculate the predictions for selected observations
2. Implement Vanilla Gradients (VG, aka Saliency Map):
    - Calculate the derivative of model output with respect to input (use automatic differentiation)
    - Visualize the comparison of VG with and without multiplying by input image
3. Implement the full Integrated Gradients method
4. Visualize the comparison between IG and VG
5. Comment on the results obtained in (2) and (4)


## **Important note:**

Try to convert the jupyter notebook into an HTML file, e.g. using the following command in bash

```
jupyter nbconvert --to=html --template=classic FILE_NAME.ipynb
```

The submitted homework should consist of two parts:

1. The 1st part is the key results and comments from points (2) and (4). In this part **PLEASE DO NOT SHOW ANY R/PYTHON CODES, ONLY RESULTS (FIGURES, COMMENTS).**
2. The 2nd part should start with the word "Appendix" or "Załącznik" and should include the reproducible R/Python code used to implement points (1)-(6).

Such division: 1. will make this homework more readable, and 2. will develop good habits related to reporting.


