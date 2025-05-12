# Stash-Scrapers

Scrapers for Stash. Here I will keep the scrapers that I make edits to (as it seems to me for a better job).  I will try to send corrections to https://github.com/stashapp/CommunityScrapers


Scrapers Themoviedb

I have made corrections that should correctly transmit the date to stash

Scrapers Pornolab

Improved the logic of getting the name;
I have improved the logic of obtaining images (at the beginning we get the left image, if there is none, then the right one. If there is no such thing, then look at what images there are, if there are several, random selection will work, restarting the information will help to get another image. Also, the scraper will not receive animated images and information located below the block.;
Improved the logic of obtaining useful information. Now there are more chances to get information from the page.
Fixed the scraper so that it doesn't get an error when receiving data it can't understand.
