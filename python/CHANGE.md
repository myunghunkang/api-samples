#### Step to fork a project through GitHub and clone it to local directory
1. git fork api-' sample' from https://github.com/youtube/api-samples
2. git clone git@github.com:/myunghunkang/api-samples.git 

### Enable Google OAuth


### Enable Youtube Data API,  YouTube Analytics API
- for example, "googleapiclient.errors.HttpError: <HttpError 403 when requesting https://youtubeanalytics.googleapis.com/v2/reports?ids=channel%3D%3DMINE&startDate=2017-01-01&endDate=2017-12-31&metrics=estimatedMinutesWatched%2Cviews%2Clikes%2CsubscribersGained&dimensions=day&sort=day&alt=json returned "YouTube Analytics API has not been used in project 279629651947 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/youtubeanalytics.googleapis.com/overview?project=279629651947 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.". Details: "[{'message': 'YouTube Analytics API has not been used in project 279629651947 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/youtubeanalytics.googleapis.com/overview?project=279629651947 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.', 'domain': 'usageLimits', 'reason': 'accessNotConfigured', 'extendedHelp': 'https://console.developers.google.com'}]">"
1. Project Dashboard, then (API) Library
2. Select to use YouTube Analytics API

### Add arguments
-   parser.add_argument(

### YouTube API
- https://developers.google.com/youtube/v3/docs/videos