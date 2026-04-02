imglora-grabber (FKA ostrolucky/Simple Subreddit Image Downloader)
==========================

Downloads all directly linked images in a subreddit in parallel.
OS agnostic.

Requirements
============
- bash
- curl
- jq
- set environment variable with your reddit username at REDDIT_USERNAME
  
Usage
=====
```
Usage: ./imglora_grabber.sh <subreddit_name> [hot|new|rising|top|controversial] [all|year|month|week|day] [limit]
Examples: ./imglora_grabber.sh aita new week 10 # 10 newest images from the last week
          ./imglora_grabber.sh selfie top all 50 # 50 all-time top images"
```

Script downloads images to `<subreddit_name>` folder in current directory. If you want to change that, you need to edit destination in rdit.sh for now.
