# yt-subs-to-ftrss

## Description
This tool helps you to generate [Full-Text-RSS](https://www.fivefilters.org/full-text-rss/) links from your youtube subscriptions, allowing you to transfer from Youtube feed to an RSS-feed like [FreshRSS](https://www.freshrss.org/). It is meant to be used as an export tool when initially switching to an RSS-Feed from the youtube feed.

## Instructions
### Obtaining the subscription export from Google
1. Export your youtube subscriptions with [Google Takeout](https://takeout.google.com/)
2. Click "Deselect all"
3. Select only "Youtube and Youtube Music" at the bottom of the page
4. Click on "All data included" beneath the Youtube section
5. Click "Deselect all"
6. Select only "Subscriptions"
7. Click on next step, leave default config and export
8. Download the resulting zip-archive from your google-e-mail

# Generating FTRSS-Links
1. In the ZIP, extract the Subs.csv (under Takeout/YOutube and Youtube Music/Subscriptions) and place it in the yt-subs-to-ftrss-folder
2. Run the "exporter"-file
3. When prompted, insert your FTRSS-Domain (e. g. ftrss.mydomain.com or the address to any of the public instances, but then the articles per feed might need to be adjusted)
4. A list of FTRSS-Links will be saved to a file "feedlinks"
