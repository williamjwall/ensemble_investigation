# ensemble_investigation
# Investigating GBM
# The pipeline has three parts:

## PART 1 
Introducing the Data and Models: I believe it's important to get acquainted with data, The dataset made available by UC Irvine consists of 9 fields, 8 of which are features that
may be used to predict the variable: concrete comprehensive strength. LINK: https://lnkd.in/eJaJRNPb We will make a baseline model and optimize it.

## PART 2 
Gradient Boosting Algorithm as a Regressor: Having defined our parameters, we analyze their impact on the algorithm's performance. EX: the loss function was the huber
method.

## PART 3
Gradient Boosting Algorithm as a Classifier: The data is then transformed as a classification task. We use the default parameters from sklearn. The algorithm does not change
at this part but we need to use a loss function that handles a classification task. This actually complicates things and makes this part a lot longer and more complicated. It is a heavy
section with a lot of math and explains how things are tied together behind the scenes.
