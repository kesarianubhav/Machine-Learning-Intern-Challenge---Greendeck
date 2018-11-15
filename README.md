# Machine-Learning-Intern-Challenge---Greendeck

The repository is dedicated to the challenge for intern at Greendeck for the position of Deep Learning Position.

Kaggle Notebook@ -> https://www.kaggle.com/kesarianubhav/ml-task?scriptVersionId=7425868#

Brief Approach used while Implementing the Solution:

Step 1 . Loading The Data , checking the data if there is any column missing , In this Dataset We didn't had.

Step 2 . Exploratory Analysis of Data-
         - Finding the relative percentage of categories 
         - Finding which words appear most , using the WordCloud
         - Finding which author uses which word most
         
Step 3 . Data Preprocessing
        Creating a new column called news which contains headline and the short description.
        - Decontraction Mapping i.e. converting common contractions like i'll to i will , i've to i have
        - Punctuating Cleaner - Cleaner Punctuation Words
        - Stopword Cleaner - Cleaning StopWords , using nltk english stopwords
        - Tokenization - Breaking the Sentences into Words
        - Capital Case to Lower Case
        - Stemming - reducing to base form
        - Lemmatization - reducing to base form using POS tagging
        
Step 4 - Data Preparation
        - Creating embedding index
        -Creating Embedding Matrix using Embedding indices
        -Label Encoding category
        -One Hot Encoding of Category column values
     
Step 5- Creating Embedding Layer for the Input Text

Step 6- Defining RNN model
      - Defining the Model 
      - Training using training input
      
Step 7 - Improving Accuracy by Hyperparameter Optimization

