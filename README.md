# Recommendation-Engine-for-IBM-Watson
Recommendation Engine to make recommendations to users about new articles on IBM Watson Studio platform.  

## Overview  
For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.  
![image](https://user-images.githubusercontent.com/40590709/82734385-564f7a00-9d38-11ea-9150-cd6325727388.png)  

### Features
The recommender system can make recommendations in a number of ways:
1. Rank Based Recommendations
> - To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
2. Collaborative Filtering
> - In order to build better recommendations for the users of IBM's platform, I could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.
3. SVD - Matrix Factorization Recommendations
> - Finally, I will complete a machine learning approach to building recommendations. Using the user-item interactions, I will build out a matrix decomposition.  

## Files
- Recommendations_with_IBM.ipynb: Recommendations Engine, It describe how to recommend articles to users.
- Recommendations_with_IBM.html: As the same of above notebook but format is html.

## Acknowledgements

I wish to thank [IBM Watson Studio platform](https://dataplatform.cloud.ibm.com/) for dataset, and thank [Udacity](https://www.udacity.com/) for advice and review.
