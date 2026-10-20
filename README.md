Social Media Engagement Analytics Using Python

Project Overview

Social Media Engagement Analytics Using Python** is a data analytics project that analyzes **5,000 social-media records** to understand content performance, user behavior, and engagement patterns.

The project analyzes metrics such as **likes, comments, shares, impressions, watch time, follower count, and engagement rate**, along with factors such as post type, content category, country, sentiment, gender, device type, and account verification.

The main objective is to transform raw social-media data into meaningful insights that can support **data-driven content and marketing decisions**.

Objectives

* Import and understand the dataset
* Clean and preprocess the data
* Handle missing and duplicate values
* Standardize categorical data
* Check unrealistic numerical values
* Create features such as `engagement_score` and `hashtag_count`
* Perform exploratory data analysis
* Calculate descriptive statistics
* Analyze correlations between numerical variables
* Create meaningful visualizations
* Generate business and behavioral insights

Dataset

File: social_media_engagement_5000.csv

The dataset contains **5,000 records and 19 original columns**.

Important features include:

* `age`
* `gender`
* `country`
* `post_type`
* `post_category`
* `likes`
* `comments`
* `shares`
* `watch_time_sec`
* `impression_count`
* `posted_at`
* `follower_count`
* `is_verified`
* `device_type`
* `sentiment`
* `hashtags`
* `engagement_rate`

Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Plotly

Install the required libraries:

pip install numpy pandas matplotlib seaborn plotly

Project Workflow

1. Data Import and Setup

The dataset was imported using Pandas. Dataset structure, columns, data types, and basic statistics were examined. The `posted_at` column was converted to datetime format, and NumPy was used for basic numerical operations.

2. Data Cleaning

The dataset was checked for missing values and duplicates. Missing numerical values were handled using the median, while categorical missing values were handled using the mode. Duplicate records were removed, categorical values were standardized, and unrealistic numerical values were checked.

A hashtag_count feature was created by counting hashtags in each post.

3. Exploratory Data Analysis

Pandas was used to analyze:

* Dataset structure
* Summary statistics
* Category distributions
* Unique values
* Correlations
* Post type performance
* Country performance
* Sentiment performance

4. Feature Engineering

New features were created, including:

engagement_score = likes + comments + shares
hashtag_count
year
month
day
weekday

GroupBy operations were also performed by post type, country, category, and sentiment.

5. Statistical Analysis

The following statistics were calculated for likes, comments, shares, watch time, engagement rate, and follower count:

* Mean
* Median
* Mode
* Standard deviation
* Variance
* Percentiles
* Skewness
* Kurtosis

6. Data Visualization

The project includes visualizations such as:

Matplotlib

* Likes vs impressions scatter plot
* Daily engagement trend
* Posts by category
* Gender distribution
* Age histogram
* Engagement rate box plot

Seaborn

* Post type count plot
* Average likes by category
* Followers vs sentiment violin plot
* Numerical feature pair plot
* Correlation heatmap
* Engagement vs device swarm plot

Plotly

* Interactive daily engagement chart

Business Insights

The analysis helps identify:

* Highest-performing post types
* Best-performing content categories
* Countries with higher average engagement
* Relationship between age and engagement
* Performance differences between verified and non-verified accounts
* Device impact on watch time
* Best-performing sentiment
* Differences between negative and neutral content

These insights can help businesses improve **content planning, audience targeting, campaign optimization, and social-media strategy**.

Project Structure

Social-Media-Engagement-Analytics/
│
├── social_media_engagement_5000.csv
├── Social_Media_Engagement_Analytics.ipynb
├── social_media_engagement_cleaned.csv
└── README.md

Conclusion

This project demonstrates a complete data analytics workflow using Python, from **data import and cleaning to exploratory analysis, feature engineering, statistical analysis, visualization, and business insight generation**.

The analysis shows how social-media data can be transformed into useful information for understanding **user behavior, content performance, and engagement patterns** and supporting data-driven business decisions.
