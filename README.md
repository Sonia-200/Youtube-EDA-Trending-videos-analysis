# 📊 Trending YouTube Video Analysis with Sentiment Insights

## 🎯 Project Objective:
To analyze trending YouTube videos using the YouTube Data API, extract useful insights about engagement patterns, and identify trends based on views, likes, comments, tags, and publishing time.

## 🗂 Dataset Source:
- Fetched using *YouTube Data API v3*
- Data includes video metadata like title, description, tags, category, views, likes, comments, publish time, etc.

## 🧹 Data Preparation:
- API Authentication and data extraction
- Converted JSON data into a structured Pandas DataFrame
- Handled missing values in tags and comments by filling with "No Tags" and "No Comments"
- Converted time-related fields to datetime objects
- Added Category Name using YouTube Category API

## 📈 Exploratory Data Analysis (EDA):
- Most liked, commented, and viewed videos
- Trending frequency per channel
- Publish time analysis (date and time trends)
- Category-wise video performance
- Pie and bar charts for visual representation

## 🧠 Key Insights:
- Most channels had only one trending video in the dataset
-Most Viewed and Commented Video: "War 2 Official Trailer" stands out as the most viewed and most commented video in the dataset.
- Most Liked Video: "Karuppa Tamil Teaser" received the highest number of likes, crossing 600,000.
- Trending Date Concentration: A majority of the videos trended on 26th July 2025, indicating a possible potential engagement on weekends.
- Optimal Publishing Time: Most trending videos were published between 2 PM – 4 PM, with a secondary engagement peak between 6 PM – 7 PM.
- Top Trending Category: The Music category featured the highest number of trending videos.
- Most Viewed Categories: Film & Animation recorded the highest views, followed closely by the Gaming category.
- Highest Engagement Ratio: Videos under the Entertainment category had the highest engagement ratio, accounting for 27.9% of the total.
- Sentiment Distribution: Most trending videos had positive sentiment in their descriptions.
- Views by Sentiment: Videos with positive sentiment descriptions attracted 56.1% of total views, while negative sentiment videos followed with 31.3%.

## 🧰 Tools & Libraries:
- Python, Pandas, Matplotlib, Seaborn
- YouTube Data API v3
- Datetime, Regex, JSON

## 📦 Deliverables:
- data folder containing Cleaned dataset (CSV)
- visuals folder containing all graphs and plots.
- EDA folder containing EDA notebook with insights and visuals.
