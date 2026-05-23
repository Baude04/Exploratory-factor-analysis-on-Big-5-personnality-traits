# Exploratory factor analysis on Big 5 personality traits

This project is part of a broader work consisting of applying diverse clustering algorithms to the Big Five personality traits. We only provide here the first step of this process, i.e. the dimension reduction phase by exploratory factor analysis. 

Particular care has been taken to provide the underlying mathematical explanations for each statistical criterion and modeling approach used. Multiple EFA techniques have been tested, compared and explained.

`factor_analysis.qmd` is the script that performs factorial analysis on the `IPIP-FFM-data-8Nov2018` dataset (available on Kaggle). It will output a file `IPIP-50_FFM_factor_scores.csv` which contains the scores on the Big 5 scales of the 695,704 retained participants. These scores come from an EFA with minres factor extraction method on the polychoric matrix, varimax factor rotation, and Anderson scoring method.

The `factor_analysis.qmd` file also features a personality test that you can take. It will give you your scores on each Big 5 factor and the quartile you belong to.
