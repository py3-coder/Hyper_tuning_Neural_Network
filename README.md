# Hyper_tuning_Neural_Network

Ways to hyperparameter tuning:

- Manual Hypertuning

- Automatic hyperparameter tuning

1.   Random search 
2.   Grid  search
3.   Bayesian optimixation

## Random search : 
In the random search method, we create a grid of possible values for hyperparameters. Each iteration tries a random combination of hyperparameters from this grid, records the performance, and lastly returns the combination of hyperparameters which provided the best performance.

## Grid Search :
In the grid search method, we create a grid of possible values for hyperparameters. Each iteration tries a combination of hyperparameters in a specific order. It fits the model on each and every combination of hyperparameter possible and records the model performance. Finally, it returns the best model with the best hyperparameters. 

![image](https://user-images.githubusercontent.com/54509629/126820027-7292922b-a65a-4252-8fe5-d1b256b3d2cb.png)

## Bayesian Optimization :
Tuning and finding the right hyperparameters for your model is an optimization problem. We want to minimize the loss function of our model by changing model parameters. Bayesian optimization helps us find the minimal point in the minimum number of steps. Bayesian optimization also uses an acquisition function that directs sampling to areas where an improvement over the current best observation is likely.

## Keras-tuner
Link_documentation :https://keras.io/guides/keras_tuner/getting_started/

Easy and Scalable libray for optimizing the deep learning models
