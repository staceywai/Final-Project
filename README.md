# Final-Project
Can factors x,y,z related to alcohol consumption predict happiness?
    happiness = output column, exclude from clustering
    List of variables 
    What is the most predictive variable?
    Linear regression
    Clusters would help define subgroups that are potentially related to happiness

## Data Sources:
Kaggle datasets pulled from GHO (Global Health Observatory) and WHO (World Health Organization), GWP (Gallup World Poll):
World Alcohol Consumption - https://www.kaggle.com/codebreaker619/alcohol-comsumption-around-the-world
2020 World Happiness - https://www.kaggle.com/londeen/world-happiness-report-2020
Life Expectancy - https://www.kaggle.com/augustus0498/life-expectancy-who
10 Clustering Algorithms - https://machinelearningmastery.com/clustering-algorithms-with-python/
SKlearn Clustering Documentation - https://scikit-learn.org/stable/modules/clustering.html
Kmeans Clustering Intro - https://www.geeksforgeeks.org/k-means-clustering-introduction/
Optimal Value in K - https://www.geeksforgeeks.org/ml-determine-the-optimal-value-of-k-in-k-means-clustering/?ref=rp
Elbow Curve - https://www.geeksforgeeks.org/elbow-method-for-optimal-value-of-k-in-kmeans/
SKLearn Preprocessing = https://scikit-learn.org/stable/modules/preprocessing.html
Data Normalization - https://towardsdatascience.com/data-normalization-with-pandas-and-scikit-learn-7c1cc6ed6475

## Tasks:
Question

Combine data sets - Jupyter notebook, join by country
Understand what the variables are
Linear regression model
    compare 2 columns, would happiness always be one of the comparison columns?
    slope tells you how related 2 columns are
Cluster analysis - comparing any 2 columns together to see if there is correlation by grouping
    compare 2 columns - form clusters, then look at happiness

Hypothesis

Conclusions...
Visualizations

## Next Steps:

1) Normalize Data
2) Run it through the correlation matrix
3) Choose columns with correlation values > .5 or < -.5
4) Run them through clustering
5) Elbow method to choose number of clusters
6) Color each data point by happiness score
7) Determine trends in each cluster
8) Multiple Linear Regression

