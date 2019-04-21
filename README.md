# Information

Title: Costa Rican Household Poverty Level Prediction

Website: https://www.kaggle.com/c/costa-rican-household-poverty-prediction

Purpose:
- *Here's the backstory: Many social programs have a hard time making sure the right people are given enough aid. It’s especially tricky when a program focuses on the poorest segment of the population. The world’s poorest typically can’t provide the necessary income and expense records to prove that they qualify.*
- *In Latin America, one popular method uses an algorithm to verify income qualification. It’s called the Proxy Means Test (or PMT). With PMT, agencies use a model that considers a family’s observable household attributes like the material of their walls and ceiling, or the assets found in the home to classify them and predict their level of need.*

Scoring Metric: Accuracy
- Accuracy is one metric for evaluating classification models. Informally, accuracy is the fraction of predictions our model got right. Formally, accuracy has the following definition:
- Formula: (TP + TN)/(TP + FP + TN + FN)
    - TP: True Positives
    - FP: False Positives
    - TN: True Negatives
    - FN: False Negatives


MyBinder Jupyter Interactive Notebooks:
1. `00_DateNotebook.ipynb`: Provides an overview of the the finding/insights during the project.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexguanga/costa-rican-household-poverty-level.git/master?filepath=00_DateNotebook.ipynb)
2. `01_DateNotebook.ipynb`: An Exploratory Analysis on the dataset.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexguanga/costa-rican-household-poverty-level.git/master?filepath=01_DataNotebook.ipynb)
- `02_DateNotebook.ipynb`: A deeper analysis and visualization understanding on the dataset. 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexguanga/costa-rican-household-poverty-level.git/master?filepath=02_DateNotebook.ipynb)
- `03_DateNotebook.ipynb`: Implemented different models like Linear SVC, GaussianNB, MLPClassifier, LogisticRegressionCV, RidgeClassifierCV, LinearDiscriminantAnalysis, KNeigbhorsClassifier, ExtraTreeClassifier, and lgb.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexguanga/costa-rican-household-poverty-level.git/master?filepath=03_DataNotebook.ipynb)
- `04_DateNotebook.ipynb`: Implemented FeatureTools!
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexguanga/costa-rican-household-poverty-level.git/master?filepath=04_DateNotebook.ipynb)