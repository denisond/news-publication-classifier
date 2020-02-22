# news-publication-classifier
Natural language processing project in Ipython notebooks. Notebook contains EDA and author classifier for news articles. 

### main.ipynb
1. Read-in and preprocess data:<br>
    a. Look for analysis sample based on article length and number of articles<br>
    b. Randomly sample articles from several authors<br>
2. Clean data:<br>
    a. Remove punctuation<br>
    b. Lemmatize<br>
    c. Label encoding<br>
    d. Split and Term Frequency Inverse Document Frequency vectorization<br>
3. Analysis:<br>
    a. Run chi-2 test to check for unigrams and bi-grams most strongly correlated with author labels<br>
    b. Run dimension reductionality techniques (PCA, TSNE, and LDA) on data and plot<br>
    c. Run several baseline models/pipelines<br>
    d. Tune hyperparameters for best candidates models with grid search<br>
