
**Project:** Predicting Income Bracket for US residents

**Project goal.** The goal of this project is to train and tune a binary random forest classifier to predict whether a person makes below or above the 50k threshold and analyze what features are correlated with income.

**Data and Features.** The data set was taken from [here](https://www.kaggle.com/uciml/adult-census-income).

**Modeling.** After doing a quick baselining with a basic random forest, I performed GridSearchCV and RandomizedSearchCV to tune and optimize model parameters. 

**Results.** The model was evaluated on the f1 score, since both precision and recall for both classes were important in this prediction problem. The parameters obtained from GridSearchCV gave the best f1 scores across the board and were chosen for testing on heldout data. Final f1 scores on unseen data: 0.89 for below 50k, 0.70 for above 50k.

