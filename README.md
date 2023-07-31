# WatchguardRecommendationModel
Watchguard repository for the ensemble video tagging model

See slite design doc for details.
 
Add a pretrained LLAMA2 or Lavila for AI models for test if data scraping doesn't work


Highlights Tool 

Potential user interaction formula:

AUI, or Average User Interaction = (w_1*viewCount + w_2*likeCount + w_3*favoriteCount + w_4*commentCount) / 4 . w_1, w_2, w_3, w_4 are predetermined weights that will be calculated depending on historical data on how much viewCounts, likeCounts, favCounts, and commentCounts contribute to how much money the YouTuber receives overall.  For example, the YouTuber receives no money from comments but will receive a lot of money from views, therefore weight for views will be much lower compared to the weight from comments. *

*Maybe round AUI to five decimal places?


Tags in videos and how the model will correlate b/w tags and AUI:




Correlate Tags that the most popular videos every day have (or every time the most popular videos list refresh) with a comprehensive score that averages user interaction. 