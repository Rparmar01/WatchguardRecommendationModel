# WatchguardRecommendationModel
Watchguard repository for the ensemble video tagging model

See slite design doc for details.
 
Add a pretrained LLAMA2 or Lavila for AI models for test if data scraping doesn't work









Highlights Tool 
We want to make starting a YouTube career easier. We also want to make growing a YouTube channel easier for all YouTube channels. 

In order to do this, let’s take the most successful YT videos and find what common elements they share. Once we do, find a way to detect those elements in YT recordings. One option is to train a YT model on videos containing this/these element(s) of successful videos, so the model will predict the presence of these elements in recorded footage. Recorded footage refers to unedited video content a YTber is planning to edit and upload to YouTube. 




Potential user interaction formula:

AUI, or Average User Interaction = (w_1*viewCount + w_2*likeCount + w_3*favoriteCount + w_4*commentCount) / 4 . w_1, w_2, w_3, w_4 are predetermined weights that will be calculated depending on historical data on how much viewCounts, likeCounts, favCounts, and commentCounts contribute to how much money the YouTuber receives overall.  For example, the YouTuber receives no money from comments but will receive a lot of money from views, therefore weight for views will be much lower compared to the weight from comments. *

*Maybe round AUI to five decimal places?


Tags in videos and how the model will correlate b/w tags and AUI:




Correlate Tags that the most popular videos every day have (or every time the most popular videos list refresh) with a comprehensive score that averages user interaction. 