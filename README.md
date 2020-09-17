# IMDB_Reviews_Analysis

### Dataset -- https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews. Contains 50k reviews, 25k positive and 25k negative.

### 1. <ins>Analysis.ipynb</ins> -- Containing some basic pandas analysis, preprocessing, N-gram analysis and visualaisation.
### 2. <ins>Vader.ipynb</ins> -- Usually my first step when doing sentimental analysis. NLTK library inbuilt sentimental analyser with just few lines of codes. Performance however is not that good.
### 3. <ins>TFIDF.ipynb</ins> -- Combination of Tfidf + Logistic Regression is used in this notebook. After general pre-processing tfidf(using sklearn) is applied to the dataset and the generated featured are trained using logistic regression yielding final accuracy score of <ins>0.9026</ins> training and testing upon 90/10 ratio.
### 4. <ins>Naive_Bayes_Scratch.ipynb</ins> -- This notebook is based on <ins>Coursera's NLP Specialization</ins>. In this sentimental analysis is done using naive bayes algorithm written from scratch. Final accuracy score is <ins>0.9154</ins> which is slightly better than TFIDF. But the main advantage of this method is that it is instantaneously fast while training and testing.
        
