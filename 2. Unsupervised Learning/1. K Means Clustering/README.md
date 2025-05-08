# K Means Clustering

K Means Clustering is an unsupervised machine learning algorithm that uses clustering to find groups. 'k' centroids are randomly selected. Then each point is assigned to the nearest centroid. This nearness is measured by a distance measure, which is Euclidean distance in this implementation. Each group is then assigned a new centroid based on the average. This is repeated, resulting in 'k' groups clustered using means.

# Datasets

I used the palmer_penguins dataset, which is a dataset that contains information about the island, bill length (mm), bill depth (mm), flipper length (mm), body mass (g), and sex of Adelie, Chinstrap, and Gentoo penguins. It was collected by Dr. Kristen Gorman and the Palmer Station in Antarctica.

# Libraries

The following packages are needed to reproduce my results:
matplotlib.pyplot
numpy
pandas
seaborn