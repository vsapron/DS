# Predictive Modeling of Coronary Heart Disease

In this project, I analyze data from a cardiovascular medicine study (/data *train.csv*). Practicing machine learning, the purpose is to fit a logistic regression model with available potential risk factors as predictors of coronary heart disease (CHD) over the course of 10 years. 

* Chosen classification metric: F1 score, due of imbalanced classes (85% have no CHD) and seeking to optimize for both precision and recall.
* Calculated optimal threshold: 0.53 at F1 score of 0.426
* The model remains suboptimal at detecting positives - actual CHD (precision 0.320; recall 0.637).
* Most influential risk factors were found be age and previous stroke (OR>2).   

Task is uploaded in /notebooks: *cardiovascular_study.ipynb*
