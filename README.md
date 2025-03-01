# markov-tweets
## Berkeley EECS 126 (Probability and Random Processes) Project

Investigating applications of Markov Chains in language by building a Markov Chain to characterize Donald Trump's tweeting style, and subsequently randomly walking along this chain to generate fake tweets. The theory behind this application is [Maximum Likelihood Estimation for Markov Chains](https://www.stat.cmu.edu/~cshalizi/462/lectures/06/markov-mle.pdf).

Code can be found [here](https://github.com/keyan3/markov-tweets/blob/master/code/MCMC-Trump-Tweets.ipynb). The primary steps involved were building the Tweet dataset by scraping Tweets from Twitter's API, cleaning/processing the dataset to prepare it for analysis, building the Markov chain through MLE, and finally walking along the chain to generate Tweets. 

Project spec can be found [here](https://d1b10bmlvqabco.cloudfront.net/attach/jiow4wnlt5e4v9/is6p9d0f5p6m3/jnb3s0iqngli/project_proposal.pdf), and full project writeup with explanation of theory, code and results can be found [here](https://github.com/keyan3/markov-tweets/blob/master/writeup/EECS_126_Project_Report%20(1).pdf). Some selected Tweets generated by the chain are displayed below.

### Selected results:

![alt text](https://raw.githubusercontent.com/keyan3/markov-tweets/master/writeup/BEST.png)
