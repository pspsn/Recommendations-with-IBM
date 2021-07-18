# Recommendations-with-IBM
This project was designed to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles.

## Summary:
The project diviกed the following tasks:
- Exploratory Data Analysis: Find out the distribution of articles a user interacts within the dataset and provide a visual and descriptive statistics.
- Rank Based Recommendations: To get started in building recommendations, I first find the most popular articles based on the most interactions. Provide two functions to get n top articles names and n top articles ids.
- User-User Based Collaborative Filtering: In order to build better recommendations for the users of IBM's platform, I look at users that are similar in terms of the items they have interacted with. These items could then be recommended to similar users.
- Matrix Factorization: Finally, I completed a machine learning approach to building recommendations to the users on the IBM Watson Studio platform. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition (Single value decomposition, SVD), I got an idea of how well I can predict new articles an individual might interact with.    

## Data
- user-item-interactions.csv: file contains user interaction.
- articles_community.csv: file contains articles description.  

## Acknowledgments
I would like to thank [Udacity](https://eu.udacity.com/) for this amazing project, and [IBM](https://dataplatform.cloud.ibm.com/) for providing the data.
