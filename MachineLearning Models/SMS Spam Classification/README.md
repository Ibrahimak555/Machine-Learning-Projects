# SMS Spam Classifier

  We use the dataset 'spam.csv' which contains '5572' SMS text messages and label each of them as either 'Spam' or 'Ham'.

  Data Cleaning is required as the dataset contains additional attributes with NaN value, and also contains some duplicate values.

  Analysis of the data with the number of characters, words, and sentences in a single message reveals the high correlation between 
the number of characters and number of words in each message.

  Now transform data into a more concise form, by removing stopwords and stem them to their root form. 

  Applying various models will show us that Naive Bayes Approach is one of the best approach, with an Accuracy at 97.2% and Precision at 100%.
Or use the Voting classifier of SVM, NB and ET, which shows promising results, with an Accuracy at 98.16% and Precision at 99.17%.
