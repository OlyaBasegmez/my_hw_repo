### ***Project 3 Feedback***

***Nico Van de Bovenkamp***
***

**Overall:** Good work on this homework! You made great use of several packages, and exhibit that you have a solid understanding of what odd rations and how logistic regression works. One note, though it is silly and truly not necessary, but the homework wanted you to calculate the odds ratios by hand for each prestige (which you would never do in practice, really). But good job on Interpreting them!

 **A note on modeling:**
At times, model evaluation and evaluation metrics can get a bit lost because we spend a lot of time just understanding what these models are and how to run them. Think about what metrics you could use to measure how well your model learned the data! ROC Curves and AUC scores are very, very handy for classifiers. And try out some different models, hyper-parameters (regularization), cross validation, and loss-functions.

**Code issues:**
There is an issue with how you have defined 'train_cols' and the joining of the 'combos' dataframe with the dummy variables. In particular, you will notice that 'train_cols' has Prestige_1.0 and your combos has Prestige_1 (without the .0 at the ends!). We can look over this in class.
