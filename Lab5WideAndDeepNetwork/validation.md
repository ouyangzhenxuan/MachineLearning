From the analysis above, it's easy to see that most customers are retained, only a few customers close the account. Since the stratified split can deal with the imbalance, we will use the stratified split. And the anther advantage of the stratified method is to ensure a level of uniformity in the training so that it can ensure the model can fit our dataset well. The sample size of the database is relatively small, so 10-fold is a better choice for us. Each sample will be used to train and test. It will make our model more generalized. According to the above, we decide to use stratified 10-fold cross validation.