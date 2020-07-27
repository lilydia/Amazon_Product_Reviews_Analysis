# Amazon Product Reviews Analysis | Natural Language Processing

For this example, we are examining a dataset of Amazon product reviews which can be accessed at http://deepyeti.ucsd.edu/jianmo/amazon/. Python analytical packages used include **nltk, pandas, matplotlib,etc.**

The following workflow is what I used to perform loading, cleaning, transforming, and sentiment analysis on the dataset:
1. Loading JSON file as pandas dataframe
2. Cleaning for null, unformatted reviews
3. Removing punctuations and stopwords
4. Stemming and lemmatizing
5. Testing sentiment analysis model
6. Visualizing results

**For details, please see "SentimentAnalysis_Py.ipynb" listed above.**

To compare the effect of data processing on final outcomes, we ran the algorithm under 3 circumstances and summary of results is presented as follows:

1. Without stemming and lemmatizing(converting words to root form)

| Sentiment | NUMBER OF REVIEWS |
| ------------- | ------------- |
| POSITIVE  | 3166 |
| NEGATIVE  | 319 |
| NEUTRAL  | 15152 |

2. WIth stemming only

| Sentiment | NUMBER OF REVIEWS |
| ------------- | ------------- |
| POSITIVE  | TBD |
| NEGATIVE  | TBD |
| NEUTRAL  | TBD |

3. WIth lemmatizing only

| Sentiment | NUMBER OF REVIEWS |
| ------------- | ------------- |
| POSITIVE  | TBD |
| NEGATIVE  | TBD |
| NEUTRAL  | TBD |





