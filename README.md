# Youtube-Data-Analysis
Scraping publicly available web data from Youtube to analyze video categories and trends

I had started this project with the initial goal to see if I could predict a videos virality based on a number of collected variables, however as I went along with the project, I found that to be not as feasable of a goal given the variables I could scrape, so I switched my goal to attempt to predict a videos genre based on its description.

I had trouble attempting to scrape data at first, learning the beautifulsoup4 and selenium libraries from Python (along with some html) in the process, however I eventually realized that I would need to use YouTube's API in order to accomplish my goal. After working this out, I found that I could only get so many useful variables to predict video virality from the top 200 trending videos playlist I was able to scrape.

I performed some EDA and plenty of data cleaning before finally jumping in to model creation and prediction, which also did not go nearly as well as I had hoped. The genres for the data I collected had quite a few rows that had multiple categories associated with them. It turns out that multi-level classification problems are notoriously difficult. I ended up attempting to make 2 models, one with a technique called One vs. Rest, and another with a technique called Label Powerset. The One vs. Rest model was relatively good at predicting categories independent of others, with most having an accuracy of over 80%. The Label Powerset method however, was much weaker and attempts to predict categories dependent on one another.

Overall, this project was difficult, a little over my head, but enjoyable. It certainly taught me a lot and it was something that interested me, so overall I am happy with it, and hope that anyone that sees this can improve upon it or is inspired otherwise.
