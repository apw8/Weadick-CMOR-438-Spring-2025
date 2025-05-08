# Bagging

The term bagging refers to bootstrap aggregating. Bootstrapping is a method of inferring results for a population from results found on a collection of smaller random samples of that population, using replacement during the sampling process. In the context of machine learning, a given set of machine learning models is trained respectively on random samples of training data with replacement, then the combined predictions of each model is aggregated and used as a single prediction. For regression tasks, this would mean taking the average of the set of model prediction, and for classification, taking the mode.

# Datasets

I used the palmer_penguins dataset, which is a dataset that contains information about the island, bill length (mm), bill depth (mm), flipper length (mm), body mass (g), and sex of Adelie, Chinstrap, and Gentoo penguins. It was collected by Dr. Kristen Gorman and the Palmer Station in Antarctica.

# Libraries

The following packages are needed to reproduce my results:
matplotlib.pyplot
numpy
pandas
seaborn
scikit-learn