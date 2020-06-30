# Coursera Capstone Final Project

This is a repository for the capstone project of the IBM Data Science course. Our goal is to find the best location for a new restaurant in Brussels. There is a great variety of restaurants in the city, so it is clear that in order to succeed in this area we must follow a strategical plan. In this scenario, we highlight some points that we need to take into account:
  * Demographic Considerations 
  * Location
  * Target Market
  * Competition
All the data used in our research is available on the following websites:
  * [https://statbel.fgov.be](https://statbel.fgov.be)
  * [http://monitoringdesquartiers.brussels](http://monitoringdesquartiers.brussels)
We use FourSquare API to obtain the venue data for all neighbourhoods in Brussels. In this part, we will analyse the type of restaurant that makes most success. In order to better compare the results we plot a graphic with the top 10 foods in Brussels. Then, we employ the k-means clustering analysis to identify the features. To obtain the best value for k, we apply two methods: The Elbow and The Silhouette Methods. Then, we explain why one method does give not give the optimal value. Once we obtain the value of k, we create a new DataFrame that includes the clusters, and we proceed to obtain a visualization of the resulting clusters. To get an idea of the area we use folium.map to plot the areas where the clusters are. Finally, our last step consists in examining these clusters. In doing so, we allocate the most suitable areas for opening our restaurant.
