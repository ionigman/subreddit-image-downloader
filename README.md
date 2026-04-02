imglora-grabber (FKA ostrolucky/Simple Subreddit Image Downloader)
==========================

Downloads all directly linked images in a subreddit in parallel.
OS agnostic.

Requirements
============
- bash
- curl
- jq
- environment variable w/ username REDDIT_USERNAME, otherwise script will be blocked
  
Usage
=====
```
Usage: ./imglora_grabber.sh <subreddit_name> [hot|new|rising|top|controversial] [all|year|month|week|day] [limit]
Examples: ./imglora_grabber.sh aita new week 10     # 10 newest images from the last week from /r/aita
          ./imglora_grabber.sh selfie top all 50    # 50 all-time top images from /r/selfie
```

Downloaded images will be saved to `<subreddit_name>` in the current directory
