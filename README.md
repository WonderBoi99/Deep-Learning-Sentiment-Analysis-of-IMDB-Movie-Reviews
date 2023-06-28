# Deep Learning Model: Sentiment Analysis of IMDB-Movie-Reviews

## Short Description:
Attempt to build a reliable Neutral Network model that can predict the correct sentiment for IMBD movie reviews.

## Code is Divided Into The Following Section:
* Collecting Data:
    * Reads the IMDB movie reviews data stored in the CSV file into a pandas DataFrame.
    * Selected 8000 reviews since the dataset was quite large and consisted of 25,000 reviews.
    * Checked if the dataset labels were balanced.
    * Separated main Dataframe into two: reviews (features) and sentiment (labels).
* PreProcessing The Data For ML:
   * Used BeautifulSoup to parse the HTML content from the raw review data and collect the text content.
   * Tokenized the text content then:
      * Removed punctuation
      * Removed stopwords
      * Removed non-alphabetic words
      * Used SnowBallStemmer to stem each word
   * Joined the list of preprocessed words   
* Prepare Data For Neutral Network:

* Time To Apply Neutral Network:

