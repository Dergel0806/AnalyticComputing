### Food_recommendation_system

Main goal of this project is to create clustering algorithm based on 3-5 features of college student, which should be used for creation of recommendation engine. Dataset for this research can be found [here](https://www.kaggle.com/borapajo/food-choices/version/5).  
  
Data will be analyzed to find good variables for clustering, then subsetted and cleaned.  
  
After this, number of clusters will be defined by doing additional investigations.  
  
Then, three custom K-Means algorithms will be created (iterative, recursive and Class-based). Data will be clustered based on those algorithms and on `sklearn.cluster.KMeans`.  
  
Clustered data will be investigated to get initial understanding of what does each cluster represent.  
Based on this, basic dummy text for coupons will be created and function for printing coupon based on cluster will be implemented and tested on 10 random datapoints.  
  
Results will be visualized by 2d prediction mesh with usage of t-SNE to reduce dimensions of training data.


### USA_crimes_analysis

We want to conduct research on [crimes dataset](https://www.kaggle.com/marshallproject/crime-rates) and analyze data to find answers to questions about crime in different regions across the years.  
Research will be focused on comparing different agencies and states in terms of crime percapita and violent crimes. Other types of crimes will also be investigated.  
  
We'll investigate each type of crime separately and answer next questions. Those question will be researched from historical point of view, so, research will be conducted on both modern and historical data. 
What are the biggest and smallest values for each type of the crime in dataset, such as violent crimes, homicides, rapes, assaults and robberies?   
  
What are the safest states to live in and how much worse the situation is in the most dangerous states? Which states are the most dangerous and so, should have more attention from law enforcement?  
Which cities have most crimes per capita and what is other available data about them?
