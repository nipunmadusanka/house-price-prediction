# house-price-prediction

I made a model to predict housing prices using Linear Regression and Gradient Boosting Regressor. First the accuracy I got using Linear Regression was 73% and then after using Gradient Boosting Regressor the accuracy increased to 91%.

<h2>Gradient Boosting Regressor</h2>
The Gradient Boosting Regressor is a machine learning algorithm utilized for regression tasks, which involve making predictions of continuous numeric values. It is a potent ensemble method that amalgamates multiple weak regression models, typically decision trees, to construct a robust predictive model.

The functioning of this algorithm entails iteratively augmenting the ensemble with additional regression models, where each new model focuses on rectifying the errors made by preceding models. This iterative process relies on the gradient descent optimization algorithm, which adjusts the parameters of the weak models to minimize the loss function.

During training, the gradient boosting regressor assigns weights to the training samples based on their residuals, which denote the disparities between the predicted and actual values. It subsequently trains a new weak model to fit these weighted residuals. In subsequent iterations, the algorithm persistently fits weak models to the residuals, with each new model being more concentrated on the remaining errors.

For making predictions, the gradient boosting regressor consolidates the predictions of all the weak models in the ensemble, often by computing their weighted average. The weights assigned to each weak model are determined by their performance during training, with more accurate models receiving higher weights.

A notable advantage of gradient boosting regressors is their proficiency in handling intricate relationships between features and target variables. They exhibit robustness against outliers and can effectively capture non-linear patterns within the data. Nonetheless, they may be susceptible to overfitting if the number of iterations (weak models) is excessively high or if the learning rate is set too high.
