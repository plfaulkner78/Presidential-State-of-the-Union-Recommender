# Presidential State of the Union Recommender

Remember when Nancy Pelosi ripped up Trump’s State of the Union speech? She obviously didn’t like the speech, so I started wondering, what other State of the Union addresses would she rip up if she could go back in time? Well, with some basic NLP tools, I created a speech recommender system that Speaker Pelosi can use to find State of the Union addresses similar to Trump’s 2020 address. 

All jokes aside, for this project I used a corpus of every presidential State of the Union address from 1790-2020. After some data preparation steps, I conducted an analysis of speech length, readability, and word popularity by comparing these metrics between parties and time periods. I found a number of interesting trends and learned some historical trivia through this analysis. Most importantly though, I created a fairly simple content-based recommendation system that can look at a State of the Union address and return to you the 10 most similar speeches.

To run this code, first download the dataset from the Kaggle link below. This will contain one .txt file for every speech. Also, this dataset is missing the speeches from 1790, 2019, and 2020, so you can create .txt files yourself using the transcripts found at the designated links.

Data Sources:

Speeches from 1791-2018: https://www.kaggle.com/rtatman/state-of-the-union-corpus-1989-2017

1790 address: https://www.mountvernon.org/education/primary-sources/state-of-the-union-address

2019 address: https://www.whitehouse.gov/briefings-statements/president-donald-j-trumps-state-union-address-2/

2020 address: https://www.whitehouse.gov/briefings-statements/remarks-president-trump-state-union-address-3/
