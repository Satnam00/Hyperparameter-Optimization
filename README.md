![1_6pCDA5Tbeu7nP3w2zCb6Sg](https://user-images.githubusercontent.com/39052765/88723742-ffef2500-d146-11ea-9b8a-f2474d890cd5.jpeg)

# Hyperparameter-Optimization
### Introduction
Hyperparameters are important because they directly control the behaviour of the training algorithm and have a significant impact on the performance of the model is being trained. “A good choice of hyperparameters can really make an algorithm shine”. Easy to manage a large set of experiments for hyperparameter tuning.

### Hyperparameter Optimization: This Tutorial Is All You Need
https://www.youtube.com/watch?v=5nYqK-HaoKY&t=2277s

# Grid Search
https://www.kaggle.com/satnam007/hyper-parameter-grid-search
Grid search is arguably the most basic hyperparameter tuning method. With this technique, we simply build a model for each possible combination of all of the hyperparameter values provided, evaluating each model, and selecting the architecture which produces the best results.

For example, we would define a list of values to try for both n_estimators and max_depth and a grid search would build a model for each possible combination.

# Random Search
https://www.kaggle.com/satnam007/hyper-parameter-randomized-searchcv
Random search differs from grid search in that we longer provide a discrete set of values to explore for each hyperparameter; rather, we provide a statistical distribution for each hyperparameter from which values may be randomly sampled.

![grid_vs_random](https://user-images.githubusercontent.com/39052765/88724579-60329680-d148-11ea-8f52-f34e484d6512.png)

# Grid/Random Search with Pipelines
https://www.kaggle.com/satnam007/grid-randomsearchcv-with-pipelines


# Bayesian Optimization with Gaussian Process
https://www.kaggle.com/satnam007/bayesian-optimization-with-gaussian-process
The previous two methods performed individual experiments building models with various hyperparameter values and recording the model performance for each. Because each experiment was performed in isolation, it's very easy to parallelize this process. However, because each experiment was performed in isolation, we're not able to use the information from one experiment to improve the next experiment. Bayesian optimization belongs to a class of sequential model-based optimization (SMBO) algorithms that allow for one to use the results of our previous iteration to improve our sampling method of the next experiment.


# Hyperopt
https://www.kaggle.com/satnam007/hyperopt

# Great link to reffer:-
http://hyperopt.github.io/hyperopt/

# Optuna
https://www.kaggle.com/satnam007/optuna
Optuna, a hyperparameter optimization (HPO) framework designed for machine learning written in Python, is seeing its first major version release. It is a new framework that aims to make HPO more accessible as well as scalable for experienced and new practitioners alike.

# Great link to reffer:-
https://medium.com/optuna/optuna-v1-86192cd09be5



## good artcle to refer
https://towardsdatascience.com/hyperparameters-optimization-526348bb8e2d

## good artcle to refer
https://scikit-optimize.github.io/stable/modules/generated/skopt.gp_minimize.html
