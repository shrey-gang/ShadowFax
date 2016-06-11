# ShadowFax
Problem statement : Lots of Locations
As after looking at the data that has been provided, it seems that area locations are divided into several clusters on the basis of their geographic locations. As it seems to be a better approach to handle logistics, it can be utilized in a better way by using historic details to manage the number of riders in a specific cluster in specific time durations. It will lead us to a better utilization of available resources. 

So to solve such a real life problem, there are two aspects of it:

    Traffic Prediction based route finding mechanism : As we can rely on the api’s provided by Google to predict the time to use any specific route. But as even in the google’s api generally the static travel cost is being used for path calculation. As proposed in the Paper “An Online-Traffic-Prediction based route finding mechanism for Smart City” By Xiaguang Niu and team, presented in Intelligent Transportation System, we can utilize their approach to find the best available path for delivery.		 	 	 		

    Utilizing historical data of the demand in specific areas: Even though finding the quickest and shortest path solves a lot of the problem. But we can assure more accuracy and user satisfaction by utilizing our own historic data to predict the requirement of delivery riders in any area and then make our riders move to those areas/cluster on the different time duration on the basis of prediction of demand.

