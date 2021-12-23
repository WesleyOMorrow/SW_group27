Public repository for the Social Web course at VU University
# Project
## Notebooks
### Video Crawler 
- fetch_video_list_final.ipynb
- filter_vidlist.ipynb

Read files generated by fetch_video_list_final.ipynb, output video's information in a time period to help us do manual screening of videos.

### Comments Retrieval
- youtube_retrieval.ipynb
- 
Read the video list after manual selection, and generated comments.csv
### Sentiment Analysis
- Fine_grained_Sentiment_Analysis.ipynb

Sentiment analysis based on sentiment dictionary, includes 8 emotions. Read NRC.xlsx and all_comments.csv, analyze the sentiment contained in each video comment.

- Semantic_Level_Sentiment_Analysis.ipynb

Sentiment analysis based on deep learning, used Sparknlp pipeline. Read all_comments.csv, analyze whether each comment is positive or negative.
### LDA
- youtube_comments_analyzer_LDA.ipynb, used spark nlp to do the data preprocess, spark ml to do topic modeling
### Toxic Comments
- youtube_comments_analyzer.ipynb, read comments.csv, used Sparknlp pipeline.


## Data
### The video list after manual selection
- BBC_videos_final.csv
- Guardian_videos_final.csv
- DailyMail_videos_final.csv
- Sun_videos_final.csv
- Independent_videos_final.csv

### Comments data retrieved from youtube
- comments.csv

## Essential packages
- googleapiclient
- pyspark==3.1.2
- sparknlp
- matplotlib 
- pandas 
- wordcloud
