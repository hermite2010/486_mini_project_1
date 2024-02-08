* Joseph Bradley
* What processing steps did you take?
  * I knew that I should standardize any numerical variables, as well as encode any categorical variables that I wanted to use. I utilized pipelines and randomized search cross validation steps to put my model together.
* How did you tune hyperparameters
  * I utilized random search cross validation to help tune my KNN hyperparameters as well as some of the other parameters like weight and imputer strategy.
* How did you select your final model and what was it?
  * I used multiple correlation heat maps to make initial judgments about which numeric variables to include in my final model. I used chi-squared tests to determine which categorical variables I should use in my final model.
* What is your out-of-sample mean absolute error?
  * 197.39088976204897
* What features seem to be the most important in the prediction?
  * Since I used a KNN to predict, there were no coefficients, and no viable way to calculate estimated effects on the response. So there is no way for me to reasonably see what features were the most important for the prediction.
