# ![image](https://github.com/user-attachments/assets/9260af85-5d8b-4495-882f-ea2ee63bb709) Social-Buzz-Analysis

# Introduction:-
During my virtual intern as a data analyst at Accenture I was assigned a project for a client called Social buzz . Social Buzz is social media and content creation platform. Social Buzz posts over 1 lakh pieces of content, ranging from text, images , videos and GIFs per day. Social Buzz wanted an analysis of their content to focus on what type of ventures to promote, to target the customers.

# Visualisation
![image](https://github.com/user-attachments/assets/2bd305b1-38d7-4d15-bcbe-39852e634bd5)

# Objective:-
Analyze the three datasets—Content, Reaction, and Reaction Types—to derive the following insights:
Category-wise Scores: Calculate and evaluate the scores across different categories.
Most Popular Categories: Identify the categories that are most popular based on engagement or other relevant metrics.
Sentiment vs. Content Type: Explore the relationship between sentiment and content type.
Sentiment vs. Score: Investigate how sentiment correlates with the scores.
Month vs. Content Type: Analyze the distribution and trends of content types across different months.

# Datasets :- 
Datasets contains the following Entities:
reaction_type:- reaction type , sentiment (positive/negative/neutral), score
reaction:- content_id , user_id , reaction type(disgust, scared , dislike , love, etc) , datetime 
content:- content_id , content type(photo/video/gif/audio) , category (16 categories- studying , healthy eating , technology, food cooking etc)

# STEPS:-
# 1. Data Cleaning:
Data cleaning is significant process in data analysis. Cleaned the data by removing the blanks and null values. Also replaced inaccurate as well as inconsistent data.

# 2.Data Modelling:
Consolidated datasets into a single dataset on the basis of common entities present in datasets. Took reactions dataset as base and merged content & reaction_type datasets into it with the help of common entities content_id and reaction type. Data is aggregated to find out the key metrics out of the data.

# 3.Data Analysis & Visualization:
Aggregated the scores across 16 unique content categories to determine category-wise scores and identified the top 5 content categories based on these scores by using Excel. 
Additionally, utilized pivot tables for the following analyses:-
Sentiment Distribution by Content Type: Created a pivot table to analyze the distribution of sentiments across different content types.
Sentiment Analysis by Scores: Generated a pivot table to examine both the count and the sum of scores associated with different sentiments.
Content Type Distribution by Month: Used a pivot table to assess the number of different content types posted each month.

Visualized the result of analysis using Excel with the help of clustered column chart , clustered bar chart, bar chart and stacked column chart.

# 4.Results:-
The analysis revealed the top 5 most popular content categories and provided category-wise scores. Among 16 different categories, including Science, Technology, Fitness, and Studies, it was found that content related to Animals and Food achieved the greatest popularity, followed by Technology and Healthy Eating.
Moreover, the "photo" content type was associated with the highest number of positive sentiments, and most sentiments were linked to positive scores overall. Notably, user engagement was highest in May.
This insights helped social buzz to focus on what type of ventures to promote, to target the Customers

# Tools Used:
* MS Excel
+ MS Power BI
- MS Power Point
