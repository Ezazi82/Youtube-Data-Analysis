# Youtube-Data-Analysis
Scraping publicly available web data from Youtube to analyze video categories and trends

This project aims to analyze trends in Youtube videos by looking at Youtube's 'Popular Right Now' playlist. It contains 200 videos that are popular within the span of a week. I am scraping data from the HTML code in addition to using GoogleCollaborator's Youtube API to gather data on the view counts, channel data, and video categories from these videos. The use of Python's BeautifulSoup and Selenium libraries are new to me, as is pretty much all web-scraping, but I thought it would be a fun project to test my abilities to pick up new material and apply it. I have also used Youtube for as long as I can remember, watching everything from music videos, to comedy sketches, to informational videos, which has shaped my incessant need to learn about new things. This is somewhat of a test and a passion project for me, so hopefully you enjoy the code(?)!

Note: Essentially had to scrap the use of BeautifulSoup and Selenium due to Youtube switching their scripting language, so The API was my only option. Got a lot less data than I had hoped for from it, but still enough to hopefully make a decent model.

Note: Currently taking a lot of time and work-around. Had a lot of issues with the Youtube API, and have never done this sort of work, definitely a challenge, but enjoyable and solvable. Current variables aren't very good for predicting at all, so going to be learning some NLP to hopefully create a better model, but definetly learned a lot so far.
