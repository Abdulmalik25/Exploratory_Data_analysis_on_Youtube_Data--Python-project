# Exploratory_Data_analysis_on_Youtube_Data-Python-project
Welcome to my exploratory journey into YouTube's enigmatic data! 🌟 As YouTube decided to hide dislike counts, our project takes a closer look at the last glimpse of this data before it disappeared in Dec 2021. Using Python's powerful libraries, Pandas and NumPy, we're unpacking secrets that were once visible to all.
### Tech Stack Used
<img src="https://github.com/Abdulmalik25/Exploratory_Data_analysis_on_Youtube_Data--Python-project/assets/153974173/26b1b5f7-dd6e-498a-9c74-fbeba755a29d" alt="jupyter-notebook" width="250" height="250">


# Domain: Social Media

### Context and Content
In November 2021, YouTube announced its decision to hide dislike counts. However, until December 13, 2021, the official YouTube Data API provided access to dislike information. This project aims to conduct Exploratory Data Analysis (EDA) to uncover hidden insights from this dataset.

## Learning Outcome
- Exploratory Data Analysis using Pandas.

## Objective
The objective is to analyze the YouTube dislikes dataset using NumPy and Pandas libraries, deriving meaningful insights through EDA.

## Dataset Description

## Overview
- This dataset provides insights into trending YouTube videos from August 2020 to December 2021 in the USA, Canada, and Great Britain.
- It contains information on dislikes, likes, views, and more, collected just before December 13, 2021.
- The data covers videos that had been trending in the mentioned countries for a year prior to the collection date.

## Dataset Link
- [YouTube Dislikes Dataset on Kaggle](https://www.kaggle.com/datasets/dmitrynikolaev/youtube-dislikes-dataset)

## Attribute Information
| SL.No | Column Name    | Description                                      |
|-------|----------------|--------------------------------------------------|
|   1.   | Video ID       | Unique video id.                                 |
|   2.   | Title          | Video title.                                     |
|   3.   | Channel ID     | Id of the channel.                               |
|   4.   | Channel Title  | Title of the channel.                            |
|   5.   | Published at   | Video publication date.                          |
|   6.   | View count     | Number of views.                                 |
|   7.   | Likes          | Number of likes.                                 |
|   8.   | Dislikes       | Number of dislikes.                              |
|   9.   | Comment Count  | Number of comments.                              |
|  10.   | Tags           | Tags (in one string).                            |
|  11.   | Description    | Video description.                               |
|  12.   | Comments       | 20 Video comments (in one string).               |
### Here are some questions that I've employed to begin with the analysis of this project.

1. Import required libraries and read the provided dataset (youtube_dislike_dataset.csv) and retrieve top
5 and bottom 5 records.
2. Check the info of the dataframe and write your inferences on data types and shape of the dataset.
3. Check for the Percentage of the missing values and drop or impute them.
4. Check the statistical summary of both numerical and categorical columns and write your inferences.
5. Convert datatype of column published_at from object to pandas datetime.
6. Create a new column as 'published_month' using the column published_at (display the months only)
7. Replace the numbers in the column published_month as names of the months i,e., 1 as 'Jan', 2 as 'Feb'
and so on.....
8. Find the number of videos published each month and arrange the months in a decreasing order based
on the video count.
9. Find the count of unique video_id, channel_id and channel_title.
10. Find the top10 channel names having the highest number of videos in the dataset and the bottom10
having lowest number of videos.
11. Find the title of the video which has the maximum number of likes and the title of the video having
minimum likes and write your inferences.
12. Find the title of the video which has the maximum number of dislikes and the title of the video having
minimum dislikes and write your inferences.
13. Does the number of views have any effect on how many people disliked the video? Support your
answer with a metric and a plot.
14. Display all the information about the videos that were published in January, and mention the count of
videos that were published in January.

### Feel Free to Check out Ipynb file to find out how I performed Exploratory Data Analysis on this Youtube Data and What are the findings that Ive Unearthed from this Dataset.

# Conclusion
In conclusion, this project provides a comprehensive overview of YouTube video data, including key metrics like views, likes, dislikes, and comments. By exploring this dataset, we gain valuable insights into video trends and user engagement, enabling us to better understand YouTube content dynamics.

