# Trump-Biden-Twitter-Analysis
This repository contains files related to a study of tweets written by Joe Biden and Donal Trump conducted by Lia Smith and Kayley Watson. The study utilizes R programming language for data analysis and visualization.

We chose to explore differences tweets posted by the accounts of two presidents: Donald Trump and Joe Biden. We found two data sets, one for each president. Biden’s tweets ranged from October 24th, 2007 to November 1st 2020. Trump’s tweets ranged from May 4th, 2009 to June 17th, 2020. Biden tweeted a total of 6,064 times while Trump tweeted 43,352 times. This means that there is more data from Trump’s account than Biden’s.

Because each of these tweets has multiple words in it, we needed to use some method to decrease the amount of data we were using to make the run time more manageable. Originally, it was supposed to take about 8 hours using the entirety of both data sets, so instead we decided to focus on a specific window of time that we thought would yield interesting results. We isolated a period of four months from each of the candidates: January to April of 2020. This period was after both presidents had announced they intended to run for president and it also included the beginning of the Covid-19 pandemic.

Furthermore, the decrease in data volume helped to solve the issue of class imbalance and made it so our final set had around a 60/40 split, favoring Trump. Our resulting model confirms that the case imbalance was handled well since our kappa score is 0.6971857 and accuracy is 0.8535653, which is pretty good.

Data sourced from Kaggle:
- [https://www.kaggle.com/datasets/austinreese/trump-tweets](url)
- [https://www.kaggle.com/datasets/rohanrao/joe-biden-tweets](url)
