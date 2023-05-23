# tiktok-discovery-api-history
This repo scrapes TikToks Web API automatically using GitHub Actions and monitors changes to its discovery endpoint on 3 different subdomains.

All pages are downloaded as JSON and prettyfied with jq. A commit is made whenever a change is detected and all changes can be viewed throughout the commit history.


## Inspiration: 
 - [Git scraping: track changes over time by scraping to a Git repository by Simon Willison](https://simonwillison.net/2020/Oct/9/git-scraping/)
 - [California fire data history](https://github.com/simonw/ca-fires-history)

## Improvements: 
 - ignore covers or just remove signature from their urls. Its not constant

---
**History:**
- `05/22/2023`: Use API params that return more data and 1080p videos
- `05/19/2023`: Re-enabled. Updated domains and added API feed
- `01/06/2023`: scrape machine broke
- `12/19/2021`: Re-enabled the workflow, test run returned good data
- `03/20/2021`: Disabled because TikTok now has captchas preventing collection of open trending data
