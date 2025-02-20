# Project Title: Insights into YouTube Channel Performance - A Data-Driven Approach

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Objective](#objective)
- [Analysis Approach](#analysis-approach)
- [Key Findings](#key-findings)
- [How to run code](#how-to-run-code)
- [Technologies Used](#technologies-used)
- [Results & Visualizations](#results--visualizations)
- [Recommendation](#Recommendation)
- [Contact](#contact)

## Overview:

The YouTube Channel Analysis project, built using R language, explores and analyzes the dataset of the most subscribed YouTube channels, collected by Nidula Elgiriyewithana from the Kaggle platform. The dataset provides valuable insights into channel performance, types, geographical distribution, and potential earnings.

## Dataset

The analysis is based on the Global YouTube Statistics 2023, obtained from Kaggle:

🔗 Global YouTube Statistics 2023 Dataset
- Source: [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023/data)
- Time Period Covered: 2023
- Number of Records: 995 rows
- Number of Features: 28 (17 numeric, 7 characters, 4 integers) 
- Key Variables: The data contains information about channel types, subscriber counts, video views, estimated earnings, country of origin, and more. Missing values were handled by dropping or imputing as needed to ensure data integrity.

## Objective

The primary objective of this R-based project is to analyze the performance of YouTube channels, identify trends in channel types, upload frequencies, and explore the relationship between channel performance and estimated earnings. The project also delves into geographical insights and recommends strategies for boosting channel performance.

## Analysis Approach

1. Data Cleaning: Handling missing values, transforming variables, and removing redundant columns.
2. Data Transformation: Converting variables to appropriate formats, adding new features, and normalizing data where needed.
3. Visualization: Creating plots and maps to explore top channels, upload frequencies, trending topics, correlations with earnings, and geographical distribution.
4. Interpret Results:
5. Recommendation:

## Key Finding: 
1. Top YouTube Channels: T-series, Cocomelon - Nursery Rhymes, and SET India are top channels in terms of subscribers and views.
2. Channel Type & Upload Frequencies: News and Entertainment channels lead in upload frequency, with Entertainment channels showing a correlation with higher engagement.
3. Trending Topics by Time: Entertainment channels remain consistently popular over time, with Music and Education channels also showing steady growth.
4. Correlation with Earnings: Video views correlate most strongly with earnings, suggesting a focus on engaging content to boost monetization.
5. Geographical Insights: The US and India dominate in terms of yearly earnings, with a notable gap before Brazil and Korea.

## How to run code
1. Open RStudio and load the project files to execute the code seamlessly

## Technologies Used
- R Code: Analyzed the dataset in RStudio, focusing on data cleaning, transformation, and visualization. Key libraries included tidyverse and ggplot2.

## Results & Visualizations

![image](https://github.com/user-attachments/assets/d6ebcd6b-6b91-4221-8d04-b1b8aac28c8d)
Figure 1: Subscriber vs Video view for Top 10 Channels

![image](https://github.com/user-attachments/assets/841aca09-6779-429a-be58-46f9ba298599)
Figure 2: Global Impact of Influential Creators by Video Views

Finding:
- T-Series, Cocomelon - Nursery Rhymes, and SET India dominate in terms of subscribers and views.
- The channel types that lead are Music, Education, and Entertainment, highlighting a strong audience preference for these categories.
- Some channels achieve higher views but fewer subscribers (and vice versa), suggesting different engagement strategies or content types.

![image](https://github.com/user-attachments/assets/134faed3-32e0-414f-9eb8-93f3cc9b2f94)
Figure 3: Most Popular Channel type by Upload Frequencies

Finding:
- News and Entertainment channels have the highest upload frequencies, but high frequency does not necessarily translate to higher subscribers or views.
- Entertainment channels seem to correlate well with high engagement, unlike News channels, which show a mismatch between upload frequency and engagement.

![image](https://github.com/user-attachments/assets/069a6b45-9fdd-4383-8f91-6b27f8093da0)
Figure 4: Number of channels are created by years

Finding:
- Entertainment channels have longevity and consistent creation over the years, showing strong and sustained demand.
- Music channels also maintain a presence but not as consistently as Entertainment.
- Channels in niches like Education, People, Games, Film, and Comedy are steadily growing, suggesting emerging opportunities.

![image](https://github.com/user-attachments/assets/f98f1d4c-20fa-4ef1-b3f0-e6eda4710cf9)
Figure 5: Correlation between Channel Performance vs. Earnings

Finding:
- Video views have the highest correlation with earnings, more so than upload frequency or subscriber count.
- Subscribers also correlate with views, indicating that a larger subscriber base can drive higher viewership but is not the sole factor for earnings.

![image](https://github.com/user-attachments/assets/d092821a-495b-4eec-a220-ed72e9d06447)
Figure 6: Location of Highest Yearly Earning by Country

![image](https://github.com/user-attachments/assets/28af58bb-7f87-4ccd-a748-c00e6a2f5810)
Figure 7: Highest yearly earnings By Country

Finding:
- The United States and India lead in yearly earnings, indicating strong YouTube markets in these regions.
- Brazil and Korea are emerging markets but with a noticeable gap compared to the US and India.

## Recommendation
1. Content Strategy:
- Create high-quality, engaging videos to boost views, which are highly correlated with earnings.
- Develop strategies to grow subscriber count, indirectly increasing viewership and earnings.
2. Channel Type Optimization:
- Focus on Entertainment, Music, and Education channels, which attract large audiences.
- Consider niche categories like People, Games, Film, and Comedy for steady growth.
3. Upload Frequency:
- Maintain consistent uploads, especially for Entertainment channels, to ensure sustained demand.
- Avoid excessive uploads for News channels; prioritize content quality and relevance.
4. Market Targeting:
- Focus on the US and India for monetization, as they generate the highest earnings.
- Explore growth opportunities in Brazil and Korea with localized content.
5. Monetization Strategies:
- Focus on video views and subscriptions, as both directly impact earnings.
6. Data-Driven Approach:
- Regularly analyze performance metrics and adjust strategies accordingly.
- Experiment with different content formats and engagement strategies to improve both subscribers and views.

## Contact

📧 Email: phanchenh99@gmail.com

🔗 [LinkedIn](https://www.linkedin.com/in/phan-chenh-6a7ba127a/) | Portfolio

