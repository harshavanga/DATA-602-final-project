# DATA_602_FINAL_PROJECT

This repository is all about the Jupyter Notebook that has some of the Machine Learning classification algorithms applied for the dataset "Housing Affordability Data System".

## DATA:

Source, the data had taken from: https://www.huduser.gov/portal/datasets/hads/hads.html which contains of 100 columns and 64,535 rows. 

## DATA DESCRIPTION:

The document is intended for housing professionals who are aware with current house affordability concerns and solutions. Footnotes are used to provide technical details about computer programming. The SAS program listings included with the datasets are for people who are familiar with SAS coding: https://www.huduser.gov/portal/datasets/hads/HADS_doc.pdf


## Objective:

The main objective of this project is to identify whether the US government assisted the citizens in their housing, if so how well the govenment assisted people in their housing.

## Overview of Machine Learning content:

1. Logistic Regression gave good results with 98 and 99 percent of recall and f1-score respectively. 
2. With less computation time, which stood out as a really good model
3. After applying the Regularization algorithm, we could not notice any difference in the results .
4. So, I would say that Logistic Regression worked really well.
5. I felt Decision Tree Classifier might work well on the data we have based on the way it actually works.
6. I expected some bettre results from this model, but we can say that precision and recall were not better than the ones that we used earlier.
7. The performance results that we got from Random Forest model were much better that Decision Trees.
8. We got a macro average accuracy of 99% with the Random Forest.
9. We got the same results with Support Vector like Logistic Regression and Random Forest which were really good.

## Conclusion:

Every model worked really well with good results except the Decision Tree.
We used Regularization to improve the results of Logistic Regression, but the results were not as expected.
There were multiple models which gave out the best results in terms of f1-scores and recall scores, particularly the Logistic Regression with regularization, support vector machine and random forest.
The highest macro avg recall we achieved was 98%.

## Final Model Selection:

I would go ahead with the random forest classifier because of the following reasons: 
1. Because of the type of classification we are doing, the nature of random forest classifier relates best. 
2. It gave out amazing results. With 100% precision, 97% recall and 98% f1 score, all macro averages. 
3. It took less time to build the model.
4. Since this model is ensemble, I have more confidence for less chance of error.

References:

https://github.com/appliedecon/data602-lectures/blob/main/regression/linear-regression-and-regularization.ipynb
https://github.com/appliedecon/data602-lectures/blob/main/logistic-regression/logistic-regression.ipynb
https://github.com/appliedecon/data602-lectures/blob/main/trees/trees.ipynb
https://github.com/appliedecon/data602-lectures/blob/main/supervised-algorithms/knn-nb-svm.ipynb



