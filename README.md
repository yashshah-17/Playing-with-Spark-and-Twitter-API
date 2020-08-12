# Word-Occurence-Sentiment-Analysis
This model extract tweets and news articles related to a set of words and performs sentiment analysis on it. It extracts the tweets using the Twitter API and the News articles
using the News API. After storing this data in csv files, it is preprocessed to get it cleaned and formatted. Post that, they are stored in MongoDB from where they are imported to
Tableau to visualize the most common words using a word graph. Lastly, a program is executed on Spark in AWS EC2 to find the occurrences of the given set of words.

## How to run the model
This model is created using Jupyter notebook, and hence each individual file has a step-by-step (one cell after another) execution process. Run the files in the order as follows:
1. Twitter-extractor
2. News-extractor
3. Content-Cleaner
4. MongoDB Data Loader

## Additional guidelines
To get a better idea of what the model does and how the implementation is carried out refer the Assignment Report PDF inside the repository.
