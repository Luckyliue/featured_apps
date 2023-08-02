# featured_apps_dataset
This repo contains the followng files:

1. rankinginfo_cn/us.csv

In this file, we list the information of "Today" page in the iOS App Store for each day (2019.1.1-2020.6.30), as well as the specific rankings of the featured apps in the week before and after being featured, including the following columns:

    date, story_id, label, appId, appName, developers, category, price, releasetime, status, offline, rankname, ranking

"date" is the date of the colletion; "story_id" is the unique identifier of the story; "label" is the name of the story; 
The following columns story the basic information of the featured apps, including app ID, app name, developer, category, price, release date, offline or online status, offline date, chart name, rankings before and after the featuring. 

2. ratinginfo_cn/us.csv

In this file, we list the specific ratings of the featured apps in the week before and after being featured. 
   
3. today_slogan_cn/us.csv

In this file, we list the specific slogans of each story on the "Today" page, including the following columns:

4.  updates_cn/us

In this directory, we provide the specific actions of each update for the featured apps.
