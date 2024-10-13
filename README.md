# MOVIELENS RECOMMENDATION SYSTEM.

![Movie](https://github.com/user-attachments/assets/45199a31-fac2-4921-957e-1e19fe3f65fe)

## 1.0 BUSINESS UNDERSTANDING
### Overview
In today’s data-driven world, recommendation systems are crucial for filtering information and enhancing user experiences. These systems help users discover relevant content by analyzing their past interactions, such as search queries or viewing histories.

Major platforms like Netflix and YouTube utilize recommendation algorithms to suggest movies and videos that cater to individual preferences, enhancing user engagement.

Aligned with our project objectives, we aim to leverage the power of data analysis to build an efficient movie recommendation system. Our goal is to deliver personalized movie suggestions by analyzing users’ previous movie ratings and interactions.

By doing so, the system will generate top 5 tailored movie recommendations for each user, improving their viewing experience and aligning with their unique preferences.

## Problem Statement
![problem_statment](https://github.com/user-attachments/assets/c999d5a6-4bb1-4f40-a26c-070fd37035e8)
With the vast amount of content available on streaming platforms, users often feel overwhelmed by choices, making it difficult to discover movies that align with their preferences. Traditional search methods fall short in addressing this challenge, resulting in a less satisfying user experience and decreased engagement.

MovieLens has tasked our team of data scientists with optimizing their recommendation system through data-driven approaches. By analyzing user behaviors and preferences, we aim to enhance the system's ability to deliver personalized movie recommendations.

## objectives
![objective image](https://github.com/user-attachments/assets/1e09790b-bdf0-434b-bdd8-e34c29a41903)
### Main Objective

Building a model that provides top 5 movie recommendations to a user, based on their ratings of other movies.

### Specific Objectives

1. Implement Content-Based Filtering for Existing Users

2.  Mitigate the Cold Start Problem by:

   - Promoting Movie Popularity
   - Content-Based Filtering

3.  Evaluate the Recommendation System Performance
4.  Analyze Movie Rating Frequency

## Model Implementation
- KNNbasic Model.
- Singular Value Decomposition(SVD)
## Evaluation
The project's success criteria is determined by achieving a Root Mean Squared Error (RMSE) of 0.50.


### Findings
- On a scale of 0.5 to 5.0, the analysis shows that most movies received an average rating of 4.0, indicating that users generally rated the majority of films positively. This suggests a tendency for users to favorably evaluate the available content, with few movies receiving extremely low ratings of 0.5.

- There is a noticeable spike around the year 2000, where the number of ratings peaked at over 10,000.This might imply that there was a surge in user activity, perhaps due to the popularity of certain movies or the increased availability of the platform at the time.

- The gragh shows that the genres "Drama" and "Comedy" are the most popular among the movies in the dataset, with significantly higher counts compared to other genres.

- Despite the relatively lower number of Western movies produced, this genre stands out due to its impressive average ratings, surpassing those of other genres. This observation suggests that while Western films may not be as prolific as others, they resonate more strongly with audiences, gaining higher appreciation and positive feedback.

-The analysis indicates that the majority of films were produced in 1994. One might expect this year to reflect the highest ratings. However, the ratings distribution graph reveals that 2000 actually had the highest number of ratings, despite a lower volume of films produced in that year compared to 1994.

## Conclusions:
1. Personalized movie recommendations, based on collaborative filtering, leverage this positive rating trend to suggest films that align with users' favorable preferences, enhancing engagement and satisfaction.

- The content-based filtering system for existing users can capitalize on popular movies from high-activity periods, like 2000, to recommend similar films based on their attributes, thereby boosting relevance for users familiar with iconic movies from that era.

- The system mitigates the cold start problem for new users by offering genre-based recommendations, ensuring that even without prior interaction, users can select popular genres like Drama and Comedy and receive top-rated films within those categories.

-  For new users, in addition to recommending top-rated films regardless of genre, the system can highlight highly rated niche genres like Westerns to encourage exploration of movies that may resonate more strongly with audiences, despite their lower production volume.

- The final model's performance evaluation, based on RMSE of 0.50, confirms the system's ability to make accurate recommendations, closely matching the high average user ratings observed in the dataset

## Recommenditions
1. The dynamic film industry requires datasets to stay updated with new releases to match changing audience preferences and trends.

2. Including detailed information about filmmakers like screenwriters and producers can improve recommendations by suggesting similar films created by the same talent.

3. Expanding genre classifications to include niche categories promotes inclusivity and encourages exploration, enriching the user experience.

4. Leveraging user location data can help address the cold start problem by recommending regionally popular movies to new users from the same area.

5. Integrating external data sources like reviews and social media sentiment can enhance recommendations with insights on movie popularity and trends.

## Author and Acknowledgement:
Special thanks to our Moringa School Data Science Technical Mentors for their guidance throughout the project. We would also like to acknowledge the contributions our gorup members.

- 1.Ruth Kitasi
- 2.Agatha Nyambati
- 3.Joseline Apiyo
- 4.Cecilia Ngunjiri
- 5.John Mbego
- 6.Leonard Koyio



