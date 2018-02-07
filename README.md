# youtube-dl-subscriptions
Downloads all new videos from your YouTube subscription feeds.

Requires Python 3 to run!

I recommend to create a new folder and place the dl.py inside. You will also need a OPML file named subs.xml containing all your YouTube's subscriptions in the same folder. You can download it from https://www.youtube.com/subscription_manager?action_takeout=1 when you're logged in your YouTube account. The script will create a last.txt file inside the folder in order to remember when it was last run and not re-download the same videos again.

Requirements:
* Python 3

Dependencies:
* opml
* feedparser
* youtube-dl
