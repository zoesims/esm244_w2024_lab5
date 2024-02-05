## ESM 244 Lab 5 Materials 

Prepared by: Allison Horst and Casey O'Hara

### Data used: 

Palmer penguins data from `palmerpenguins package:

Horst AM, Hill AP, Gorman KB (2020). palmerpenguins: Palmer Archipelago (Antarctica) penguin data. R package version 0.1.0. https://allisonhorst.github.io/palmerpenguins/. doi: 10.5281/zenodo.3960218.

### Objectives:

In this lab, we several candidate linear models to predict penguin body mass from a set of variables, and then apply various methods to compare and select among the candidate models.

* Compare models using information criteria
    * Akaike Information Criteria (AIC and AIC~c~)
    * Bayesian Information Criteria (BIC)
* Compare models using k-fold cross-validation
* Practice writing functions
    * function to calculate RMSE given predicted and observed values
    * function to train and test a single fold in a cross-validation
* Perform iterations using `for`-loops and `purrr`
