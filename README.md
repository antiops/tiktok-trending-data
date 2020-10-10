# tiktok-discovery-api-history

This repo scrapes TikToks Web API automatically using GitHub Actions and monitors changes to its discovery endpoint on 3 different subdomains.

All pages are downloaded as JSON and prettyfied with jq. A commit is made whenever a change is detected and all changes can be viewed throughout the commit history.


Inspiration: https://simonwillison.net/2020/Oct/9/git-scraping/ & https://github.com/simonw/ca-fires-history
