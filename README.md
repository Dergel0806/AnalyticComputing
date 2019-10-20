# AnalyticComputingInPython

## KMeansAndRecommendationSystem

Main goal of this project is to create clustering algorithm based on 3-5 features of college student, which should be used for creation of recommendation engine. Dataset for this research can be found [here](https://www.kaggle.com/borapajo/food-choices/version/5).

Data will be analyzed to find good variables for clustering, then subsetted and cleaned.

After this, number of clusters will be defined by doing additional investigations.

Then, three custom K-Means algorithms will be created (iterative, recursive and Class-based). Data will be clustered based on those algorithms and on sklearn.cluster.KMeans.

Clustered data will be investigated to get initial understanding of what does each cluster represent.
Based on this, basic dummy text for coupons will be created and function for printing coupon based on cluster will be implemented and tested on 10 random datapoints.

Results will be visualized by 2d prediction mesh with usage of t-SNE to reduce dimensions of training data.
