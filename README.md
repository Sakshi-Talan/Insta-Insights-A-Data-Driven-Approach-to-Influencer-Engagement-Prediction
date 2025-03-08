# Insta-Insights-A-Data-Driven-Approach-to-Influencer-Engagement-Prediction

### Project Overview

This project aims to predict the engagement rate of Instagram influencers based on various features such as followers, posts, average likes, and country. The engagement rate is a crucial metric for brands to identify the right influencers for marketing campaigns. By building a predictive model, we can help businesses make data-driven decisions when selecting influencers, ensuring higher ROI and more effective marketing strategies.

### Key Features

## Data Analysis:
- Cleaned and preprocessed a dataset of top Instagram influencers, including features like rank, followers, posts, average likes, and engagement rates.
- Performed exploratory data analysis (EDA) to uncover trends and insights.

## Feature Engineering:
- Created new features such as engagement ratio and growth rate to better understand influencer performance.

## Machine Learning Models:
- Built a Random Forest Regressor to predict influence scores.
- Developed a Random Forest Classifier to categorize engagement rates into Low, Medium, and High.

## Clustering:
- Used KMeans clustering to group influencers into categories like High-profile, Rising, and Niche based on their followers and engagement metrics.

## Visualization:
Created insightful visualizations, including:
- Distribution of influence scores.
- Engagement rate vs. followers.
- Top countries with the most influencers.
- Confusion matrix for classification performance.
- True vs. predicted influence scores.

##  Insights and Recommendations:
- Provided actionable insights for businesses, such as prioritizing mid-tier influencers and targeting high-engagement regions.

### Dataset Overview

The dataset contains information about the top Instagram influencers, including:

1. Rank: The rank of the influencer based on their influence score.
2. Channel Info: The Instagram handle or username of the influencer.
3. Influence Score: A score representing the overall influence of the account.
4. Posts: The total number of posts published by the influencer.
5. Followers: The total number of followers the influencer has.
6. Average Likes: The average number of likes per post.
7. 60-Day Engagement Rate: The engagement rate over the last 60 days.
8. New Post Average Likes: The average number of likes on new posts.
9. Total Likes: The total number of likes across all posts.
10. Country: The country where the influencer is based or primarily operates.
11. Engagement Ratio: The ratio of average likes to followers.
12. Growth Rate: The growth in engagement over time.
13. Engagement Category: Engagement rate categorized as Low, Medium, or High.
14. Country Encoded: Numerical representation of the country for machine learning.

### Key Insights

1. Engagement vs. Followers:
- Mid-tier influencers with moderate followers tend to have higher engagement rates than mega influencers.
2. Country-Specific Trends:
- Countries like Russia, UAE, and Brazil show the highest average engagement rates.
3. Posting Frequency:
- Frequent posting may lower overall engagement; a balanced strategy is recommended.
4. Influencer Categories:
- Influencers can be grouped into High-profile, Rising, and Niche categories based on their followers and engagement metrics.
5. Model Performance:
- The classification model achieved 90% accuracy in predicting engagement categories.
- The regression model had a low R² score (0.015), indicating room for improvement with additional data features.

### Recommendations for Businesses

1. Select the Right Influencers:
- Prioritize engagement rate over follower count.
- Focus on mid-tier and niche influencers for higher ROI.
2. Expand into High-Engagement Markets:
- Target regions like Russia, UAE, and Brazil for localized campaigns.
3. Improve Influencer Campaigns:
- Encourage quality content over high-frequency posting.
- Avoid influencers with high followers but low engagement (potential fake followers).
