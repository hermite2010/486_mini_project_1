* Joseph Bradley, Aaron Brown, Jackson Passey, Garrett Springer
* What processing steps did you take?
  * We cleaned a lot of the data. Some important factors like state and city we thought would be importatnt to include had to be encoded. We tried some pipelines, but we found our best model through experimentation on the parameters, and what would reasonably run.
* How did you tune hyperparameters
  * This process utilized online resources and chat gpt to help guide us to which hyperparameters would be most influential. It was through consistent trial and error to help us find the best parameters.
* How did you select your final model and what was it?
  * We selected XGboosting as our final model. We tried a few other models like random forest and lasso, but the XGboosting gave us the best score.
* What is your out-of-sample mean absolute error?
  * 105.3
* What features seem to be the most important in the prediction?
  * Our most important features were city
  * Our other features were not as important, and they were the maximum maximum nights, maximum nights on average, and the host listing counts.
