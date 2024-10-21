# Tiktok-Project-EDA
The purpose of this project is to conduct exploratory data analysis on Tiktok video data

The project is based on the Project Question:
You have just started as a data professional at TikTok.

The team is still in the early stages of the project. You have received notice that TikTok's leadership team has approved the project proposal. To gain clear insights to prepare for a claims classification model, TikTok's provided data must be examined to begin the process of exploratory data analysis (EDA).

Orion Rainier, a Data Scientist at TikTok, is pleased with the work you have already completed and is requesting your assistance with some Data wrangling and data visualization. The management team asked to see a Python notebook showing data structuring and cleaning, as well as any matplotlib/seaborn visualizations plotted to help us understand the data. At the very least, include a graph comparing claim counts to opinion counts, as well as boxplots of the most important variables (like “video duration,” “video like count,” “video comment count,” and “video view count”) to check for outliers. Also, include a breakdown of “author ban status” counts.

Data sources used

This project uses a dataset called tiktok_dataset.csv. It contains synthetic data created for this project in partnership with TikTok. Below are the variables in the data you will be working with.

Data Dictionary

Field	Description
#	     TikTok assigned number for video with claim/opinion.
claim_status	Whether the published video has been identified as an “opinion” or a “claim.” In this dataset, an “opinion” refers to an individual’s or group’s personal belief or thought. A “claim” refers to information that is either unsourced or from an unverified source.
video_id	Random identifying number assigned to video upon publication on TikTok
video_duration_sec	How long the published video is measured in seconds
video_transcription_text	Transcribed text of the words spoken in the published video
verified_status	Indicates the status of the TikTok user who published the video in terms of their verification, either “verified” or “not verified.”
author_ban_status	Indicates the status of the TikTok user who published the video in terms of their permissions: “active,” “under scrutiny,” or “banned.”
video_view_count	The total number of times the published video has been viewed.
video_like_count	The total number of times the published video has been liked by other users.
video_share_count	The total number of times the published video has been shared by other users.
video_download_count	The total number of times the published video has been downloaded by other users
video_comment_count	The total number of comments on the published video.
Business Task

In this activity, you will examine data provided and prepare it for analysis. You will also design a professional data visualization that tells a story, and will help data-driven decisions for business needs.

The purpose of this project is to conduct exploratory data analysis on a provided data set. Your mission is to continue the investigation you began in C2 and perform further EDA on this data with the aim of learning more about the variables. Of particular interest is information related to what distinguishes claim videos from opinion videos.

The goal is to explore the dataset and create visualizations.


This activity has 4 parts:

Part 1: Imports, links, and loading

Part 2: Data Exploration

Data cleaning
Part 3: Build visualizations
