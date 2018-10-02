# youtube-dl-subscriptions

Downloads all new videos from your YouTube subscription feeds.


## Requirements

This script requires python3. Additional dependencies can be found in the `requirements.txt` file.


## Usage

Clone the repository

    git clone https://github.com/mewfree/youtube-dl-subscriptions

Install the requirements

    pip install -r requirements.txt

Download your YouTube's subscriptions OPML file by visiting [this URL](https://www.youtube.com/subscription_manager?action_takeout=1). Save the file as `subs.xml` into the cloned repository folder.

You can then run the script

    python3 dl.py

A `last.txt` file will be created in order to avoid downloading the same videos on the next run.
