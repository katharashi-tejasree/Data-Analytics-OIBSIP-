# Google Play Store Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) and Sentiment Analysis on Google Play Store applications. The analysis focuses on app categories, ratings, reviews, installations, pricing, content ratings, genres, and user feedback.

## Objective

- Analyze the distribution of apps across different categories.
- Understand app ratings and review counts.
- Identify highly installed and highly reviewed apps.
- Compare free and paid applications.
- Analyze content ratings and app genres.
- Analyze user review sentiments.
- Generate business insights and recommendations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses two datasets:

### Google Play Store Apps Dataset

The dataset contains information about Google Play Store applications, including:

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Ver
- Android Ver

### Google Play Store User Reviews Dataset

The user reviews dataset contains:

- App
- Translated Review
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

## Data Cleaning

The following data cleaning steps were performed:

- Checked for missing values.
- Removed duplicate records.
- Filled missing Rating values using the median.
- Filled remaining missing categorical values.
- Converted Reviews and Installs into numeric format.
- Removed currency symbols from the Price column.
- Converted Price into numeric format.
- Checked data types after cleaning.

## Exploratory Data Analysis

The following analyses were performed:

1. Number of Apps by Category
2. Distribution of App Ratings
3. Top 10 Most Reviewed Apps
4. Top 10 Most Installed Apps
5. Free vs Paid Apps
6. Apps by Content Rating
7. Top 10 App Genres
8. Average Rating by Category
9. Average Rating by App Type
10. Price Distribution of Paid Apps

## Sentiment Analysis

User reviews were analyzed based on:

- Positive, Negative, and Neutral sentiments
- Average Sentiment Polarity
- Average Sentiment Subjectivity
- Number of reviews by app
- Sentiment distribution by app

## Key Findings

- Family has the highest number of apps.
- The average app rating is approximately 4.20.
- Free apps are much more common than paid apps.
- Most apps have an Everyone content rating.
- Positive reviews are more common than Negative and Neutral reviews.
- Paid apps have a slightly higher average rating than free apps.
- Highly installed apps show strong user engagement.
- User sentiment varies across different applications.

## Business Recommendations

1. Focus on popular app categories such as Family, Game, and Tools because they contain a large number of applications.
2. Monitor negative user reviews regularly to identify common problems and improve user satisfaction.
3. Analyze highly installed and highly reviewed apps to understand factors contributing to app popularity.
4. Maintain high quality in paid applications because paid apps have a slightly higher average rating.
5. Use positive user feedback to identify successful features and improve future app updates.

## Conclusion

This project provided useful insights into Google Play Store applications, including app categories, ratings, installations, pricing, content ratings, genres, and user reviews.

The analysis shows that the Google Play Store contains a large variety of applications, with Family, Game, and Tools being some of the most common categories. Most applications are free and have an Everyone content rating.

The sentiment analysis also shows that Positive reviews are more common than Negative and Neutral reviews. Overall, the analysis demonstrates strong user engagement and generally positive user feedback while also highlighting opportunities to improve applications based on negative reviews.

## Author
K. Teja Sree
