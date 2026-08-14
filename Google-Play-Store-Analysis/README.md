# Google Play Store Analysis - OIBSIP Task 3

## Objective

To perform Exploratory Data Analysis (EDA) and Sentiment Analysis on Google Play Store apps to understand app categories, ratings, installations, pricing, content ratings, genres, and user feedback.

## Dataset

The Google Play Store dataset contains information about applications with the following columns:

* App
* Category
* Rating
* Reviews
* Size
* Installs
* Type
* Price
* Content Rating
* Genres
* Last Updated
* Current Ver
* Android Ver

A separate user reviews dataset was used for sentiment analysis.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* TextBlob
* Jupyter Notebook

## Analysis Performed

* Loaded and explored the Google Play Store dataset.
* Checked data types, missing values, and duplicate records.
* Cleaned and converted the `Installs` and `Price` columns into appropriate numeric formats.
* Analyzed the number of apps by category.
* Analyzed the distribution of app ratings.
* Identified the most reviewed and most installed apps.
* Compared Free and Paid applications.
* Analyzed apps by Content Rating and Genre.
* Compared average ratings across categories and app types.
* Analyzed the price distribution of paid applications.
* Performed sentiment analysis on user reviews.
* Analyzed Positive, Negative, and Neutral user sentiments.
* Compared sentiment distribution across applications.

## Key Insights

* **Family** has the highest number of apps, followed by Game and Tools.
* The average app rating is approximately **4.20**.
* Free apps are much more common than paid apps.
* Most apps have an **Everyone** content rating.
* Positive reviews are more common than Negative and Neutral reviews.
* Paid apps have a slightly higher average rating than free apps.
* Popular applications such as WhatsApp Messenger, Facebook, and Instagram have very high installation and review counts.
* User sentiment varies across different applications, with some popular apps receiving a considerable number of negative reviews.

## Conclusion

The Google Play Store Analysis provides useful insights into app categories, ratings, installations, pricing, content ratings, genres, and user reviews. The analysis shows that free applications dominate the dataset and that most applications have positive ratings and user feedback.

The sentiment analysis also shows that Positive reviews are the most common, while some popular applications receive a significant number of Negative reviews. These insights can help developers understand user preferences and improve application quality and user experience.

## Business Recommendations

1. Focus on popular and competitive categories such as Family, Game, and Tools.
2. Monitor negative user reviews regularly to identify problems and improve app quality.
3. Analyze highly installed and highly reviewed applications to understand factors contributing to popularity.
4. Maintain high quality in paid applications because they have a slightly higher average rating than free applications.
5. Use positive user feedback to identify successful features and improve future app updates.

