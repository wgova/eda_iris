# eda_iris
A notebook to explore different types of useful visualisations for the purpose of exploratory data visualisation for classification

Exploratory data analysis to check for natural groups

The iris dataset has some evidence of groups based on the species, but with evidence that two of the three species (Iris versicola abd Iris virginica) have closely related properties. A clustering algorithm like k-means clustering might be able to separate these two species better, or find another dimension to separate the species.   
  
![Pairwise plot](https://github.com/wgova/eda_iris/blob/master/img/pairwise.png)

Poor separation of these species is clearly visible in the radviz plot, a multi-variate data based on a simple spring tension minimization algorithm.

![Radviz plot](https://github.com/wgova/eda_iris/blob/master/img/radviz.png)

These two species are also not easy to separate using Andrews curves, another simple multivariate visualisation aid plotted using the attributes of samples as coefficients for Fourier series.

![Andrews plot](https://github.com/wgova/eda_iris/blob/master/img/andrews.png)

The difficulty in separating the two iris species seems to be due to the fact that all their properties have similar magintudes of measurement, i.e Sepals (lengths and widths) and Petals (lengths and widths) 

![Measures against average for sepals](https://github.com/wgova/eda_iris/blob/master/img/aboveavg_scatter.png)

![Measures against average for petals](https://github.com/wgova/eda_iris/blob/master/img/petals.png)

As previously observed, based on the properties provided, there are two iris species that cannot be separated into separate groups.

![Ground truth groupings](https://github.com/wgova/eda_iris/blob/master/img/petals.png)

The elbow method and silhouette method both suggest that 3 clusters will be sufficient to cluster samples in the iris dataset

![Optimum clusters](https://github.com/wgova/eda_iris/blob/master/img/optimisation.png)



