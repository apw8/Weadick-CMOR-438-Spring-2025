# Boosting

Boosting is an ensemble method that trains predictors sequentially, each trying to correct the errors made by the previous predictor. Some well known boosting methods include AdaBoost and gradient boosting. My implementation uses AdaBoost, in which the training algorithm first trains a base classifier and uses it to make predictions on the training set. Then, each of the misclassified training instances is given a relative weight. The next classifier is then trained on the dataset using these relative weights, and so on. The idea is that whenever a classifier misclassifies a data point, this data point is then boosted to signal difficulty in classification.

# Datasets

I used the palmer_penguins dataset, which is a dataset that contains information about the island, bill length (mm), bill depth (mm), flipper length (mm), body mass (g), and sex of Adelie, Chinstrap, and Gentoo penguins. It was collected by Dr. Kristen Gorman and the Palmer Station in Antarctica.

# Libraries

The following packages are needed to reproduce my results:
matplotlib.pyplot
numpy
pandas
seaborn
scikit-learn